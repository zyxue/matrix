# ml-matrix

  [![NPM version][npm-image]][npm-url]
  [![build status][travis-image]][travis-url]
  [![npm download][download-image]][download-url]

Matrix manipulation and computation library.

## Installation

`$ npm install --save ml-matrix`

## Usage

### As an ES module

```js
import Matrix from 'ml-matrix';

const matrix = Matrix.ones(5, 5);
```

### As a CommonJS module

```js
const {Matrix} = require('ml-matrix');

const matrix = Matrix.ones(5, 5);
```

## [API Documentation](https://mljs.github.io/matrix/)

## License

  [MIT](./LICENSE)

[npm-image]: https://img.shields.io/npm/v/ml-matrix.svg?style=flat-square
[npm-url]: https://npmjs.org/package/ml-matrix
[travis-image]: https://img.shields.io/travis/mljs/matrix/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/mljs/matrix
[download-image]: https://img.shields.io/npm/dm/ml-matrix.svg?style=flat-square
[download-url]: https://npmjs.org/package/ml-matrix
