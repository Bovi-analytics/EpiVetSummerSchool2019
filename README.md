Notebook for Jolien Oosterink
================

  - [Packages](#packages)
  - [Basic code](#basic-code)

# Packages

``` r
#data manipulation
if (!require("dplyr")) {
  install.packages("dplyr", dependencies = TRUE)
  library(dplyr)
}
```

    ## Loading required package: dplyr

    ## 
    ## Attaching package: 'dplyr'

    ## The following objects are masked from 'package:stats':
    ## 
    ##     filter, lag

    ## The following objects are masked from 'package:base':
    ## 
    ##     intersect, setdiff, setequal, union

``` r
#drop_na
if (!require("tidyr")) {
  install.packages("tidyr", dependencies = TRUE)
  library(tidyr)
}
```

    ## Loading required package: tidyr

# Basic code

``` r
plot(cars)
```

![](README_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

I have a bright STAT idea
