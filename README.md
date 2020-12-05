# Project 3: Multi-Classification
### Authors: Alex Zieky, Ben Spilsbury, and David Shin

![img](./images/twitter.png.png)

## Overview


## Business Problem

To understand the sentiment towards brands, we need to break down Tweets and ____. Classifying Twitter post into different sentiments can help to find ways to improve brand images and products.

## Data

We utilized a dataset from CrowdFlower that has over 9,000 Tweets about Apple and Google products.
*  https://data.world/crowdflower/brands-and-product-emotions

## Method

### Initial Data Setup

Drop ambiguous data and divide into each brand.

### Exploratory Data Analysis

In our notebook, we created wordclouds to show the top words in both the Positive and Negative sentiment.

### Models

Our initial models were created using only a Positive/Negative classifier. Later, we ran a Multi-Class Text Classification model that could classify a Tweet as one of the three classes (Positive, Negative, No Emotion). 

### Evaluation

WE evaluated our models for both Accuracy and F1 scores. We looked into Accuracy initially because in the context of Tweet classification, wrongly classifying Tweets into Positive or Negative sentiments didn't pose as a critical issue. We also utilized F1 score due to the imbalance in our dataset of Positive/Negative/No Emotion Tweets.

## Conclusions

## Further Research

For further development of our models, we can continue to branch out into other brands. It also looks like a majority of this data was from a particular event during SXSW, so taking Tweets from a larger span of time may help to improve our model accuracy. 

```
## Navigation
├── README.md
├── images
│   ├── twitter.png
