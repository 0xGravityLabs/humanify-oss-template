# humanify-oss-template

> Follow this template and complete todos. DON'T leave any template related content like this message.

> Other shields can be found [here](https://shields.io/badges/git-hub-license). Shields about social medias, statistic data, tests are favored.

<a href="https://github.com/0xGravityLabs/humanify-oss-template/actions/workflows/release-please.yml"><img src="https://img.shields.io/github/actions/workflow/status/0xGravityLabs/humanify-oss-template/release-please.yml"></a>
<a href="https://github.com/0xGravityLabs/humanify-oss-template"><img src="https://img.shields.io/github/license/0xGravityLabs/humanify-oss-template"></a>
<a href="https://github.com/0xGravityLabs/humanify-oss-template"><img src="https://img.shields.io/github/v/tag/0xGravityLabs/humanify-oss-template"></a>

> Add other translations or delete this section

*[English](./README.md) | [Add Translation]()*

Help us [translate]().

## Template Specification

- [ ] Rewrite [README.md](./README.md)
- [ ] Rewrite [CONTRIBUTING.md](./CONTRIBUTING.md)
- [ ] Configure dependabot: goto 'setting' and enable all dependabot related items
- [ ] Configure git hooks(e.g. `cp hooks/commit-msg .git/hooks/commit-msg`)
- [ ] Check license
- [ ] Check rulesets on branches
- [ ] Workflow related items: 
  - [ ] Replace the 'package-ecosystem' in .github/dependabot.yml with your language-specific package manager
  - [ ] Replace the 'release-type' in .github/release.yml with your language-specific value([refer here](https://github.com/googleapis/release-please?tab=readme-ov-file#strategy-language-types-supported))
  - [ ] Rewrite the issue and pr templates in .github if needed
  - [ ] Add language-specific implmentations in .github/workflows/test.yml, e.g. lint, e2e tests, fuzz tests

### Version Releasement

The version release schema is based on [release-please](https://github.com/googleapis/release-please). To release a new version just push to the `main` branch with a conventional commit with type `feat`, `fix` or `!`. And then the CI/CD workflow will be triggered resulting in a pull request whose changes are about the changelogs and version update proposed by the bot. Squash and merge the pull request so that a new version is released.

## Introduction

Come up with a slogan and brief descriptions about your product here.

Use a video/[online demo](https://tedyin.com/archive/snow-bft-demo/#/snow) to illustrate your product. Don't forget to post a screenshot here.

## Documentation

Talk about your documentation system, and route to [Getting Started](), [API Reference](), [Contributing](./CONTRIBUTING.md) or something else.

## FAQ

Use issues to construct this section. 

## Contribution

Feel free to pull requests to help better our project. Before you start make sure you have reviewed the [Contributing Guidelines](CONTRIBUTING.md).

<a href="https://github.com/0xGravityLabs/humanify-oss-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=0xGravityLabs/humanify-oss-template" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
