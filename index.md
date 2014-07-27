---
title       : Stock Price Explorer
subtitle    : Project for Developing Data Products class on Coursera
author      : https://github.com/coursera-/CourseraDevelopingDataProductsSlidify
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Get started with shiny!

* Project for Developing Data Products class on Coursera:
  * Shiny app to explore historical data for stock prices
  * Use "quantmod" R package to access the data

```r
library(quantmod)
```
* Hands-on experience with shiny package:
  * Building UI using predefined UI blocks
  * Using different interactive widgets for user input
  * Implementing reactive processing of user input
  * Sending produced plot of stock prices from server back to UI
* Next three slides show features available in the app!

---

## (1/3) Stock selection

* Select one of the following stocks: AAPL, FB, GOOG, TWTR

!["stock selection"](assets/img/s1.png)

---

## (2/3) Price type selection

* Choose one of the following price types: open, high, low, close

!["stock selection"](assets/img/s2.png)

---

## (3/3) Range of dates selection

* Select range of dates 

!["stock selection"](assets/img/s3.png)

