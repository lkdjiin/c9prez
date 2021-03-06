---
title       : Temperature Converter
subtitle    : From Kelvin to Celsius to Kelvin
author      : me
job         : Student
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is Kelvin

The kelvin (K) is a unit of measure for temperature based upon an absolute scale.

0 K is know as the _absolute zero_, the temperature at which all thermal motion ceases.

--- .class #id 

## What is Celsius

The degree Celsius (°C) is a unit of mesure for temperature used by most countries
in the world.

Historically it was defined like:

- **0 °C** is the **freezing** point of water
- **100 °C** is the **boiling** point of water

--- .class #id

## Formulas

The formulas to convert from and to kelvin and Celsius are ridiculously
simple.

### kelvin to Celsius: °C = K - 273.15

### Celsius to kelvin: K = °C + 273.15

For example, 0 K is:


```r
k2c <- function(x) x - 273.15

cat(paste(k2c(0), "\n"))
```

```
## -273.15
```

--- .class #id

## The Shiny Application

The temperature converter is a shiny application to convert kelvin to Celsius
and Celsius to kelvin.

[Go to temperature converter](https://lkdjiin.shinyapps.io/c9project)

Enter your temperature, choose the conversion type, either K to °C or
°C to K, and hit the *Convert* button. That is!


