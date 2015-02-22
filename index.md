---
title       : Slidify Presentation
subtitle    : Data Science Class 9 Project Part 2
author      : Blake Anderson
job         : 
framework   : html5slides        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : mathjax            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## A Good and a Bad Wastewater Operator's Fate
![alt text](http://alruralwater.com/about/News/images/2012_Awards_3.jpg) ![alt text](http://www.salem-news.com/stimg/february102010/handcuffed_new_.jpg)
<br />Hero or Goat

--- .class #id 

## The Difference
###### Can an Operator keep his solids and bugs in the plant?
![alt text](.//mod_1415118689814.jpg) 
<br />
Bugs going out of the plant to a stream. An operator's nightmare

--- .class #id
### The Solution is to use the State Point Analysis App. 
If the green underflow line crosses the black Solids Flux Line, the Return
Activated Sludge (RAS) flow needs to be increased.  If the Red State Point is 
above the black line, you need to pull out every trick because your solids
are almost destined to go into the river. 




--- .class #id
A Bad Day

```r
Q_RAS=1
```


![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- .class #id

RAS rate was increased, so the solids will stay in the plant.


```r
RAS_Q=1+RAS_Q
```

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 




