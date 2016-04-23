# crockpot [![Build Status](https://travis-ci.org/eternal44/crockpot.svg?branch=master)](https://travis-ci.org/eternal44/crockpot)

> Converts multiple number formats using decimal numbers as a proxy.

## Install

```
$ npm install --save crockpot
```

## Development
To run tests follow the following instructions:

```
$ npm install -g gulp
$ npm install -g mocha
```

To run tests on file changes:
```
$ gulp test
```

Alternatively you can run individual tests:
```
$ mocha specs/**
```

## Usage

```js
var convert = require('crockpot')

convert.roman.toEnglish('IV')
// 'four'
```
## License
MIT
