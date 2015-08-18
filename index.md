---
title       : Mtcars Analysis
subtitle    : linear model for mpg
author      : shawn huang
job         : Engineer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Overview
### Purpose

provide an interactive approach to build up linear model for mpg in mtcars

### Procedure

* select the variables in the sidebar panel.
* click linear model tab in the main panel.
* check the output of the linear model in the main panel.

--- .class #id 

## Datasets 



The variables in the mtcars dataset are mpg,cyl,disp,hp,drat,wt,qsec,vs,am,gear,carb  
This following is the first 10 rows in mtcars


```
##                    mpg cyl  disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6 160.0 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6 160.0 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4 108.0  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6 258.0 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8 360.0 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6 225.0 105 2.76 3.460 20.22  1  0    3    1
## Duster 360        14.3   8 360.0 245 3.21 3.570 15.84  0  0    3    4
## Merc 240D         24.4   4 146.7  62 3.69 3.190 20.00  1  0    4    2
## Merc 230          22.8   4 140.8  95 3.92 3.150 22.90  1  0    4    2
## Merc 280          19.2   6 167.6 123 3.92 3.440 18.30  1  0    4    4
```

---

## Select variable

We will use the variables showing in the sidebar to build up the linear model for mpg.  
Please select the variables in the sidebar.  

<img class=center src=./fig/sidebar.png height=500>

---

## Linear model


* Select the variables from the sidebar . ex: cyl,disp,hp,drat,wt,qsec,vs,am,gear,carb
* Show the linear model result in the main panel
<img class=center src=./fig/main.png height=500>
