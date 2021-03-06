# eslint-config-zhike

## Eslint rules for zhike

<!-- Badges section here. -->
![codestyle](https://img.shields.io/badge/codestyle-%40zhike-green.svg)
![travis](https://travis-ci.org/zhike-team/eslint-config-zhike.svg?branch=master)
![npm](https://img.shields.io/npm/v/@zhike/eslint-config.svg)
![npm](https://img.shields.io/npm/v/@zhike/eslint-config/next.svg)
![npm](https://img.shields.io/npm/l/@zhike/eslint-config.svg)
![npm](https://img.shields.io/npm/dm/@zhike/eslint-config.svg)

[![GitHub forks](https://img.shields.io/github/forks/zhike-team/eslint-config-zhike.svg?style=social&label=Fork)](https://github.com/zhike-team/eslint-config-zhike/fork)
[![GitHub stars](https://img.shields.io/github/stars/zhike-team/eslint-config-zhike.svg?style=social&label=Star)](https://github.com/zhike-team/eslint-config-zhike)

### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for [Zhike Team](https://github.com/zhike-team)

## Install

```bash
npm install --save-dev @zhike/eslint-config
```

or

```bash
yarn add -D @zhike/eslint-config
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the Zhike JavaScript Style shareable config, first run this:

```bash
npm install --save-dev @zhike/eslint-config\
  eslint-config-standard\
  eslint-plugin-standard\
  eslint-plugin-promise\
  eslint-plugin-import\
  eslint-plugin-node
  eslint
```

Then, add this to your .eslintrc file:

```json
{
  "extends": "@zhike"
}
```

*Note: We omitted the `/eslint-config` suffix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## Badge

You can add a badge to your README.md file now.

With code:

```markdown
![codestyle](https://img.shields.io/badge/codestyle-%40zhike-green.svg)
```

It looks like ![codestyle](https://img.shields.io/badge/codestyle-%40zhike-green.svg)

## Contribute

[Contribute Guide](./CONTRIBUTING.md)

## License

MIT. Copyright (c) [Zhike](http://www.smartstudy.com).