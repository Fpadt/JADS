
<!-- README.md is generated from README.Rmd. Please edit that file -->

# smart-R <a href="https://www.smart-r.net" target="_blank" rel="noopener noreferrer"><img src="figures/mail_signature_white.png" align="right" height="138" /></a>

*Under Development*

<!-- badges: start 
[![R-CMD-check](https://github.com/tidyverse/ggplot2/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/tidyverse/ggplot2/actions/workflows/R-CMD-check.yaml)
[![codecov](https://codecov.io/gh/Fpadt/sapyr/branch/main/graph/badge.svg?token=8FXGGC2M8C)](https://codecov.io/gh/Fpadt/sapyr)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/sapyr)](https://cran.r-project.org/package=sapyr) 
<badges: end -->

## Overview

The goal of JADS is to …

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/v1/examples>.

You can also embed plots, for example:

<img src="man/figures/pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub.
