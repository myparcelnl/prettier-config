# @myparcel/prettier-config

[![NPM version](https://img.shields.io/npm/v/@myparcel/prettier-config)](https://www.npmjs.com/package/@myparcel/prettier-config/)

## Installation

Using Yarn:

```shell
yarn add -D @myparcel/prettier-config
```

Using NPM:

```shell
npm i -D @myparcel/prettier-config
```

## Usage

Add this to your `package.json`:

```json
{
  "prettier": "@myparcel/prettier-config"
}
```

And you're good to go! There are a few more specific configurations below.

### ES5

```json
{
  "prettier": "@myparcel/prettier-config/es5"
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
  "prettier": "@myparcel/prettier-config/vue"
}
```

### Difference from the default configuration

```diff
- bracketSpacing: false
+ bracketSpacing: true
```
