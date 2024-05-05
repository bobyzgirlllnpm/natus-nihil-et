# @bobyzgirlllnpm/natus-nihil-et <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @bobyzgirlllnpm/natus-nihil-et
```

## Usage/Examples

```js
var regexTester = require('@bobyzgirlllnpm/natus-nihil-et');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@bobyzgirlllnpm/natus-nihil-et
[npm-version-svg]: https://versionbadg.es/ljharb/@bobyzgirlllnpm/natus-nihil-et.svg
[deps-svg]: https://david-dm.org/ljharb/@bobyzgirlllnpm/natus-nihil-et.svg
[deps-url]: https://david-dm.org/ljharb/@bobyzgirlllnpm/natus-nihil-et
[dev-deps-svg]: https://david-dm.org/ljharb/@bobyzgirlllnpm/natus-nihil-et/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@bobyzgirlllnpm/natus-nihil-et#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@bobyzgirlllnpm/natus-nihil-et.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@bobyzgirlllnpm/natus-nihil-et.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@bobyzgirlllnpm/natus-nihil-et.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@bobyzgirlllnpm/natus-nihil-et
[codecov-image]: https://codecov.io/gh/ljharb/@bobyzgirlllnpm/natus-nihil-et/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@bobyzgirlllnpm/natus-nihil-et/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@bobyzgirlllnpm/natus-nihil-et
[actions-url]: https://github.com/bobyzgirlllnpm/natus-nihil-et/actions
