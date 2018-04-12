# prefer-local

[![Build Status](https://travis-ci.org/mohitsinghs/prefer-local.svg)](https://travis-ci.org/mohitsinghs/prefer-local)
[![npm](https://badge.fury.io/js/prefer-local.svg)](http://badge.fury.io/js/prefer-local)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![dependencies Status](https://david-dm.org/mohitsinghs/prefer-local/status.svg)](https://david-dm.org/mohitsinghs/prefer-local)
[![devDependencies Status](https://david-dm.org/mohitsinghs/prefer-local/dev-status.svg)](https://david-dm.org/mohitsinghs/prefer-local?type=dev)
[![license MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/mohitsinghs/prefer-local/blob/master/LICENSE)
[![codecov](https://codecov.io/gh/mohitsinghs/prefer-local/branch/master/graph/badge.svg)](https://codecov.io/gh/mohitsinghs/prefer-local)

## Install

Install with [npm](https://npm.im/prefer-local)

```console
npm i prefer-local
```

## Uses

Useful for places where we need to choose between boolean value of a property inside an object (if exists) and another boolean value and prefer inner property. For Example, while choosing between local option in an object and a global option. If local option is set to `false` returns `false` even if global option is true.

* `src` - source object containing inner property
* `key` - key of the inner property
* `prop` - value of global property
