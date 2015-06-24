tis-100-puzzle-lint
===================

tis-100-puzzle-lint analyzes puzzle programs written in Lua for TIS-100.
It reports compilation errors, runtime errors, and invalid data.  It can
optionally display a preview of what the puzzle will look like in TIS-100.

This program requires a Lua interpreter.  If you're on Linux, your 
distribution can probably provide a suitable one.  Otherwise check
out http://www.lua.org/


Usage
-----

    ./tis-100-puzzle-lint [options] INPUT.lua

INPUT.lua is the TIS-100 Lua puzzle to be analyzed.

Options:

      -h, --help    - Display this text and abort
      -p, --preview - Preview what the puzzle will look like in TIS-100
      -f, --fancy   - NOT FINISHED
                      Draw boxes in preview to more closely match TIS-100
                      May not display correctly on all systems
				  


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
