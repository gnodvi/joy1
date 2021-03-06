Joy1
----

Build|Linux|Windows|Coverity|Coverage|Codecov|Quality|Alerts
---|---|---|---|---|---|---|---
status|[![Travis CI build status](https://travis-ci.org/Wodan58/joy1.svg?branch=master)](https://travis-ci.org/Wodan58/joy1)|[![AppVeyor CI build status](https://ci.appveyor.com/api/projects/status/github/Wodan58/joy1?branch=master&svg=true)](https://ci.appveyor.com/project/Wodan58/joy1)|[![Coverity Scan Build Status](https://img.shields.io/coverity/scan/14633.svg)](https://scan.coverity.com/projects/wodan58-joy1)|[![Coverage Status](https://coveralls.io/repos/github/Wodan58/joy1/badge.svg?branch=master)](https://coveralls.io/github/Wodan58/joy1?branch=master)|[![Codecov](https://codecov.io/gh/Wodan58/joy1/branch/master/graph/badge.svg)](https://codecov.io/gh/Wodan58/joy1)|[![Language grade: C/C++](https://img.shields.io/lgtm/grade/cpp/g/Wodan58/joy1.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Wodan58/joy1/context:cpp)|[![Alerts](https://img.shields.io/lgtm/alerts/g/Wodan58/joy1.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/Wodan58/joy1/alerts)

Changes
-------

Changes are mentioned in globals.h and documented in the `doc` directory.
Some builtins have been added: fget, getch, and sametype.
The original version is available [here](https://github.com/Wodan58/Joy).

Installation
------------

Build with the [BDW garbage collector](https://github.com/ivmai/bdwgc):

    ln -s ../bdwgc
    cmake .
    cmake --build .

or without:

    make -f make.nogc

Then run:

    make -f regres.mak
