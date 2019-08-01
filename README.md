




<!-- README.md was auto-generated by README.Rmd. Please DO NOT edit by hand!-->

# Luminesence <img width=120px src="man/figures/RL_Logo.svg" align="right" />

The R package ‘Luminescence’ by the R-Luminescence Group provides a
collection of various R functions for luminescence dating data analysis.

[![CRAN](http://www.r-pkg.org/badges/version/Luminescence)](https://cran.r-project.org/package=Luminescence)
[![Downloads](http://cranlogs.r-pkg.org/badges/grand-total/Luminescence)](http://www.r-pkg.org/pkg/Luminescence)
[![Downloads](http://cranlogs.r-pkg.org/badges/Luminescence)](http://www.r-pkg.org/pkg/Luminescence)
[![Downloads](http://cranlogs.r-pkg.org/badges/last-week/Luminescence)](http://www.r-pkg.org/pkg/Luminescence)
[![Downloads](http://cranlogs.r-pkg.org/badges/last-day/Luminescence)](http://www.r-pkg.org/pkg/Luminescence)

### Test performance

[![Build
status](https://ci.appveyor.com/api/projects/status/jtgqr9a6jajn02y0/branch/master?svg=true)](https://ci.appveyor.com/project/tzerk/luminescence/branch/master)
[![Build
Status](https://travis-ci.org/R-Lum/Luminescence.svg?branch=master)](https://travis-ci.org/R-Lum/Luminescence)
[![Coverage
Status](https://img.shields.io/codecov/c/github/R-Lum/Luminescence.svg)](https://codecov.io/github/R-Lum/Luminescence?branch=master)

### CRAN check status

| error | fail | warn | note | ok |
| ----: | ---: | ---: | ---: | -: |
|     0 |    0 |    0 |    6 |  6 |

## Social media and other resources

Follow us on
[![](http://i.imgur.com/wWzX9uB.png)](https://www.twitter.com/RLuminescence)
or visit our [R-Luminescence homepage](http://www.r-luminescence.org).

## Installation

#### i. Requirements

**Windows (32/64bit)** - ‘Rtools’ (provided by CRAN)

<https://cran.r-project.org/bin/windows/Rtools/>

**Mac OS X** - ‘Xcode’ (provided by Apple)

<https://developer.apple.com/xcode/downloads/>

For **Linux** users *gcc* often comes pre-installed in most
distributions. Should *gcc* be not available, however, we kindly refer
to the exhaustive collection of installation guides depending on the
linux distribution.

#### ii. Install the package

Install any development versions using our *RStudio* add-in

![](man/figures/README-Screenshot_AddIn.png)

##### The plain **R** way

To install the stable version from CRAN, simply run the following from
an R console:

``` r
install.packages("Luminescence")
```

To install the latest development builds directly from GitHub, run

``` r
if(!require("devtools"))
  install.packages("devtools")
devtools::install_github("R-Lum/Luminescence@<wanted branch>")
```

## Contribute

The R luminescence project is based on and evolves from ideas,
contributions and constructive criticism of its users. Help us to
maintain and develop the package, to find bugs and create new functions
as well as a user-friendly design. Try
<https://github.com/R-Lum/Luminescence/issues> or write us an
[e-mail](mailto:developers@r-luminescence.org) if anything crosses your
mind or if you want your new self-written function to be to implemented.
You are kindly invited to bring forward the package with us\!

## Note

**The package comes without any guarantee\!**

Please further note that this version is a development version and may
change day by day. For stable branches please visit the package on [CRAN
‘Luminescence’](https://cran.r-project.org/package=Luminescence).

## License

This program is free software: you can redistribute it and/or modify it
under the terms of the GNU General Public License as published by the
Free Software Foundation, either version 3 of the License, or any later
version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU
General Public
License](https://github.com/R-Lum/Luminescence/blob/master/LICENSE) for
more details.

## Related projects

  - [RLumModel](https://github.com/R-Lum/RLumModel)
  - [RLumShiny](https://github.com/R-Lum/RLumShiny)
  - [BayLum](https://github.com/R-Lum/BayLum)
  - [RLumDocker](https://github.com/R-Lum/RLumDocker)
  - [RCarb](https://github.com/R-Lum/RCarb)

## R package dependencies

![](man/figures/README-Package_DependencyGraph.png)
