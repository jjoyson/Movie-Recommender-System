# Milestone Report

# MOVIELENS

The largest movielens dataset was used to grab movies and potential features such as genres, tags and keywords. This dataset also introduces sample users and their ratings of random movies. This was used to create target classifications of movies that were rated by a user. Furthermore, a threshold was used to contribute to the target classifications of different movies. This aspect of the classification will be used as the interaction portion of the recommender since the user can control this.

# ALGORITHM

There was a lot of data cleaning (understanding APIs and how to featurize aspects of a movie). The most simple classifier was used to test out the featurization and different datasets were tried till one was chosen. So far, only the logistic Regression classifier was used to classfy movies of a user and then predicting recommendations.

Active Learning methods were used to test which would be the best movies to ask the user once fully implemented and different metrics such as accuracy, precision, recall and f1 were plotted. These plots are already part of the notebook for a "test" user

# TOKENIZATION

The movielens dataset does not include cast or keywords so there needs to be different API calls to tokenize these options. Due to time restrictions and lack of cast list calls (actors need to requested and then check if the actor was in a given movie) which will create more calls.

Besides that, genres, tags and keywords were featurized and binary (0/1) assocaitations were given to represent if the values are present in the given movie. Keywords need to be cleaned further since some tags include random characters that would be duplicate in different movvies.

# DATA (URL)

https://www.dropbox.com/sh/d2hfvn33oswhe33/AABUYwGIK8h3GJu0pZt5VMZha?dl=0