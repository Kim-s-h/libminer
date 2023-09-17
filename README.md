
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to help you understand your libraries better,
and learn how to write packages.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Kim-s-h/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminer)

lib_summary()
#>                                                                   Library
#> 1                                      C:/Program Files/R/R-4.3.1/library
#> 2 C:/Users/O808022/AppData/Local/Temp/RtmpQ9hm9P/temp_libpath58dc65527dc5
#>   n_packages
#> 1        283
#> 2          1

# Also can calculate sizes
lib_summary(sizes = TRUE)
#>                                                                   Library
#> 1                                      C:/Program Files/R/R-4.3.1/library
#> 2 C:/Users/O808022/AppData/Local/Temp/RtmpQ9hm9P/temp_libpath58dc65527dc5
#>   n_packages  lib_size
#> 1        283 462378218
#> 2          1     13512
```
