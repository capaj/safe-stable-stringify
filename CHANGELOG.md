# Changelog

## v2.0.0

- __[BREAKING]__ Convert BigInt to number by default instead of ignoring these values
  If you wish to ignore these values similar to earlier versions, just use the new `bigint` option and set it to `false`.
- __[BREAKING]__ Support ESM
- __[BREAKING]__ Requires ES6
- Optional BigInt support
- Deterministic behavior is now optional
- The value to indicate a circular structure is now adjustable
- Significantly faster TypedArray stringification
- Smaller Codebase
- Removed stateful indentation to guarantee side-effect freeness

## v1.1.1

- Fixed an indentation issue in combination with empty arrays and objects
- Updated dev dependencies

## v1.1.0

- Add support for IE11 (https://github.com/BridgeAR/safe-stable-stringify/commit/917b6128de135a950ec178d66d86b4d772c7656d)
- Fix issue with undefined values (https://github.com/BridgeAR/safe-stable-stringify/commit/4196f87, https://github.com/BridgeAR/safe-stable-stringify/commit/4eab558)
- Fix typescript definition (https://github.com/BridgeAR/safe-stable-stringify/commit/7a87478)
- Improve code coverage (https://github.com/BridgeAR/safe-stable-stringify/commit/ed8cadc, https://github.com/BridgeAR/safe-stable-stringify/commit/b58c494)
- Update dev dependencies (https://github.com/BridgeAR/safe-stable-stringify/commit/b857ea8)
- Improve docs