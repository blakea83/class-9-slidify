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

## You should use the State Point App to choice your fate.
#### A Good and a Bad Wastewater Operator's Fate 
![alt text](http://alruralwater.com/about/News/images/2012_Awards_3.jpg) ![alt text](http://www.salem-news.com/stimg/february102010/handcuffed_new_.jpg)


--- .class #id 

## The Difference between a good and bad Operator.
###### Can an Operator keep his solids and bugs in the plant?
![alt text](.//mod_1415118689814.jpg) 
###### Picture above is bugs leaving a plant this can make you a bad operator. 

--- .class #id
### The State Point Analysis App can help you keep your bugs in your plant. 
#### If the blue Underflow Line crosses the black Solids Flux Line, the Return Activated Sludge (RAS) flow needs to be increased. 
<br />
#### If the Red State Point is above the black line, you need to do everything possible to adjust the plant because your solids are almost certianly going into the river. 




--- .class #id
## A Bad Day

```r
Q_RAS=1
```


![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- .class #id

## RAS rate was increased, so the solids will stay in the plant.


```r
RAS_Q=1+RAS_Q
```

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 




