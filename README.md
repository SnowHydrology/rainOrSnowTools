
<!-- README.md is generated from README.Rmd. Please edit that file -->

# rainOrSnowTools

<!-- badges: start -->
<!-- badges: end -->

<img src="https://www.dri.edu/wp-content/uploads/badge.png" align="right" width="150"/>

The goal of the `rainOrSnowTools` R package is to support analysis for
the [**Mountain Rain or Snow**](https://www.rainorsnow.org/) **citizen
science project**.

### `rainOrSnowTools` provides:

------------------------------------------------------------------------

1)  Access to meteorological data from the
    [HADS](https://hads.ncep.noaa.gov/),
    [LCD](https://www.ncei.noaa.gov/products/land-based-station/local-climatological-data),
    and [WCC](https://www.nrcs.usda.gov/wps/portal/wcc/home/) networks.
2)  Modeled meteorological data (air/dew point/wet bulb temperature and
    relative humidity) for an observation point.
3)  [GPM IMERG probability of liquid
    precipitation](https://gpm.nasa.gov/data/imerg) (pLP) data for an
    observation point.
4)  Geographical data (elevation, state, and ecoregion 3/4) for an
    observation point.
5)  QA/QC of processed observation data.

## Installation

------------------------------------------------------------------------

You can install the development version of `rainOrSnowTools` from
[GitHub](https://github.com/SnowHydrology/rainOrSnowTools/tree/r_packaging/)
with:

``` r
# install.packages("devtools")
# Install location is here for now...
devtools::install_github("SnowHydrology/rainOrSnowTools",
                         ref = "add_meteo_gpm")

# ...but eventually it will be here:
devtools::install_github("SnowHydrology/rainOrSnowTools")
```

## Loading Example

------------------------------------------------------------------------

Load in the `rainOrSnowTools` library…

``` r
library(rainOrSnowTools)
```
