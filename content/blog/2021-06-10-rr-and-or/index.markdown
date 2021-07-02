---
title: RR and OR
author: ''
date: '2021-06-10'
slug: rr-and-or
categories: []
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2021-06-10T13:26:57-07:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---


```r
library(shiny)
library(widgetframe)
```

```
## Loading required package: htmlwidgets
```


For this blog, I'm hoping to sample from a dataset so as to get any RR I want but a fixed OR.

##  Definitions


```r
set.seed(47)
rnorm(10)
```

```
##  [1]  1.99469634  0.71114251  0.18540528 -0.28176501  0.10877555 -1.08573747
##  [7] -0.98548216  0.01513086 -0.25204590 -1.46575030
```

##  Case-control studies, one more time

##  Can we force the RR to be anything we want?


<iframe height="800" width="100%" frameborder="no" src="https://hardin47.shinyapps.io/RROR/"> </iframe>

A shiny app goes here

 https://statsandr.com/blog/how-to-embed-a-shiny-app-in-blogdown/ 

https://www.cultureofinsight.com/post/responsive-iframes-for-shiny-apps
