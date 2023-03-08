* README_EN.txt
* 2023.03.11
* libarchive

1. DESCRIPTION
2. SOURCES
3. PATCHES
4. DEPENDENCIES
5. EXTERNALS
6. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
`libarchive` library fork

-------------------------------------------------------------------------------
2. SOURCES
-------------------------------------------------------------------------------
https://github.com/libarchive/libarchive

-------------------------------------------------------------------------------
3. PATCHES
-------------------------------------------------------------------------------
The original library patched to fix these issues:

1. Workaround for the library issue:
   `CMakeLists.txt tries to override globally visible CMAKE_BUILD_TYPE through the cache` :
   https://github.com/libarchive/libarchive/issues/1163

-------------------------------------------------------------------------------
4. DEPENDENCIES
-------------------------------------------------------------------------------
Optional:

* `xzutils`

-------------------------------------------------------------------------------
5. EXTERNALS
-------------------------------------------------------------------------------
To checkout externals you must use the
[vcstool](https://github.com/dirk-thomas/vcstool) python module.

NOTE:
  To install the module from the git repository:

  >
  python -m pip install git+https://github.com/dirk-thomas/vcstool

-------------------------------------------------------------------------------
6. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
