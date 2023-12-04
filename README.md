
<!-- README.md is generated from README.Rmd. Please edit that file -->

# bis620.2023

<!-- badges: start -->

[![R-CMD-check](https://github.com/zqji0610/bis620.2023/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/zqji0610/bis620.2023/actions/workflows/R-CMD-check.yaml)
[![test-coverage](https://github.com/zqji0610/bis620.2023/actions/workflows/test-coverage.yaml/badge.svg)](https://github.com/zqji0610/bis620.2023/actions/workflows/test-coverage.yaml)
<!-- badges: end -->

Author: Yufei Deng, Ziqing Ji, Yining Chen

The goal of bis620.2023 is to allow users to query clinical trial studies, interact with the filtered data table, and visualize and customize graphs according to needs. To learn more information about the clinical trials, go to the website ClinicalTrials.gov. 

Package features:  
Users can filter the dataset by specific fields, including:  
1. Title keywords search
2. Define study date ranges
3. Define sponsor types
4. Histogram visualization customization
 
Displaying Visualization includes:  
1. Phase Histogram
2. Condition Histogram
3. Primary Purpose Pie Chart
4. Study Type Histogram
5. Intervention Type Pie Chart
6. Intervention Histogran Specified by Intervention Type

Example output:
![818571701727358_ pic](https://github.com/zqji0610/bis620.2023/assets/144503716/0d3a453f-d1e4-4685-b726-be9a74955670)


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
