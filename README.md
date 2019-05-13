# @redan/tiny

[![npm (scoped)](https://img.shields.io/github/issues/RedanHassoun/tiny.svg)](https://www.npmjs.com/package/@redan/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @redan/tiny
```

## Usage

```js
const tiny = require("@redan/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
