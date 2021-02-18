# @terchriss/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@terchris/tiny.svg)](https://www.npmjs.com/package/@bterchris/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@terchris/tiny.svg)](https://www.npmjs.com/package/@terchris/tiny)

testing how to create a npm package
## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```