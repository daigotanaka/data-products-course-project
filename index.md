---
title       : My Tweets in 2014
subtitle    : Interactive visualization of impressions and engagements
author      : Daigo Tanaka (@DaigoTanaka)
job         : Tech Lead at FiveStars
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## How was my Tweets received?

### Motivation

- Building reputations for the profession is important to me.
- For online presence, Twitter is one of the great channels.
- I want to learn the characteristics of influential Tweets!

--- &twocol

## How do I do that?

*** =left

- In 2014, I tweeted 851 times.
- Each has metrics such as:
    - *Impressions*: the number of users who saw the tweet
    - *Engagements*: the number of user's actions such as retweets, replies,
      link clicks, profile clicks, and etc.

Let's visualize taking date and impressions as X and Y axes, respectively.
(I also colored English and Japanese tweets differntly)

*** =right

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

--- &twocol

## What about engagements?

*** =left

We can visualize as the size of the point.

This is called *bubble chart*.

*** =right

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

--- &twocol

## I want to see the actual tweets along the chart!

*** =left

- Now the chart needs to be interactive to reveal details of the data including
the content of the tweets.
- So, I built an app that has a slide bar to choose the months to display
all the tweets in the month along with the chart.
- Please try out the app at:
    https://daigotanaka.shinyapps.io/shiny_twitter_chart/

*** =right

<img src="./assets/img/screen_shot.png" style="width:100%"/>
