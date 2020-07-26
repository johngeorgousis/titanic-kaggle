# Overview
This is my project on the Titanic Kaggle Competition. The aim is to use data about the people who were on the Titanic (e.g. age, family members, ticket fare, etc.) and make predictions about who survived and who didn't on unseen data. 


## Procedure
I took a raw dataset and pre-processed the data to prepare it for ML algorithms. 
Then, I instantiated 5+ ML models (SVM, Naive Bayes, AdaBoost, etc.) and performed grid search.
After checking their validation scores, I chose to train the AdaBoost model with the Gaussian Naive Bayes one as its base estimator. 
Finally, I fit it to the whole dataset and submitted my predictions to get an accuracy score from Kaggle.
