# @myparcel-dev/prettier-config

[![NPM version](https://img.shields.io/npm/v/@myparcel-dev/prettier-config)](https://www.npmjs.com/package/@myparcel-dev/prettier-config/)

## Installation

Using Yarn:

```shell
yarn add -D @myparcel-dev/prettier-config
```

Using NPM:

```shell
npm i -D @myparcel-dev/prettier-config
```

## Usage

Add this to your `package.json`:

```json
{
  "prettier": "@myparcel-dev/prettier-config"
}
```

And you're good to go! There are a few more specific configurations below.

### ES5

```json
{
  "prettier": "@myparcel-dev/prettier-config/es5"
}
```

#### Difference from the default configuration

```diff
- trailingComma: 'all'
+ trailingComma: 'es5'
```

### Vue

```json
{
  "prettier": "@myparcel-dev/prettier-config/vue"
}
```

### Difference from the default configuration

```diff
- bracketSpacing: false
+ bracketSpacing: true
```
