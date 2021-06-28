---
title: Global river slopes
summary: R script to estimate the reach slope of any river in the world
tags:""

date: "2021-04-27T00:00:00Z"

external_link: ""
image:
  caption: An example of the algorithm working. The black point is the low site, and the red the site upstream. The raster shows the flow accumulation in the landscape
  focal_point: Smart
  margin: auto
links:
- icon: github
  icon_pack: fab
  name: GitHub
  url: https://github.com/rocher-ros/global_slope
-
summary: R package to compare multivariate time-series.
tags:
- R packages

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---


River slope is a very useful parameter in stream geomorphology, aquatic ecology, hydrology... but hard to obtain easily at any location in the globe. This R script can obtain the stream channel just providing a pair of coordinates of a stream. The workflow is as follows:

- Download a high resolution digital elevation model (DEM) around the site, using the package "elevatr".
- Model the flow accumulation in the landscape to see the stream channels.
- Snap the coordinates provided to the closest stream.
- An algorithm then follows the stream channel upstream for a predetermined length, and estimates the slope as the elevation difference between the site and upstream divided by the distance.
