# @clysema/jsonload

[![npm (scoped)](https://img.shields.io/npm/v/@clysema/jsonload.svg)](https://www.npmjs.com/package/@clysema/jsonload)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@clysema/jsonload.svg)](https://www.npmjs.com/package/@clysema/jsonload)

Removes all spaces from a string.

## Install

```
$ npm install @clysema/jsonload
```

## Usage

```js
const jsonload = require("@clysema/jsonload");

(async () => {
  try {
    const test = await jsonload("./test.json")
  } catch (e) {
    console.log(e);
  }
})();
```
