# Finding-Donors:
Udacity ML cross-skilling Nanodegree December 2022 - January 2023
# Project Details:
This project is designed to test many supervised learning algorithms available in sklearn, providing a method of evaluating just how each model works
and performs on a certain type of data, using Optomization. It is important in machine learning to understand exactly when and where a certain algorithm should be used, and when one should be avoided.
So this project provide a pipeline for upcoming developers to use and just change the ML algorithm they uss + comparing it to two other models (or even more of your choice).
# Specifications:
## Exploring the Data
+ Implementation correctly calculates the following:
    
    * Number of records.
    
    * Number of individuals with income >$50,000.
    
    * Number of individuals with income <=$50,000.
    
    * Percentage of individuals with income > $50,000.
+ Correctly implements one-hot encoding for the feature and income data.
## Evaluating Model Performance
+ correctly calculates the benchmark score of the naive predictor for both accuracy and F1 scores.
+ The pros and cons or application for each model is provided with reasonable justification why each model was chosen to be explored (Including references).
+ successfully implements a pipeline in code that will train and predict on the supervised learning algorithm given.
+ correctly implements three supervised learning models and produces a performance visualization.
## Improving Results
+ Justification is provided for which model appears to be the best to use given computational cost, model performance, and the characteristics of the data.
+ There is a clear and concise describtion of how the optimal model works in layman's terms to someone who is not familiar with machine learning nor has a technical background.
+ The final model chosen is correctly tuned using grid search with at least one parameter using at least three settings. If the model does not need any parameter tuning it is explicitly stated with reasonable justification.
+ I reported the accuracy and F1 score of the optimized, unoptimized, models correctly in the table provided. Student compares the final model results to previous results obtained.
## Feature Importance
+ I chose five features which I believe to be the most relevant for predicting an individual's income. Discussion is provided for why these features were chosen.
+ implemented a supervised learning model that makes use of the `feature_importances_` attribute. Additionally, I discussed the differences or similarities between the features they considered relevant and the reported relevant features.
+ analyzing the final model's performance when only the top 5 features are used and compares this performance to the optimized model from Question 5.
