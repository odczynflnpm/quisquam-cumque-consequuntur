# @odczynflnpm/quisquam-cumque-consequuntur <sup>[![Version Badge][2]][1]</sup>

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
var availableTypedArrays = require('@odczynflnpm/quisquam-cumque-consequuntur');
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

[1]: https://npmjs.org/package/@odczynflnpm/quisquam-cumque-consequuntur
[2]: https://versionbadg.es/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur.svg
[5]: https://david-dm.org/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur.svg
[6]: https://david-dm.org/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur
[7]: https://david-dm.org/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur/dev-status.svg
[8]: https://david-dm.org/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur#info=devDependencies
[11]: https://nodei.co/npm/@odczynflnpm/quisquam-cumque-consequuntur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@odczynflnpm/quisquam-cumque-consequuntur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@odczynflnpm/quisquam-cumque-consequuntur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@odczynflnpm/quisquam-cumque-consequuntur
[codecov-image]: https://codecov.io/gh/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@odczynflnpm/quisquam-cumque-consequuntur
[actions-url]: https://github.com/odczynflnpm/quisquam-cumque-consequuntur/actions
