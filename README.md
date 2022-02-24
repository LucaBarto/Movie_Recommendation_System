# Movie_Recommendation_System

The purpose of the present project is to create a recommendation system for predicting the rating of movies.

A recommendation system is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item.

As a data source for training and final evaluation of the system will be used the MovieLens 10M Dataset from https://grouplens.org/datasets/movielens/10m/.

The residual mean squared error (RMSE) will be used as the evaluation system of the recommendation system.
The ultimate goal is to obtain an RMSE value of less than 0.86490.

In a first phase, the data will be imported and the sub-data sets configured for training and final evaluation.

We will start to represent the base data structure using table and charts in order to highlight the 
relationship between the rating and the features; once it is clear how each feature effects the outcome, 
it is possible to discard the ineffective ones.

A data cleanup will then be performed to focus only on relevant data.

Finally, selected algorithms will be implemented and then respective RMSE values compared
