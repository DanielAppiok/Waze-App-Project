# Predicting User Churn on the Waze App

**Overview :**

The goal of this project was to create a multiple logistic regression and random forest model to predict user churn on the Waze App. This project utilized the Waze App dataset collected in the organization database system. The final random forest model performed with 81% accuracy and 46% precision determining what features were most important in causinh a user churn. Based on the model, the kilometers per hour, number of days after onboarding, and percentage sessions in last month were most influential in determining user churn. 

**Data Understanding:**

The Waze App data came from the organization dataset. The data consisted of approximately 15k rows and 11 columns. The features included information on sessions and total sessions, drives, number of days after onboarding, and driving days. Additional useful features were added through feature engineering.

**Modeling and Evaluation :**

A random forest model comprising 300 decision trees was used to determine feature importance in who would churn or not. An XGBoost classifier was used as an alternative to determine the best performing model of the two.. The overall model performed fairly well with 81% accuracy but a poor 46% precision. 

**Conclusion :**

If the model is being used to drive consequential business decisions, then no, it should not be used. The model is not a strong enough predictor, as made clear by its poor recall score. However, if the model is only being used to guide further exploratory efforts, then it can have value.
