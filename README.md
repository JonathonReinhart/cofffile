# coffile

_coffile_ is a Python module for manipulating
[COFF](http://en.wikipedia.org/wiki/COFF) files.
It requires [_pefile_](http://github.com/erocarrera/pefile).

Main features:

- Build COFF files from XML description file
- Automatic calculation of pointers and sizes
- Support for relocations

In the future:

- Create XMLs from binary COFF files
- New members in XML (String Table, Optional Header, Line Numbers)

This is tested on Windows XP (win32) and GCC (version 3.4.2 mingw-special).

_coffile_ was originally written by Bartlomiej Piekarski.
