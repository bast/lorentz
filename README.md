[![Build Status](https://travis-ci.org/bast/lorentzian.svg?branch=master)](https://travis-ci.org/bast/lorentzian/builds)
[![License](https://img.shields.io/badge/license-%20MPL--v2.0-blue.svg)](../master/LICENSE)


# lorentzian

Primitive script to convert raw x-y data to Lorentzian shapes.

![](example/spectrum.png "example spectrum")

Example:

```shell
$ python lorentzian.py --xy=example/1.xy --x-min=1000.0 --x-max=1800.0 > example/1.out
```

To see all options:

```shell
$ python lorentzian.py --help
```
