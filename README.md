# semantic-release-config

[![Greenkeeper badge](https://badges.greenkeeper.io/traverson/semantic-release-config.svg)](https://greenkeeper.io/)

[Shareable semantic-release config](https://semantic-release.gitbook.io/semantic-release/usage/shareable-configurations)
for the [traverson organization](https://github.com/traverson)

<!-- status badges -->
[![Build Status][ci-badge]][ci-link]

## Usage

<!-- consumer badges -->
[![npm][npm-badge]][npm-link]
[![MIT license][license-badge]][license-link]

### Installation

```sh
$ npm install @traverson/semantic-release-config
```

### Add to project config file

In a `.releaserc.json` file in the root pf the project:

```json
{
  "extends": "@traverson/semantic-release-confg"
}
```

## Contributing

<!-- contribution badges -->
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![PRs Welcome][PRs-badge]][PRs-link]

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[npm-link]: https://www.npmjs.com/package/@traverson/semantic-release-config
[npm-badge]: https://img.shields.io/npm/v/@traverson/semantic-release-config.svg
[license-link]: LICENSE
[license-badge]: https://img.shields.io/github/license/traverson/semantic-release-config.svg
[ci-link]: https://travis-ci.com/traverson/semantic-release-config
[ci-badge]: https://img.shields.io/travis/com/traverson/semantic-release-config/master.svg
[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[semantic-release-link]: https://github.com/semantic-release/semantic-release
[semantic-release-badge]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
