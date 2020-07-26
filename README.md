# Overview
This is my project on the [Titanic Kaggle Competition](https://www.kaggle.com/c/titanic). The aim was to use labeled data about the people who were on the Titanic (e.g. age, family members, ticket fare, etc.) and make predictions about who survived and who didn't on unseen data. 


## Procedure
- I took the raw dataset, explored it, and pre-processed it to prepare the data for ML algorithms. 
- I instantiated 5+ ML models (SVM, Naive Bayes, AdaBoost, etc.) and performed grid search to tune the hyperparameters.
- After checking their validation scores, I chose to train the AdaBoost model with the Gaussian Naive Bayes model as its base estimator. 
- Finally, I fit it to the whole dataset and submitted my predictions to get an accuracy score from Kaggle.
