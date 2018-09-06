# eslint-config-opentable-es5

This package provides a standard Opentable .eslintrc as an extensible shared config. It's built around airbnbs style guide

Requires `eslint`, `^2.0.0 || ^3.0.0`
Requires `eslint-plugin-mocha`, `^3.0.0 || ^4.0.0`

## Usage

```shell
npm install --save-dev eslint-config-opentable-es5
```

add `"extends": "eslint-config-opentable-es5"` to your .eslintrc

If using babel:

add `"parser": "babel-eslint"` to your .eslintrc

## Changelog

### 0.8.0
 - removed a deprecated option.
### 0.7.0
 - added support for `eslint-plugin-mocha` `v4`.
### 0.6.0
 - add new rule: error callbacks must be handled.

### 0.5.0
 - added object-shorthand and prefer-const rules

### 0.4.0
 - env explicitly set to es6
 - ecmaVersion set to 7
 - eslint-plugin-mocha-only replaced by eslint-plugin-mocha

### 0.2.0
 - remove parser from eslint, upgrade rules to 2.0

### 0.1.2
 - add .npmrc for artifactory deploys

### 0.1.1
 - reorganize, add ES6/ES7 rules

### 0.0.2
 - add usage notes to readme

### 0.0.1
 - initial release
