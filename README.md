
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bis620.2023

<!-- badges: start -->

[![R-CMD-check](https://github.com/zqji0610/bis620.2023/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/zqji0610/bis620.2023/actions/workflows/R-CMD-check.yaml)
[![test-coverage](https://github.com/zqji0610/bis620.2023/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/zqji0610/bis620.2023/actions/workflows/test-coverage.yaml)
<!-- badges: end -->

The goal of bis620.2023 is to allow users to query clinical trial studies, interact with the filtered data table, and visualize and customize graphs according to needs. To learn more information about the clinical trials, go to the website ClinicalTrials.gov. Users can filter the dataset by specific fields, including title keywords, study date ranges, sponsor types, conditions, study types, and intervention types. Users can also customize the visualizations by choosing different colors.

Author: Yufei Deng, Ziqing Ji, Yining Chen



## Installation

You can install the development version of bis620.2023 from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("zqji0610/bis620.2023")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(bis620.2023)
accel |> 
  head(100) |> 
  plot_accel()
```

<img src="man/figures/README-example-1.png" width="100%" />


## Test-Coverage Report

Link to the [test coverage page](https://github.com/zqji0610/bis620.2023/actions/workflows/test-coverage.yaml).
Link to the [R-CMD-check](https://github.com/zqji0610/bis620.2023/actions/workflows/R-CMD-check.yaml).
