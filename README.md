# ENTRI-Module-5-Machine-Learning-project

Car Price Prediction Using Machine Learning
Project Overview
This project focuses on predicting car prices in the American market using machine learning models. A Chinese automobile company is planning to enter the US market and wants to understand the factors affecting car prices. By leveraging a dataset of car features and prices, we build and evaluate multiple regression models to identify significant predictors of car price and recommend the best-performing model.

Dataset
The dataset contains various features of cars and their corresponding prices. It was sourced from market surveys conducted by a consulting firm.

Download Dataset: https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link

Objectives
Understand the key factors influencing car prices in the US market.
Build regression models to predict car prices based on input features.
Identify the best-performing model using evaluation metrics:
R-squared
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
Perform feature importance analysis to identify significant variables.
Optimize the model using hyperparameter tuning for better performance.

Workflow
1. Data Loading and Preprocessing
Loaded the dataset and examined it for missing values, outliers, and inconsistencies.
Performed feature scaling, encoding of categorical variables, and correlation analysis to preprocess the data.
2. Model Implementation
Implemented five regression algorithms:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
3. Model Evaluation
Evaluated the models on:

R-squared: Measures how well the model explains the variability in the data.
MSE (Mean Squared Error): Measures the average squared difference between actual and predicted prices.
MAE (Mean Absolute Error): Measures the average absolute difference between actual and predicted prices.
4. Feature Importance Analysis
Identified the most significant features contributing to car prices using:

Feature importance from tree-based models.
Recursive Feature Elimination (RFE).
5. Hyperparameter Tuning
Performed hyperparameter tuning on the models to boost their performance using:

GridSearchCV
RandomizedSearchCV

Conclusion
The Gradient Boosting Regressor was identified as the best model for predicting car prices, offering high accuracy and low error rates.
Significant features affecting car prices include engine size, weight, fuel type, and horsepower.
Hyperparameter tuning further improved model performance, ensuring better generalization.

Future Work
Collect more data to improve model generalization.
Explore deep learning techniques for regression.
Integrate external factors like market demand, fuel prices, and brand perception into the analysis.


License
This project is licensed under the MIT License. See LICENSE for details.

