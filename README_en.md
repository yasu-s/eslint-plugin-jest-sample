# eslint-plugin-jest-sample

## Overview

- This is a sample project using [eslint-plugin-jest](https://www.npmjs.com/package/eslint-plugin-jest).
- Run the eslint rule for jest. 

## System Requirements

- Node.js - 14.x
- Yarn - 1.22.x

## Library

- Jest - 27.5.x
- eslint-plugin-jest - 26.1.x

## Usage

```bash
# package install
yarn

# eslint run
yarn lint
```

## Execution result

```bash
$ eslint ./test --ext .js

./test/sample.js
  11:6  error  Test title is used multiple times in the same describe block  jest/no-identical-title
  16:3  error  Prefer using 'it' instead of 'test' within describe           jest/consistent-test-it
  22:1  error  All test cases must be wrapped in a describe block            jest/require-top-level-describe

✖ 3 problems (3 errors, 0 warnings)
  1 error and 0 warnings potentially fixable with the `--fix` option.
```

