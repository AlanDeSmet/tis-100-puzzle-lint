tis-100-puzzle-lint
===================

tis-100-puzzle-lint analyzes puzzle programs written in Lua for TIS-100.
It reports compilation errors, runtime errors, and invalid data.

This program requires a Lua interpreter.  If you're on Linux, your 
distribution can probably provide a suitable one.  Otherwise check
out http://www.lua.org/


Usage
-----

> lua tis-100-puzzle-lint _12345678.lua_

_12345678.lua_ should be your TIS-100 program, written in Lua.

This program will return 0 if no problems were detected and non-0 if
one or more problems were detected.



License
-------

tis-100-puzzle-lint copyright 2015 Alan De Smet

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:
 
The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE. 
