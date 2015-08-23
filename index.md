---
title       : Web Application for Learning Country Statistics
subtitle    : 
author      : Ted Yun
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## How much do you know about the world?

<img src="app_screenshot.png" style="width: 800px;"></img>

---

## Application Overview

- Web application for learning country statistics
- Based on OECD 2014 Factbook data
- Simple question-and-answer interface
- Answers include plots that are easy to understand
- Questions are auto-generated from the data

<img src="externalLogo-en.gif" style="margin-top:100px"></img>

---

## Implementation

1. Shiny server randomly picks a statistic (ex. population, GDP per capita) and picks two countries in the OECD Factbook data.

```
## [1] "Population"
```

```
## $country
## [1] "Hungary"
## 
## $value
## [1] 9920.361
```

```
## $country
## [1] "Japan"
## 
## $value
## [1] 127515
```

---

## Implementation

<ol start="2">
    <li>Questions and options are generated based on the data.</li>
    <li>Provide feedback by showing the values in a plot.</li>
</ol>

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 

## Further Directions

- Include interactive plot for questions and answers 
- Include more data
- Include time-series related questions (ex. how GDP of a country changed over last 5 years)
