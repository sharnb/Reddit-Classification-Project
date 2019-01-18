# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & Classification

Author:  Sharnique Beck

### Problem Statement

An online comic book store wants to determine where forum posts are originating from. I will create and train a classifier model on which subreddit a given post came from, Marvel or DCcomics.
 
### Executive Summary
### Contents:
- [Part_1: Data Gathering]()
- [Part_2: Cleaning Data]()
- [Part _3: Modeling and Evaluation]()

Data Dictionary:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|id|str|reddit_data|Assure no data duplication in collection set.|
|title|str|Clean_data|Title of post on subreddit to be used in modeling|
|subreddit|str|Clean_data|Subreddit that title came from.|
|y|int|Train/Test|Class to be predicted|


## Conclusions and Recommendations
The model will be able to predict a posts subreddit with very good accuracy
With more time I would like to Collect more data, possibly include commentse, as well as explore and go more indepth with some models such as random forest and extra trees parameters further.

Use for sentiment analysis of combined comic boards, weight comment biases, see if post or comments given are Constructive vs critical.