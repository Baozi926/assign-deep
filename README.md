# assign-deep [![NPM version](https://img.shields.io/npm/v/assign-deep.svg?style=flat)](https://www.npmjs.com/package/assign-deep) [![NPM monthly downloads](https://img.shields.io/npm/dm/assign-deep.svg?style=flat)](https://npmjs.org/package/assign-deep) [![NPM total downloads](https://img.shields.io/npm/dt/assign-deep.svg?style=flat)](https://npmjs.org/package/assign-deep) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/assign-deep.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/assign-deep)

> Deeply assign the enumerable properties and/or es6 Symbol properies of source objects to the target (first) object.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save assign-deep
```

## Usage

```js
var assign = require('assign-deep');

var one = {b: {c: {d: 'e'}}};
var two = {b: {c: {f: 'g', j: 'i'}}};
var three = {foo: 'bar'};

console.log(assign(one, two, three));
//=> {b: {c: {d: 'e', f: 'g', j: 'i'}}, foo: 'bar'}
```

## About

### Related projects

You might also be interested in these projects:

* [assign-symbols](https://www.npmjs.com/package/assign-symbols): Assign the enumerable es6 Symbol properties from an object (or objects) to the first object… [more](https://github.com/jonschlinkert/assign-symbols) | [homepage](https://github.com/jonschlinkert/assign-symbols "Assign the enumerable es6 Symbol properties from an object (or objects) to the first object passed on the arguments. Can be used as a supplement to other extend, assign or merge methods as a polyfill for the Symbols part of the es6 Object.assign method.")
* [extend-shallow](https://www.npmjs.com/package/extend-shallow): Extend an object with the properties of additional objects. node.js/javascript util. | [homepage](https://github.com/jonschlinkert/extend-shallow "Extend an object with the properties of additional objects. node.js/javascript util.")
* [merge-deep](https://www.npmjs.com/package/merge-deep): Recursively merge values in a javascript object. | [homepage](https://github.com/jonschlinkert/merge-deep "Recursively merge values in a javascript object.")
* [mixin-deep](https://www.npmjs.com/package/mixin-deep): Deeply mix the properties of objects into the first object. Like merge-deep, but doesn't clone. | [homepage](https://github.com/jonschlinkert/mixin-deep "Deeply mix the properties of objects into the first object. Like merge-deep, but doesn't clone.")

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Contributors

| **Commits** | **Contributor** | 
| --- | --- |
| 23 | [jonschlinkert](https://github.com/jonschlinkert) |
| 11 | [doowb](https://github.com/doowb) |

### Building docs

_(This project's readme.md is generated by [verb](https://github.com/verbose/verb-generate-readme), please don't edit the readme directly. Any changes to the readme must be made in the [.verb.md](.verb.md) readme template.)_

To generate the readme, run the following command:

```sh
$ npm install -g verbose/verb#dev verb-generate-readme && verb
```

### Running tests

Running and reviewing unit tests is a great way to get familiarized with a library and its API. You can install dependencies and run tests with the following command:

```sh
$ npm install && npm test
```

### Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](https://twitter.com/jonschlinkert)

### License

Copyright © 2017, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT License](LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on August 03, 2017._