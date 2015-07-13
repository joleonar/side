---
title       : Developing Data Products
subtitle    : App Presentation
author      : Leonardo Alvarado
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction
The app was designed for plotting two different histograms: 

1. Number of seismic events per year 

2. Number of seismic events per magnitud,

The information about earthquakes was provided by FUNVISIS (Fundación Venezolana de Investigaciones Sismológicas), the database contain seismic events from 2000 to 2010 occurred in the region of Venezuela between latitude 5 to 14ºN and longitude 58 to 74ºW.

--- .class #id 

## The data
Each event has the following information: 
* Origin time of the event : Year, Month, Day, hour, minute,seconds
* Localization: Latitude, Longitude, Depth
* Magnitude

Part of the data is: 

```
##   Year mm dd hh min  seg    lat     lon prof Magnitude
## 1 2000  1  6 14   0 20.5  9.905 -70.010  0.0       3.1
## 2 2000  1  7  5  51  1.0 10.313 -72.605  0.1       3.7
## 3 2000  1 11 22  31 36.4 10.409 -69.624  0.0       3.0
## 4 2000  1 13 19  13 25.5  6.469 -72.348  0.1       4.2
## 5 2000  1 14 12  14 47.4 10.627 -71.324  0.0       4.1
```

--- .class #id 
## Results of the App
With this app you can plot two type of histogram:   

* Number of seismic events per year

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

In this plot you can see that seismic activity is increasing from 2000 to 2010, this is because the number of seismological station are increased too.

--- .class #id 
## Results of the App (cont)
* Number of seismic events per magnitude

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

In this plot you can see that the mayority of the magnitudes are between 2 and 3.
