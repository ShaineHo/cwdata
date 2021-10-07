
<!-- README.md is generated from README.Rmd. Please edit that file -->

# cwdata

<!-- badges: start -->

<!-- badges: end -->

The goal of cwdata is to …

## Installation

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("ShaineHo/cwdata")
```

## Example

This package provide data set from Communication wiht Data Course

``` r
library(cwdata)
head(key_crop_yields)
#>        entity code year     crop tonnes_per_hectare
#> 1 Afghanistan  AFG 1961    wheat             1.0220
#> 2 Afghanistan  AFG 1961     rice             1.5190
#> 3 Afghanistan  AFG 1961    maize             1.4000
#> 4 Afghanistan  AFG 1961 soybeans                 NA
#> 5 Afghanistan  AFG 1961 potatoes             8.6667
#> 6 Afghanistan  AFG 1961    beans                 NA
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date. `devtools::build_readme()` is handy for this. You could also
use GitHub Actions to re-render `README.Rmd` every time you push. An
example workflow can be found here:
<https://github.com/r-lib/actions/tree/master/examples>.
