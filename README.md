# chord
[![Build Status](http://img.shields.io/travis/mohayonao/chord.svg?style=flat-square)](https://travis-ci.org/mohayonao/chord)
[![NPM Version](http://img.shields.io/npm/v/@mohayonao/chord.svg?style=flat-square)](https://www.npmjs.org/package/@mohayonao/chord)
[![License](http://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](http://mohayonao.mit-license.org/)

## Installation

```sh
npm install @mohayonao/chord
```

## Usage

```js
const chord = require("@mohayonao/chord");

// list of defined chord
console.log(Object.keys(chord));

// get chord
console.log(chord["major"]);
// → [ 0, 4, 7 ]
```

## License

MIT
