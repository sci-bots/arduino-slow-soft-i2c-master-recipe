Conda recipe to build Conda package for [Arduino `SlowSoftI2CMaster`][0]
(forked from [here][1]).

Build
=====

Install `conda-build`:

    conda install conda-build

Build recipe:

    conda build .


Install
=======

Install [pre-built package][2] from the [`wheeler-microfluidics`][3] channel
using:

    conda install -c wheeler-microfluidics arduino-slow-soft-i2c-master


[0]: https://github.com/sci-bots/SlowSoftI2CMaster
[1]: https://github.com/felias-fogg/SlowSoftI2CMaster
[2]: https://anaconda.org/wheeler-microfluidics/arduino-slow-soft-i2c-master
[3]: https://anaconda.org/wheeler-microfluidics
