# humanify-oss-template

> Follow this template and complete todos. DON'T leave any template related content like this message.

> Other shields can be found [here](https://shields.io/badges/git-hub-license). Shields about social medias, statistic data, tests are favored.

<a href="https://github.com/0xGravityLabs/humanify-oss-template/actions/workflows/release-please.yml"><img src="https://img.shields.io/github/actions/workflow/status/0xGravityLabs/humanify-oss-template/release-please.yml"></a>
<a href="https://github.com/0xGravityLabs/humanify-oss-template"><img src="https://img.shields.io/github/license/0xGravityLabs/humanify-oss-template"></a>
<a href="https://github.com/0xGravityLabs/humanify-oss-template"><img src="https://img.shields.io/github/v/release/0xGravityLabs/humanify-oss-template"></a>

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
  - [ ] Rewrite the issue and PR templates in .github if needed
  - [ ] Add language-specific implmentations in .github/workflows/test.yml, e.g. lint, e2e tests, fuzz tests

### Development Specification

- Follow [conventional commits](https://www.conventionalcommits.org) to write standard commit messages that can turn to changelogs automatically
  - `feat(api)!: send an email to the customer when a product is shipped`
  - `fix: prevent racing of requests`
  - `docs: correct spelling of CHANGELOG`
- Follow [Gitflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) or other branch model to organize your branches
  - `feat/myself/txt2img-midjourney`
  - `fix/myself/oom-outpaint`
- Use [Github Project](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) or other tools like [Jira](https://www.atlassian.com/software/jira) for project management
- Use [Github Actions](https://docs.github.com/en/actions) or other CI/CD solutions to automate your workflow, including build, test, etc.
- Use [Dependabot](https://docs.github.com/zh/code-security/getting-started/dependabot-quickstart-guide) or other security tools like [CodeQL](https://docs.github.com/en/code-security/code-scanning/introduction-to-code-scanning/about-code-scanning-with-codeql) to find out vulnerable dependencies or implementations
- Follow [RF3986](https://www.rfc-editor.org/rfc/rfc3986) to standerize URLs
  - `https://domain/v1/get-user?user_id=xxxx&other_params=xxxx`

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
