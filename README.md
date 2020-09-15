# Twitter-Sentimental-Analysis

## Dataset Information

I use and compare various different methods for sentiment analysis on tweets (a binary classification problem). The training dataset is a csv file of type `tweet_id,sentiment,tweet` where the `tweet_id` is a unique integer identifying the tweet, `sentiment` is either `1` (positive) or `0` (negative), and `tweet` is the tweet enclosed in `""`. Similarly, the test dataset is a csv file of type `tweet_id,tweet`.

## Requirements

There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.  
* `numpy`
* `scikit-learn`
* `scipy`

