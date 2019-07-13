
<!-- README.md is generated from README.Rmd. Please edit that file -->

# tsviz

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/tsviz)](https://CRAN.R-project.org/package=tsviz)
[![CRAN\_Downloads](https://cranlogs.r-pkg.org/badges/tsviz)](https://cran.r-project.org/package=tsviz)
[![Travis build
status](https://travis-ci.org/donlelef/tsviz.svg?branch=master)](https://travis-ci.org/donlelef/tsviz)
<!-- badges: end -->

An RStudio addin to provide easy and interactive time series
visualization. To be visible to the addin, time series must be stored in
a dataframe in the global environment, with:

  - at least a column of type *Date*
  - at least a column of type *numeric*

## Installation

You can install the released version of tsviz from
[CRAN](https://CRAN.R-project.org) with:

``` r
# install.packages("tsviz")
```

Or install the development version from Github:

``` r
# devtools::install_packages("donlelef/tsviz")
```

Once you have installed the package, you donâ€™t need to load it with
`library()`, the addins are installed on your machine as part of the
package install process.

## Example

First, let us load some suitable data:

``` r
library(tsviz)
prices <- crypto_prices
```

Then, we can run the addin:

![Tutorial gif](reference/figure/tsviz.gif)

That’s it.
