
<!-- README.md is generated from README.Rmd. Please edit that file -->

nebula
======

<!-- badges: start -->

[![Codecov test
coverage](https://codecov.io/gh/margarethannum/nebula/branch/master/graph/badge.svg)](https://codecov.io/gh/margarethannum/nebula?branch=master)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/margarethannum/nebula?branch=master&svg=true)](https://ci.appveyor.com/project/margarethannum/nebula)
[![Travis build
status](https://travis-ci.com/margarethannum/nebula.svg?branch=master)](https://travis-ci.com/margarethannum/nebula)

<!-- badges: end -->

The Nebula package implements Network-based latent-Dirichlet subtype
analysis (Nebula) algorithm.

Practically, this can be used to incorporate biological
networks/pathways to inform clustering solutions.

Flexible sparsity parameters for multiple input data types allows for
control over which data types need sparse vs rich feature selection.

Installation
------------

You can install the development version from
[GitHub](https://github.com/nebula-group/nebula) with:

    # install.packages("remotes")

    remotes::install_github("nebula-group/nebula", build_vignettes = TRUE)

    library(nebula)

Learn more in `vignette("nebula_tutorial", package = "nebula")` or
`?nebula`.
