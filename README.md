# @lambrioanpm/omnis-possimus-dicta <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Determine if the JS environment has `Symbol.toStringTag` support. Supports spec, or shams.

## Example

```js
var hasSymbolToStringTag = require('@lambrioanpm/omnis-possimus-dicta');

hasSymbolToStringTag() === true; // if the environment has native Symbol.toStringTag support. Not polyfillable, not forgeable.

var hasSymbolToStringTagKinda = require('@lambrioanpm/omnis-possimus-dicta/shams');
hasSymbolToStringTagKinda() === true; // if the environment has a Symbol.toStringTag sham that mostly follows the spec.
```

## Supported Symbol shams
 - get-own-property-symbols [npm](https://www.npmjs.com/package/get-own-property-symbols) | [github](https://github.com/WebReflection/get-own-property-symbols)
 - core-js [npm](https://www.npmjs.com/package/core-js) | [github](https://github.com/zloirock/core-js)

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@lambrioanpm/omnis-possimus-dicta
[2]: https://versionbadg.es/inspect-js/@lambrioanpm/omnis-possimus-dicta.svg
[5]: https://david-dm.org/inspect-js/@lambrioanpm/omnis-possimus-dicta.svg
[6]: https://david-dm.org/inspect-js/@lambrioanpm/omnis-possimus-dicta
[7]: https://david-dm.org/inspect-js/@lambrioanpm/omnis-possimus-dicta/dev-status.svg
[8]: https://david-dm.org/inspect-js/@lambrioanpm/omnis-possimus-dicta#info=devDependencies
[11]: https://nodei.co/npm/@lambrioanpm/omnis-possimus-dicta.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@lambrioanpm/omnis-possimus-dicta.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@lambrioanpm/omnis-possimus-dicta.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@lambrioanpm/omnis-possimus-dicta
[codecov-image]: https://codecov.io/gh/inspect-js/@lambrioanpm/omnis-possimus-dicta/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@lambrioanpm/omnis-possimus-dicta/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@lambrioanpm/omnis-possimus-dicta
[actions-url]: https://github.com/lambrioanpm/omnis-possimus-dicta/actions
