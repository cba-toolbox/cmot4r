
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cmot4r: Computational MOdel Toolbox for R

<!-- badges: start -->
<!-- badges: end -->

The cmot4r package includes the following R packages: -
cba-toolbox/PRLpreprocess : Preprocessing of Probabilistic Reversal
Learning Data

## Installation

You can install the development version of cmot4r from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("cba-toolbox/cmot4r")
```

## Example

``` r
library(cmot4r)
data <- PRL_preprocess_csv("data_v.csv")
```
