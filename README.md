
<!-- TODO README.md is generated from README.Rmd. Please edit that file -->

# FixelArray

<!-- badges: start -->

[![CircleCI build
status](https://circleci.com/gh/PennLINC/FixelArray.svg?style=svg)](https://circleci.com/gh/PennLINC/FixelArray)
<!-- badges: end -->

The goal of FixelArray is to …

## Installation

Before you install FixelArray R package, if you are using Linux system, please check if libhdf5-dev has been installed in your system:
```console
foo@bar:~$ ldconfig -p | grep libhdf5*
```
If you got more than one line of outputs, congrats, you have libhdf5-dev installed. Otherwise, please install it. For Ubuntu user, you may install via:
```console
foo@bar:~$ sudo apt-get update -y
foo@bar:~$ sudo apt-get install -y libhdf5-dev
```

After setting libhdf5 up, you can install the released version of FixelArray from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("FixelArray")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("PennLINC/FixelArray")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(FixelArray)
## basic example code
```

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
<https://github.com/r-lib/actions/tree/master/examples>.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
