# Yelp Analysis and Rating Prediction
## Overview 
Yelp is a regional directory platform and review site with social networking tools. The website provides crowd-sourced reviews for local businesses (spas, restaurants, department stores, pubs, home-local services, shops, cars). This helps users to give business ratings and reviews. Normally, the review is a brief text composed of a few lines of about 100 words describing various user experiences with respect to various dimensions. This offers business owners the opportunity to improve their products and customers to choose among the best available sector.

## Business Value/Analysis Aim
The management might not have enough time to go through each and every review. If valuable information and insights can be provided to them at a glance, it can be really helpful and time-saving. And not only for the management but also for the customers who are trying to know more about the restaurant and need some help in ordering or selecting the restaurants. After all, in today’s world, every person prefers to read reviews and feedbacks before they take a decision. In our project, we have used Natural Language Processing and Machine Learning to achieve these business and customer goals. We have focussed on Sentiment Analysis, Topic Modelling, Data Analysis, and Classification for rating prediction. 

## Data Source and Preparation
- The dataset is available at https://www.yelp.com/dataset​. It contains 6,685,900 reviews for 192,609 businesses based in 10 metropolitan areas.
- As a part of the data preparation and cleaning process, corrected the datatypes of every column in the dataset and dropped all the unnecessary columns.
- Wanted to focus on only one city which had the maximum no of reviews for restaurants. 
- In this case, it was Las Vegas. Hence, filtered the dataset records to keep only reviews for restaurants in Las Vegas. The resultant dataset had 1,242,711 reviews for 6450 restaurant businesses.

## Exploratory Data Analysis
#### 1. Which are the top 10 categories with the maximum number of reviews?
<img src="images/Top 10 Businesses.png" width="800" height="500">
**Interpretation:** Restaurants are the most reviewed business category followed by shopping, food and home services. It is always better to focus on one category for analysis in order to get relevant insights from data. Hence, reviews were filtered in the dataset to keep only restaurant category reviews.

#### 2. Which city has the maximum number of restaurant reviews?
<img src="images/Max review restauranrs.png" width="800" height="500">
**Interpretation:** Las Vegas has the maximum number of reviews. The reviews were filtered to keep the Las Vegas restaurant reviews.
 
## Best-rated restaurants in Las Vegas
<img src="images/Review posted over time.png" width="800" height="500">
**Interpretation:** From April 2016 to December 2018, it can be observed how the number of reviews for each restaurant varies. For example, for Nacho Daddy the reviews dropped from 100 in May 2016 to 20 in June 2016. It stayed the same for quite some time until Sept 2016. This information can be useful for the management to evaluate the possible reasons behind the drop and gain in number of reviews and when it happened.

Now, after cleaning the dataset, sentimental analysis was applied on the data to achieve analysis aim.
#### Sentiment polarity distribution for the restaurants
<img src="images/Sentiment polarity.png" width="800" height="500">





