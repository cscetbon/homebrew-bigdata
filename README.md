homebrew-bigdata
================

Formulas for BigData related brews

Filing Bug Reports
==================

Please include the following information in your bug report:

- OS X Version: ex. 10.9.0, 10.9.1
- Homebrew Version: `brew -v`
- Xcode Version: 4.4, 4.3, 4.0, 3 etc.
  - If you are on Mountain Lion `10.8.x`, please also upgrade to the latest Xcode, 4.4.
  - If using 4.3, verify whether you have the `Command Line Tools` installed as well
  - If on Snow Leopard, you may want to install the [`OS X GCC Installer`](https://github.com/kennethreitz/osx-gcc-installer/)
- Output of `gcc -v`
- Output of `brew install -V path/to/homebrew-php/the-formula-you-want-to-test.rb --with-your --opts-here` within a [gist](http://gist.github.com). Please append any options you added to the `brew install` command.
- Output of `brew doctor` within a [gist](http://gist.github.com)

This will help us diagnose your issues much quicker, as well as find commonalities between different reported issues.

Requirements
============

* [Homebrew](https://github.com/mxcl/homebrew)
* Mavericks. Untested everywhere else.

Usage
=====

Tap the repository into your brew installation:

    brew tap cscetbon/homebrew-bigdata

Then install any formulae you might need:

    brew install cloudera-hadoop

That's it!

License
=======

Copyright (c) 2014 Cyril Scetbon and other contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
