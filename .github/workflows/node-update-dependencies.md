name: Update

on:
  schedule:
  - cron: 0 0 * * 3
  workflow_dispatch:
  
permissions:
  contents: write
  pull-requests: write

jobs:
  package-update:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@master
    
    - name: set remote url
      run: git remote set-url --push origin https://$GITHUB_ACTOR:${{ secrets.GITHUB_TOKEN }}@github.com/$GITHUB_REPOSITORY
      
    - name: package-update
      uses: taichi/actions-package-update@master
      env:
        AUTHOR_EMAIL: author@example.com
        AUTHOR_NAME: author
        EXECUTE: "true"
        GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        LOG_LEVEL: debug
      with:
        args: -u --packageFile package.json --loglevel verbose
