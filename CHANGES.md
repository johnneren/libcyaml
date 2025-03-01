LibCYAML: Change Log
====================

## LibCYAML v1.2.1

* **General**
  * Support for dynamic library build on Mac OS X.
  * Ordered designated initialisers in public header for C++ compatibility.

No changes are required for client applications to upgrade.


## LibCYAML v1.2.0

* **Loading**:
  * Allow mappings with zero fields in the schema.
  * Improved logging of errors.
  * `CYAML_BOOL` type now treats "Off" as false.
  * Allow loading of float values that overflow or underflow unless
    `CYAML_FLAG_STRICT` set.
  * Added line and column numbers to backtraces.
* **General**:
  * Update tests to handle libyaml 0.2.5 output format change.
  * Buildsystem improvements.
  * Made public header C++ compatible.
  * Test runner supports running individual tests.

No changes are required for client applications to upgrade.


## LibCYAML v1.1.0

* **Loading**:
  * Significantly optimised handling of aliases and anchors.
  * Fixed handling of duplicate mapping keys.
* **Saving**:
  * Increased precision for double precision floating point values.
* **General**:
  * Fixed data handling on big endian systems.

No changes are required for client applications to upgrade.


## LibCYAML v1.0.2

* **Loading**:
  * Fixed invalid read on error path for bitfield handling.
* **Buildsystem**:
  * Fixed to link against libraries after listing objects.
  * Added `check` target as alias for `test`.

No changes are required for client applications to upgrade.


## LibCYAML v1.0.1

* **Loading**:
  * Fixed mapping and sequence values with `CYAML_FLAG_POINTER_NULL`.
* **Buildsystem**:
  * Installation: Explicitly create leading directories.

No changes are required for client applications to upgrade.


## LibCYAML v1.0.0

* Initial release.
