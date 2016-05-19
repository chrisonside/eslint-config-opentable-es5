# eslint-config-opentable-es5

This package provides a standard Opentable .eslintrc as an extensible shared config. It's built around airbnbs style guide

Requires eslint v2.

## Usage

```shell
npm install --save-dev eslint-config-opentable-es5
```

add `"extends": "eslint-config-opentable-es5"` to your .eslintrc

If using babel:

add `"parser": "babel-eslint"` to your .eslintrc

## Changelog

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
