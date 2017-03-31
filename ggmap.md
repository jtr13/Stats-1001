Untitled
================
Joyce Robbins
3/26/2017

``` r
# install ggmap from GitHub to avoid problems
# devtools::install_github("dkahle/ggmap")
library(ggmap)
```

    ## Loading required package: ggplot2

    ## Google Maps API Terms of Service: http://developers.google.com/maps/terms.

    ## Please cite ggmap if you use it: see citation("ggmap") for details.

``` r
qmap(location = "612 West 115th New York", zoom = 19)
```

    ## Source : https://maps.googleapis.com/maps/api/staticmap?center=612+West+115th+New+York&zoom=19&size=640x640&scale=2&maptype=terrain&language=en-EN

    ## Source : https://maps.googleapis.com/maps/api/geocode/json?address=612%20West%20115th%20New%20York

![](ggmap_files/figure-markdown_github/unnamed-chunk-1-1.png)
