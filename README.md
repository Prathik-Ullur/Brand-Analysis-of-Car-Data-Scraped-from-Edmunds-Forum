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

### Insights we offered brand managers.

The brands with the highest common lift are Hyundai and Kia with the lift value equal to 4.29, which turns out to be the highest between any 2 combinations among the top 10 brands. The frequency of occurrence of Hyundai is 887 and that of Kia is 522 among the total posts and comments scraped.

Digging deeper to understand the co-occurrence of these brands in comments, we realized that Kia and Hyundai, both belong to the same parent company. Hyundai and Kia are both leading car manufacturers from South Korea. Hyundai Motors bought a 51% stake of Kia Motors in 1998 when the latter declared bankruptcy.

The numbers suggest that customers closely associate the two car brands together. Brand managers of the two sister companies must focus on differentiating the customer sentiment associated with each brand. In the long run, this could lead to brand cannibalism where the brands would be competing for market share. The management must focus more on driving advertising and marketing campaigns to spread awareness about each of these brands in a unique manner.

Another way to improve brand differentiation is by focusing on product features specifically intended for targeted customer segments. This would not only change customer perception but also help carve out two niche markets for each of these brands, which the parent company would benefit from. Hyundai is typically known for its reasonably well-sized cars with luxury interiors. They could build on top of existing features making their cars attractive for the older generation who are more focused on quality and comfort. Kia is known for its sporty design, yet affordable prices meant for the younger generation. Driving digital marketing campaigns, rallies and concerts for Kia customers would help establish brand loyalty among the millennials and Gen-Z.

### Provide advice to (i) product managers, and (ii) marketing/advertising managers of these brands.

### Product Managers

#### Honda:

Honda has a low lift for “comfort” and “interior” compared to a Toyota or a Hyundai. All three brands compete in the space in the market, but our analysis shows that customers perceive Toyota and Hyundai sedans as confortable cars having pleasant interiors. Product managers for Honda's upcoming model years should focus on improving the quality of their models' interiors, paying particular attention to features like more leg room, quiet cabins, and sufficient head room for tall passengers. Addressing buyers' lack of enthusiasm about interiors and comfort will help Honda to be more competitive and bring them on par with their competitors.

#### Ford:

Ford was the second most frequently mentioned maker in the midsize sedans forum, but it scores low on every attribute association compared to the other top brands. This does not mean that people strongly dislike Ford cars, but instead that there is ambivalence and a lack of association with Ford and any given attribute. It seems to suggest that public perception of Ford cars is somewhat bland. In order to increase passion for Ford cars, a product manager at Ford, can afford to take more risks in their approach to building future models, innovating their design and improving performance and comfort. In a highly competitive market, if Ford wants to maintain its popularity it will have to generate more enthusiasm in future buyers. Otherwise, there is a high probability that customers could move on to purchase other brands that are highly associated with the attributes that they desire.

### Marketing/Advertising Managers

#### Mazda:

Mazda stands out above the competition in its association with performance in discussions on Edmunds. When people mention Mazda in their posts, they are more likely to also use words like “power”, “speed”, “engine” and “turbo,” among others. Mazda can capitalize on this association by advertising to this strength. People already perceive Mazda cars as sporty and fun to drive, so they should exploit this public opinion by targeting their advertising to young potential buyers and older mid-life-crisis buyers. Buyers looking for high performance cars may not place as high importance on fuel economy, so Mazda should not worry about slightly lower lift values for fuel economy. However, if it has cars with fuel economy that is similar to other makers, it might be able to gain market share by advertising that it is able to maintain top performance and fuel economy.

#### Toyota:

Toyota has a low lift value in “fuel economy” compared to a Hyundai, and the lowest "fuel economy" lift of any brand in the top 5. This means that people don’t strongly associate Toyota with fuel economy. This is does not reflect differences in these brands' products: in reality, gas mileage for Hyundai and Toyota models are similar as per car specifications. For example, the 2019 Toyota Corolla gets 32 combined miles per gallon (MPG), while the 2019 Hyundai Elantra gets only 28 combined MPG. The Toyota car is actually superior to Hyundai in MPG, but this advantage is not perceived by the end customer. Therefore, Marketing and Advertising managers for Toyota should focus in their upcoming campaigns to project a fuel-efficient image of Toyota.

### Determine the most aspirational brand in the data in terms of people actually wanting to buy or own. Determine business implications for this brand.

BMW appears to be the most aspirational car brand in the mid-size sedan segment followed closely by its German counterpart Audi. BMW has a lift value of 3.48 and Audi has a lift value of 2.98 in association with aspirational customer sentiment. Next in the list are Hyundai and Toyota, leading Asian car manufacturers. Hyundai and Toyota's appearance so high on the list was surprising, but may confirm the popular belief that American car buyers are not very brand conscious.

The low co-occurrence of other brands and aspirational phrases reflects their market positions as reliable economy cars, not luxury mid-sized sedans which people "aspire to own". Even if they offer higher-end product features, the brand image for BMW and Audi are superior from customers' perspectives. Honda, Kia, Ford, Volkswagen appear further down in the list. These brands are considered family-oriented cars with a strong focus on safety and comfort, while being affordable.

We have included phrases such as ‘wish to own’, ‘wish to buy’, ‘want to buy’, ’looking to buy’, ‘desire to buy’, ‘dream car’, ‘have to own’, ‘future car’, ‘want to own’, ‘desirable’, etc. as aspirational words. These words were picked after ensuring that a sample of comments retrieved for a given phrase displayed strong aspiration or wistful intent to buy a car of a certain make or model.
