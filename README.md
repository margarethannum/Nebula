
<!-- README.md is generated from README.Rmd. Please edit that file -->

# nebula

<!-- badges: start -->

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
<!-- [![CRAN status](https://www.r-pkg.org/badges/version/nebula)](https://CRAN.R-project.org/package=nebula) -->
[![Codecov test
coverage](https://codecov.io/gh/nebula-group/nebula/branch/master/graph/badge.svg)](https://codecov.io/gh/nebula-group/nebula?branch=master)
[![R build
status](https://github.com/nebula-group/nebula/workflows/R-CMD-check/badge.svg)](https://github.com/nebula-group/nebula/actions)
<!-- badges: end -->

The {nebula} package implements Network-based latent-Dirichlet subtype
analysis (Nebula) algorithm.

Practically, this can be used to incorporate biological
networks/pathways to inform clustering solutions.

Flexible sparsity parameters for multiple input data types allows for
control over which data types need sparse vs rich feature selection.

## Installation

You can install the development version from
[GitHub](https://github.com/nebula-group/nebula) with:

``` r
# install.packages("remotes")

remotes::install_github("nebula-group/nebula", build_vignettes = TRUE)

library(nebula)
```

Learn more in `vignette("nebula_tutorial", package = "nebula")` or
`?nebula`.
