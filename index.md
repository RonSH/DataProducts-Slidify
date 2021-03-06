---
title       : Coursera Data Products
subtitle    : Wordcloud Usefulness
author      : RonSH
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [quiz, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Wordcloud

A Wordcloud is a tool for visualizing text.  It works by isolating the most frequently used words from a text.  And, the more frequently a word appears the larger it is displayed.  

A Wordcloud is meant to provide visual clues to content of a text, what's being tweeted, hotel reviews, etc...

Of course, this wouldn't be as useful if we only see common words like "the","it","a", etc...  That's why its essential to clean the text first using a package like 'tm'

---  

## Judge Wordcloud Usefulness for Yourself

The Shiny App created for the class project is a Wordcloud of text from this course's video lectures.  It allows you to visualize the content of each week's lectures by simply choosing a week and clicking upon 'Change'.

---

## Sample: Wordcloud of this Presentation

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

--- &radio

## Wordcloud Usefulness Survey

Did you find a Wordcloud to be useful?

1. _Y_
2. N
