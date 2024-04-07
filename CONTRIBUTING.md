# Contributing Guidelines

Contributions are welcome!

**Please review this page carefully so that your contributions are standard and more likely to be merged.**

Please follow [Code of Conduct](http://contributor-covenant.org/).

## Issue & PR Guide

You can submit issues on [bugs](https://github.com/0xGravityLabs/humanify-oss-template/issues/new?assignees=&labels=&projects=&template=bug_report.md&title=) or [new features](https://github.com/0xGravityLabs/humanify-oss-template/issues/new?assignees=&labels=&projects=&template=feature_request.md&title=). Remember to follow the issue template.

### Pull Requests

1. Fork the [main repository](https://github.com/0xGravityLabs/humanify-oss-template). Click on the 'Fork' button near the top of the page.  This creates a copy of the repository under your account on the GitHub server.

2. Clone this copy to your local disk:

        $ git clone git@github.com:<your-account>/<your-project>.git
        $ cd <your-project>

3. Create a branch to hold your changes and start making changes. Don't work in the `main` branch! You can refer to the [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) for more understanding on large scale software management.

        $ git checkout -b feature/{your-name}/{feature-name}

4. Work on this copy. When you're done, run the following to record your changes in Git. Remember to use [conventional commit messages](https://www.conventionalcommits.org/en/v1.0.0/) to format your comments of changes.

        $ git add <modified-files>
        $ git commit -m <commit-message>

5. Push your changes to GitHub with:

        $ git push -u origin feature/{your-name}/{feature-name}

6. Finally, go to the web page of your fork of the repo and click 'Pull Request' to send your changes for review.

## Development Setup

Talk about how to configure the environment so that developers can run the project and get hands dirty.

For instance, you can tell the prerequisites like what OS systems are supported, which language package managers are under use, the versions of your toolchain, and how to get these stuff.

After that, tell how to build the whole project, run tests, etc..

## Project Structure

You can use the `tree` command to visualize your project structure and explain functions of each folder, sub folder, for developers to understand your project. Here are examples from [vuejs](https://github.com/vuejs/vue/blob/dev/.github/CONTRIBUTING.md).

> - packages: contains vue-server-renderer and vue-template-compiler, which are distributed as separate NPM packages. They are automatically generated from the source code and always have the same version with the main vue package.
> - test: contains all tests. The unit tests are written with Jasmine and run with Karma. The e2e tests are written for and run with Nightwatch.js.

The `scripts` parts should be paid attention to since it's frequently used by developers to automate their local workflows.
