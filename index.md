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

Include image here

--- .class #id

## Application Overview

- Web application for learning country statistics
- Based on OECD 2014 Factbook data
- Simple Question and Answer interface
- Questions are auto-generated from the data

Include OECD.Stat Logo here

---

## Implementation

1. Shiny server randomly picks a statistic (ex. Population) and picks two countries in the data
2. Questions and options are generated based on the data
3. Provide feedback by showing the value and a plot

Include some R code here

---

## Further Directions

- Include interactive plot for questions and answers 
- Include more data
- Include time-series related questions (ex. how GDP of a country changed over last 5 years)
