# Overview
This is my project on the Titanic [Kaggle Competition](https://www.kaggle.com/c/titanic). The aim is to use data about the people who were on the Titanic (e.g. age, family members, ticket fare, etc.) and make predictions about who survived and who didn't on unseen data. 


## Procedure
- I took the raw dataset and pre-processed it to prepare the data for ML algorithms. 
- I instantiated 5+ ML models (SVM, Naive Bayes, AdaBoost, etc.) and performed grid search to tune the hyperparameters.
- After checking their validation scores, I chose to train the AdaBoost model with the Gaussian Naive Bayes one as its base estimator. 
- Finally, I fit it to the whole dataset and submitted my predictions to get an accuracy score from Kaggle.
