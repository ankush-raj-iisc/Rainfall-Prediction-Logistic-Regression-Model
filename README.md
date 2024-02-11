# Rainfall-Prediction-Logistic-Regression-Model
Approximately ten years' worth of daily weather observations from multiple Australian weather stations are included in the Rain in Australia dataset. My job as a data scientist at the Bureau of Meteorology is to develop a fully automated system that can determine whether it will rain at a specific area tomorrow based on the weather data for that location as of today.

Since logistic regression is more appropriate for categorization/classification issues like forecasting if it will rain tomorrow, I'll use it. An essential first step in machine learning is determining whether a given problem is a regression or classification problem.

# The following steps are followed in this project:
1. Obtaining a real-world Kaggle dataset (https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
2. Exploratory data analysis and visualization
3. Dividing a dataset into test, validation, and training sets
4. Replacing missing values in numerical columns using imputing
5. Putting numerical features in a range of (0,1)
6. Utilizing one-hot vectors to encode categorical columns
7. Using Scikit-learn to train a logistic regression model
8. Assessing/Evaluating a model with a test set and validation set
9. Reloading a model after saving it to disk
