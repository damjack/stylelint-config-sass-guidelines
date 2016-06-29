# stylelint-config-sass-guidelines 
[![NPM version](http://img.shields.io/npm/v/stylelint-config-sass-guidelines.svg)](https://www.npmjs.org/package/stylelint-config-sass-guidelines) [![Build Status](https://travis-ci.org/bjankord/stylelint-config-sass-guidelines.svg?branch=master)](https://travis-ci.org/bjankord/stylelint-config-sass-guidelines)

> Sass Guidelines shareable config for stylelint.

A stylelint config based on [sass-guidelin.es](https://sass-guidelin.es/)

## Installation

```console
$ npm install --save stylelint-config-sass-guidelines
```

## Usage

Set your stylelint config to:

```json
{
  "extends": "stylelint-config-sass-guidelines"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs and turn off the `number-leading-zero` rule:


```json
{
  "extends": "stylelint-config-sass-guidelines",
  "rules": {
    "indentation": "tab",
    "number-leading-zero": null
  }
}
```

## [Changelog](CHANGELOG.md)

## [License](LICENSE)
