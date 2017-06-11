
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Travis-CI Build Status](https://travis-ci.org/boshek/rsoi.svg?branch=devel)](https://travis-ci.org/boshek/rsoi) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/boshek/rsoi?branch=devel&svg=true)](https://ci.appveyor.com/project/boshek/rsoi)[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/rsoi)](https://cran.r-project.org/package=rsoi) [![CRAN Downloads](http://cranlogs.r-pkg.org/badges/grand-total/rsoi)](https://CRAN.R-project.org/package=rsoi)

rsoi
----

An R package to download the most up to date Southern Oscillation Index, Oceanic Nino Index and North Pacific Gyre Oscillation data.

Installation
------------

``` r
install.packages("rsoi")

library(rsoi)
```

Usage
-----

``` r
enso <- download_enso()
enso
```

Or for index specific data use the argument:

``` r
soi <- download_enso(climate_idx = "soi")
soi
```

Inspired by
-----------

The idea for this package borrows heavily from the rpdo package. The initial efforts by these authors are gratefully acknowledged. The rpdo github page can be found here: [rpdo](https://github.com/poissonconsulting/rpdo)

Data Sources
------------

-   Southern Oscillation Index <https://www.ncdc.noaa.gov/teleconnections/enso/indicators/soi/>
-   Oceanic Nino Index data <http://www.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/detrend.nino34.ascii.txt>
-   Northern Pacific Gyre Oscillation <http://www.o3d.org/npgo/data/NPGO.txt>

Helpful References
------------------

[In Watching for El Niño and La Niña, NOAA Adapts to Global Warming](https://www.climate.gov/news-features/understanding-climate/watching-el-ni%C3%B1o-and-la-ni%C3%B1a-noaa-adapts-global-warming)

[L’Heureux, M. L., Collins, D. C., & Hu, Z.-Z. (2012, March.). Linear trends in sea surface temperature of the tropical Pacific Ocean and implications for the El Niño-Southern Oscillation. Climate Dynamics, 1–14. doi:10.1007/s00382-012-1331-2](https://link.springer.com/article/10.1007%2Fs00382-012-1331-2)

[The Victoria mode in the North Pacific linking extratropical sea level pressure variations to ENSO](http://onlinelibrary.wiley.com/doi/10.1002/2014JD022221/pdf)
