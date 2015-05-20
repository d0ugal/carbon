# Carbon Change Log

![1.1.0](https://img.shields.io/badge/1.1.0-in_development-orange.svg?style=flat-square)
- Added custom allocators in the form of the `Allocator` attribute

![1.0.2](https://img.shields.io/badge/1.0.1-in_development-orange.svg?style=flat-square)
- Fixed attributes applying when they aren't inherited
- Fixed Matrix3x3 quaternion methods
- Improved matrix performance

![1.0.1](https://img.shields.io/badge/1.0.1-latest-brightgreen.svg?style=flat-square)
- Upgraded to Graphene 1.1.3, fixes several issues
- Added missing `Carbon.Unpack` method for faster unpacking
- Added alias to `Graphene.Support` as `Carbon.Support`
- Added `SyntaxErrorException` for Carbide
- Added the notion of 'features' for supporting edge features
	- Added `Carbon.Features`, `Carbon.Enable`, `Carbon.Disable`, and `Carbon.Enabled`
- Fixed `List:Clear` not returning self
- Fixed `Set:ToList`
- Improved Carbide to throw exceptions when faults occur
- Improved documentation on matrix methods
- Improved test coverage

![1.0.0](https://img.shields.io/badge/1.0.0-unsupported-red.svg?style=flat-square)
- Initial release