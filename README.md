
<!-- README.md is generated from README.Rmd. Please edit that file -->

# eda

<!-- badges: start -->
<!-- badges: end -->

The goal of eda is to provide data wrangling and summary functions to
conduct a proper exploratory data analysis.

## Installation

You can install the development version of eda from
[GitHub](https://github.com/kshim99/SSC2024Workshop) with:

``` r
# install.packages("devtools")
devtools::install_github("kshim99/SSC2024Workshop")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(eda)
count_classes(mtcars, cyl)
#> # A tibble: 3 × 2
#>   class count
#>   <dbl> <int>
#> 1     4    11
#> 2     6     7
#> 3     8    14
```
