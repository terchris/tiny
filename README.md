# @terchris/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@terchris/tiny.svg)](https://www.npmjs.com/package/@terchris/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@terchris/tiny.svg)](https://www.npmjs.com/package/@terchris/tiny)

testing how to create a npm package
## Install

```
$ npm install @terchris/tiny
```

## Usage

```js
const tiny = require("@terchris/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```