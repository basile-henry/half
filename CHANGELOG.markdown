0.2.2.3
-------
* Avoid the new warnings for missing pattern synonym signatures on GHC 8

0.2.2.2
-------
* Fixed an issue with `Storable` that was causing crashing for some users.

0.2.2.1
-------
* Added support for older GHCs still. `unsafeShiftR` was only added in 7.4.

0.2.2
-----
* Fixed `isInfinite`.
* Added support for older GHCs. On GHC < 7.8 the pattern synonyms are disabled.

0.2.1
-----
* Removed need for `GeneralizedNewtypeDeriving` and `ScopedTypeVariables`.

0.2.0.1
-------
* Fixed source repository location

0.2
---
* Renamed `toFloat` to `fromHalf` for easier unqualified use.
* Added a `Read` instance.

0.1.1
-----
* Added a `CTYPE` to the Half declaration so that it can be used with `CApiFFI` as an unsigned short.

0.1
---
* Initial release

