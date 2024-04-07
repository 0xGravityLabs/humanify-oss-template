# humanify-oss-template

> Follow this template and complete todos. DON'T leave any template related content.

- [ ] read *Dev Specification* and *OSS Engineering* carefully, which mentioned how to write sound readme and contributing docs
- [ ] rewrite readme.md([shields](https://github.com/badges/shields), lanuage, slogan, competing products, demos in GIF/SPA, contributors(refer to insights section), routing to getting-started/API-reference/contributing)
- [ ] rewrite CONTRIBUTING.md
- [ ] configure dependabot: goto 'setting' and enable all dependabot items
- [ ] configure git hooks(e.g. `cp hooks/commit-msg .git/hooks/commit-msg`)
- [ ] check license
- [ ] workflow related items: 
  - [ ] replace the 'package-ecosystem' in .github/dependabot.yml with your language-specific package manager
  - [ ] replace the 'release-type' in .github/release.yml with your language-specific value([refer here](https://github.com/googleapis/release-please?tab=readme-ov-file#strategy-language-types-supported))
  - [ ] rewrite the issue and pr templates in .github if needed

# Version Releasement(DELETEME)

The version release schema is based on [release-please](https://github.com/googleapis/release-please). To release a new version just push to the `main` branch with a conventional commit with type `feat`, `fix` or `!`. And then the CI/CD workflow will be triggered resulting in a pull request whose changes are about the changelogs and version update proposed by the bot. Squash and merge the pull request so that a new version is released.