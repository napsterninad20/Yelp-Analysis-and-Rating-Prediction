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
<img src="P3.png" width="600" height="300">


