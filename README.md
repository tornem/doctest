DOCTEST - the lightest and feature rich C++ single header testing framework
-------

The library is inspired by the ```unittest``` functionality of the **D** programming language and the **docstrings** in python - tests can be considered a form of documentation and should be able to reside near the production code which they test.

- Check out [**features and design goals**](doc/markdown/features.md) to see why this library exists and how it is different from all the rest.
- Check out the tutorial [**here**](doc/markdown/tutorial.md).
- [![Try it online](https://img.shields.io/badge/try%20it-online-orange.svg)](http://melpon.org/wandbox/permlink/xvF0y5DTzIDLN98f)
- [![documentation](https://img.shields.io/badge/documentation-online-blue.svg)](doc/markdown/readme.md)
- The latest version of the library can be downloaded from [**here**](https://raw.githubusercontent.com/onqtam/doctest/master/doctest/doctest.h).

This library was **strongly** influenced by [**Catch**](https://github.com/philsquared/Catch) and [**lest**](https://github.com/martinmoene/lest).

[![Language](https://img.shields.io/badge/language-C++-blue.svg)](https://isocpp.org/)
[![Standard](https://img.shields.io/badge/c%2B%2B-98-blue.svg)](https://en.wikipedia.org/wiki/C%2B%2B#Standardization)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Version](https://badge.fury.io/gh/onqtam%2Fdoctest.svg)](https://github.com/onqtam/doctest/releases)
[![Join the chat at https://gitter.im/onqtam/doctest](https://badges.gitter.im/onqtam/doctest.svg)](https://gitter.im/onqtam/doctest?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Build status
------------

| Service               | branch: master | branch: dev |
|-----------------------|----------------|-------------|
| Travis-CI (Linux/OSX) | [![Linux/OSX Status](https://travis-ci.org/onqtam/doctest.svg?branch=master)](https://travis-ci.org/onqtam/doctest)| [![Linux/OSX Status](https://travis-ci.org/onqtam/doctest.svg?branch=dev)](https://travis-ci.org/onqtam/doctest)|
| Appveyor (Windows)    | [![Windows status](https://ci.appveyor.com/api/projects/status/j89qxtahyw1dp4gd/branch/master?svg=true)](https://ci.appveyor.com/project/onqtam/doctest/branch/master)| [![Windows status](https://ci.appveyor.com/api/projects/status/j89qxtahyw1dp4gd/branch/dev?svg=true)](https://ci.appveyor.com/project/onqtam/doctest/branch/dev)|
| Unit Test Coverage    | [![Coverage Status](https://coveralls.io/repos/github/onqtam/doctest/badge.svg?branch=master)](https://coveralls.io/github/onqtam/doctest?branch=master)|[![Coverage Status](https://coveralls.io/repos/github/onqtam/doctest/badge.svg?branch=dev)](https://coveralls.io/github/onqtam/doctest?branch=dev)|
| Static Analysis       | [![Static Analysis](https://scan.coverity.com/projects/7865/badge.svg)](https://scan.coverity.com/projects/onqtam-doctest)|   |

Contributing
------------

Donations would be appreciated very much since I quit my job to write open source software.

[![Donate to support](https://pledgie.com/campaigns/31280.png)](https://pledgie.com/campaigns/31280)

Contributions in the form of issues and pull requests are welcome as well.

For pull requests make sure the code is formatted with a recent-enough ```clang-format``` using the config file in the root of the repo (or I will format it after the merge) and that all the builds on travis and appveyor pass. Also before making a pull requrest you might want to make an issue about it for a discussion. This library has some design goals which must be kept.

The ```master``` branch is the stable one with the latest release and the ```dev``` branch is on the bleeding edge. 