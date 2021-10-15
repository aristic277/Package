
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Package

<!-- badges: start -->
<!-- badges: end -->

The goal of Package is to show you how cool Disc Golf is. It is mega
cool.

## Installation

You can install the released version of Package from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("Package")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("aristic277/Package")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(Package)
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
head(DiscGolf, 5)
#>   approved_date class diameter flexibility height
#> 1    2020-10-03  <NA>     21.2        7.95    1.6
#> 2    2020-09-29  <NA>     21.3       11.02    1.4
#> 3    2020-09-29  <NA>     21.3       10.68    1.8
#> 4    2020-09-29  <NA>     21.4        5.11    1.6
#> 5    2020-09-29  <NA>     21.0        6.70    1.9
#>                          manufacturer                     model rim_depth
#> 1                         Yikun Discs           Qi (, Qiong Qi)       1.1
#> 2 Viking Discs (IP-Agency Finland Oy)                      Odin       1.1
#> 3 Viking Discs (IP-Agency Finland Oy)                    Fenrir       1.1
#> 4                   Lone Star Molding The Dillard Midrange Md-1       1.2
#> 5                   Lone Star Molding              Penny Putter       1.5
#>   rim_thickness weight
#> 1           2.3  176.0
#> 2           2.3  176.8
#> 3           2.0  176.8
#> 4           1.3  177.6
#> 5           1.1  174.3
```
