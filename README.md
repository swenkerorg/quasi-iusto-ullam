# @swenkerorg/quasi-iusto-ullam <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Returns an array of Typed Array names that are available in the current environment.

## Example

```js
var availableTypedArrays = require('@swenkerorg/quasi-iusto-ullam');
var assert = require('assert');

assert.deepStrictEqual(
	availableTypedArrays().sort(),
	[
		'Int8Array',
		'Uint8Array',
		'Uint8ClampedArray',
		'Int16Array',
		'Uint16Array',
		'Int32Array',
		'Uint32Array',
		'Float32Array',
		'Float64Array',
		'BigInt64Array',
		'BigUint64Array'
	].sort()
);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@swenkerorg/quasi-iusto-ullam
[2]: https://versionbadg.es/inspect-js/@swenkerorg/quasi-iusto-ullam.svg
[5]: https://david-dm.org/inspect-js/@swenkerorg/quasi-iusto-ullam.svg
[6]: https://david-dm.org/inspect-js/@swenkerorg/quasi-iusto-ullam
[7]: https://david-dm.org/inspect-js/@swenkerorg/quasi-iusto-ullam/dev-status.svg
[8]: https://david-dm.org/inspect-js/@swenkerorg/quasi-iusto-ullam#info=devDependencies
[11]: https://nodei.co/npm/@swenkerorg/quasi-iusto-ullam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@swenkerorg/quasi-iusto-ullam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@swenkerorg/quasi-iusto-ullam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@swenkerorg/quasi-iusto-ullam
[codecov-image]: https://codecov.io/gh/inspect-js/@swenkerorg/quasi-iusto-ullam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@swenkerorg/quasi-iusto-ullam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@swenkerorg/quasi-iusto-ullam
[actions-url]: https://github.com/swenkerorg/quasi-iusto-ullam/actions
