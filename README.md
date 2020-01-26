# Brand Analysis on Car Brands 

![](https://wallpaperaccess.com/full/11207.jpg)

## Overview

As an analytics consultant to (i) brand manager, (ii) product manager and (iii) advertising manager of car brands, the goal is to provide advice/insights to these individuals based on the analysis of social media conversations. The detailed tasks are described below. We use cars as an example of a “high involvement” good. 

1.	Wrote a scraper using Selenium to fetch messages posted in Edmunds.com discussion forums. 

2.	Fetched around 4,000-5000 posts about cars from Edmunds.com. We choose a forum dedicated to a particular brand or model. The idea is to have multiple brands and models being discussed without one of them being the focal point. 

3.	Once we fetch the data, we find the top 10 brands from frequency counts. We write a script to count the frequencies of words and replace frequently occurring car models with brands so that we deal with only brands and not models.

### Task A: 

We identifed top 10 brands by frequency. From the posts, we calculated lift ratios for associations between the brands. For lift calculations we show the brands on a multi-dimensional scaling (MDS) map. 

### Task B: 

We provided insights to the brand managers from our analysis in Task A.
  
### Task C: 

Evaluated the 5 most frequently mentioned attributes of cars in the discussion. Note that the same attribute may be described by different words – e.g., pick-up and acceleration may both refer to a more general attribute, “performance”. We have made suitable replacements and pick the 5 most frequently mentioned brands. Determine attributes that are most strongly associated with these 5 brands?

### Task D: 

Provided advice to (i) product manager, and (ii) marketing/advertising manager of these brands based on the analysis in Task C.

### Task E: 

Determined most aspirational brands in terms of people actually wanting to buy or own. Determined the business implications for this brand.

## Results

BMW appears to be the most aspirational car brand in the mid-size sedan segment followed closely by its German counterpart Audi. BMW has a lift value of 3.48 and Audi has a lift value of 2.98 in association with aspirational customer sentiment. Next in the list are Hyundai and Toyota, leading Asian car manufacturers. Hyundai and Toyota's appearance so high on the list was surprising, but may confirm the popular belief that American car buyers are not very brand conscious.

The low co-occurrence of other brands and aspirational phrases reflects their market positions as reliable economy cars, not luxury mid-sized sedans which people "aspire to own". Even if they offer higher-end product features, the brand image for BMW and Audi are superior from customers' perspectives. Honda, Kia, Ford, Volkswagen appear further down in the list. These brands are considered family-oriented cars with a strong focus on safety and comfort, while being affordable.

We have included phrases such as ‘wish to own’, ‘wish to buy’, ‘want to buy’, ’looking to buy’, ‘desire to buy’, ‘dream car’, ‘have to own’, ‘future car’, ‘want to own’, ‘desirable’, etc. as aspirational words. These words were picked after ensuring that a sample of comments retrieved for a given phrase displayed strong aspiration or wistful intent to buy a car of a certain make or model.
