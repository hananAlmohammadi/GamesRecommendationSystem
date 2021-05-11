[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)![Misk Logo](https://i.ibb.co/KmXhJbm/Webp-net-resizeimage-1.png)

---

# Project 4: Content-Based Recommender System 

# Introduction 

## published Kaggle kernel:


[ps4-games](https://www.kaggle.com/ww1234/ps4-games)

## Datasets Description 

The dataset contains all games for PlayStation 4: 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|game|object|game|Contains the games name| 
|score|int|game|Contains maximum TrueTraphy score|
|leaderbord|float|game|Contains Game Leaderboard ratio|
|gamers|int|game|Contains the number of gamers plying this game in truetrophies website|
|comp_perc|float|game|Contains percentage of how many gamer complete this game|
|rating|float|game|Contains a rating from people who play this game by out of 5|
|url|object|game|Contains URL that have more information about each game|
|min_comp_time|str|game|Contains maximum estimated time to unlock all trophies|
|max_comp_time|int|game|Contains a rating from people who play this game by out of 5|


## Executive Summary:

[ps4-games](https://www.kaggle.com/ww1234/ps4-games)
The dataset comes from a Kaggle page named “ps4-games: video games Dataset from truetrophies website”.This dataset include all games for PlayStation 4 for the present.It comes from from truetrophies website contains 1584 games information and 10 features about games information such as games name and other details like score ,rating for each game etc.


## Problem Statment

This project we are aims to build a Content-based recommender system based on games and the similarities between them. We will implement two algorithms from sklearn neighbors library the first one is Nearest Neighbors which is unsupervised machine learning algorithm to find the most similar games based-on gamers, comp_perc, rating, min_comp_time and max_comp_time. The second one is K-Neighbors Classifier which is supervised algorithm to find the most similar games based-on gamers, min_comp_time and max_comp_time.

## Conclusions and Recommendations

In this project we built a Content-based recommender system based on games and the similarities between them. we implement two algorithms the first one is Nearest Neighbors which is unsupervised machine learning algorithm. The second one is K-Neighbors Classifier which is supervised algorithm. we didn't use metric to measure the performance since most recommenation system evaluates on how close a recommender from the original point.
 



# Group Members:

- Hanan Almohammadi 
- Nesreen Alqahtani
- Samaher Alharbi
