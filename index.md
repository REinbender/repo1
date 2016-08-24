---
title       : Best car for a road trip!
subtitle    : A Cost Benefit Analysis
author      : Ryan Einbender
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## The Project

For this course we were tasked with creating a pitch presentation where I will be describing to the view why they should use my Shiney application and how it will benefit their lives.

For this project I used the "mtcars" database and developed a tool to help road trippers isolate the best fit car for their specific road trip needs.

Here is the link to my application:https://reinbender.shinyapps.io/myApp/



--- .class #id 

## How to choose?

The shiney application allows you to customize your car requirements to see which style of car best suits your individual needs and wants. 

Using any combination of the following parameters:
Distance to travel
Gas price
Gas budget
number of cylinders
displacement
total horse power

--- .class #id 

## backend Application Data structure
Here is what our data looks like that we will be deriving our solutions from.
in this data set we have 32 cars and 11 variables not including flexable fields like gas price, budget and distance.

```r
head(mtcars)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

--- .class #id 

## Why use this application?

This application will make the user better informed and enhance the their overall road trip experience for the following reasons

1. Choosing the car for the specific road trip
2. Cost savings
3. Ease of mind that you made an informed decision
