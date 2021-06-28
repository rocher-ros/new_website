---
title: Interactive app for discharge estimation
summary: Shiny app to calculate discharge in a river using the slug method
tags:
- R
- hydrology

date: "2021-05-27T00:00:00Z"

external_link: ""

image:
  caption: An example of the algorithm working. The black point is the low site, and the red the site upstream. The raster shows the flow accumulation in the landscape
  focal_point: Smart


links:
- icon: github
  name: GitHub
  url: https://github.com/rocher-ros/dischargeApp_shiny

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

App developed in Shiny to measure discharge in streams using a slug injection.

This app is intended to measure discharge using a slug injection of salt, it requires data recorded with a HoBo conductivity logger, a correction coefficient of the response of conductivity against NaCl and the exact amount of salt injected.

The version 2 is to use with another method: by adding a measured volume of salt solution in water, with a known conductivity.

Developed by G. Rocher-Ros (2016), for internal use at Umeå University. Any third party use is under the users' responsability. For any questions contact gerardrocher (at) gmail (dot) com
