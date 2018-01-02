---
title       : Developing Data Products Peer Graded Assignment 2
subtitle    : Please click right arrow key to cycle through slides
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## January 1st, 2018
```r
plot_ly(mtcars, x = ~mpg, y = ~hp, type = "scatter", color = ~cyl) %>%
    layout(xaxis = x, yaxis = y)
```
![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

--- .class #id 

## Thank you!




