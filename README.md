
<!-- README.md is generated from README.Rmd. Please edit that file -->

# calcthat

<!-- badges: start -->
<!-- badges: end -->

The goal of `calcthat` is to make a common calculation, subtracting
minimum value from maximum value, more convenient.

## Installation

You can install the development version of `calcthat` from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("stat545ubc-2023/calcthat")
```

## Usage

A fairly common task when processing data is to subtract the minimum
value from the maximum value. This is what `max_minus_min()` does.

## Example

This is a basic example which shows you how to solve a common problem.
In this example, the minimum value of \[1\] is subtracted from the
maximum value of \[20\]:

``` r
library(calcthat)

max_minus_min(1:20)
#> [1] 19
```
