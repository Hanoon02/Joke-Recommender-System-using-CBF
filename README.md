# Joke Recommender System using Content Based Filtering

A joke recommender system build using classical ML concepts for Machine Learning (CSE344)
 
## About

This project focuses on constructing a recommendation system tailored to suggest ratings for newly introduced jokes. We will be using the [Jester Joke Dataset (Dataset 1)](https://eigentaste.berkeley.edu/dataset/). The ratings will be obtained using Content Based Filtering methods that leverages Natural Language Processing (NLP) and associated concepts to extract features from the jokes. The features will be used to train models to predict the ratings.

## Methodology

We build two systems, one using a user-based approach and the other using a joke-based approach.  
The user-based approach predict the ratings for the existing user.  
The average-rating approach predict the average ratings of a new joke to any user.  

## Results

The SVR with C=2 yielded the highest R-square value, achieving an average R-squared score of 0.354.   
R-squared serves as a measure of the model's goodness of fit, with a higher value indicating a better fit to the data.  

### Contributors

Lakshya, Zubaida, Hanoon, Sumit, Nitish