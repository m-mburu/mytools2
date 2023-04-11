
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mytools2

<!-- badges: start -->
<!-- badges: end -->

The goal of mytools2 is to …

## Installation

You can install the development version of mytools2 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("m-mburu/mytools2")
```

## Get info example

This is a basic example which shows you how to solve a common problem:

``` r
library(mytools2)

get_info_data(iris)
#> $dimension
#> [1] 150   5
#> 
#> $names
#> [1] "Sepal.Length" "Sepal.Width"  "Petal.Length" "Petal.Width"  "Species"
```

## get mean example

``` r
library(mytools2)

get_mean_data(iris)
#>   Sepal.Length Sepal.Width Petal.Length Petal.Width
#> 1     5.843333    3.057333        3.758    1.199333
```
