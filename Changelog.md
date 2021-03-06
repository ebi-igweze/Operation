Version 1.0.7
-------------
- Added Support for Linq sytnax from Operation<T> to Operation

Version 1.0.6
-------------
- Made Operation Compatible with Linq Syntax

Version 1.0.5
-------------
- Removed Support for IQueryable in Linq Syntax

Version 1.0.4
-------------
- Added the ability to Mix IEnumerable with Operation in the Linq Syntax
- Added `Fold` Extension to an `IEnumerable<Operation<T>>` and `IEnumerable<Operation>`

Version 1.0.3
-------------
- Upgraded to .NET Core and Fixed Net Standard Dependencies of Regular .NET

Version 1.0.2
-------------
- Upgraded to .NET Core but had the Net Standard Library 1.1 as a Dependency

Version 1.0.1
-------------
- Upgraded to .NET Core but had the Net Standard Library 1.6 as a Dependency

Version 1.0.0
-------------
- Moved to 1.0 Since this library is now used in production environments and the API surface is not going to change

Version 0.1.7
-------------
- Added Change Log :smile:
- Moved Extensions namespace from `System.Extensions` to `System.OperationExtensions` to prevent namespace collision
- Added `Operation.Unwrap()` method instead of `Operation.Throw()`. Throw will always be available but Unwrap is clearer