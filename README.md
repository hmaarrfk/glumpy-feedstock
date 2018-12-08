About glumpy
============

Home: http://glumpy.github.io/

Package license: BSD-3-Clause

Feedstock license: BSD 3-Clause

Summary: Glumpy is a python library for scientific visualization that is both fast, scalable and beautiful.

Glumpy is a python library for scientific visualization that is both fast,
scalable and beautiful. Glumpy offers an intuitive interface between numpy
and modern OpenGL.


Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/ramonaoptics/glumpy-feedstock/master.svg?label=Linux)](https://circleci.com/gh/ramonaoptics/glumpy-feedstock)
[![OSX](https://img.shields.io/travis/ramonaoptics/glumpy-feedstock/master.svg?label=macOS)](https://travis-ci.org/ramonaoptics/glumpy-feedstock)
[![Windows](https://img.shields.io/appveyor/ci/ramonaoptics/glumpy-feedstock/master.svg?label=Windows)](https://ci.appveyor.com/project/ramonaoptics/glumpy-feedstock/branch/master)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-glumpy-green.svg)](https://anaconda.org/ramonaoptics/glumpy) | [![Conda Downloads](https://img.shields.io/conda/dn/ramonaoptics/glumpy.svg)](https://anaconda.org/ramonaoptics/glumpy) | [![Conda Version](https://img.shields.io/conda/vn/ramonaoptics/glumpy.svg)](https://anaconda.org/ramonaoptics/glumpy) | [![Conda Platforms](https://img.shields.io/conda/pn/ramonaoptics/glumpy.svg)](https://anaconda.org/ramonaoptics/glumpy) |

Installing glumpy
=================

Installing `glumpy` from the `ramonaoptics` channel can be achieved by adding `ramonaoptics` to your channels with:

```
conda config --add channels ramonaoptics
```

Once the `ramonaoptics` channel has been enabled, `glumpy` can be installed with:

```
conda install glumpy
```

It is possible to list all of the versions of `glumpy` available on your platform with:

```
conda search glumpy --channel ramonaoptics
```




Updating glumpy-feedstock
=========================

If you would like to improve the glumpy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`ramonaoptics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `ramonaoptics` channel.
Note that all branches in the ramonaoptics/glumpy-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
