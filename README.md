# Credit-Risk-Modelling-using-ML

This project aims to develop a credit risk model to predict the likelihood of a borrower defaulting on a loan using various features from the dataset.

## Project Overview and Steps

The project involves the following steps:

1. Data Loading and Exploration: Loading the dataset and performing initial exploration to understand the structure and distribution of the data.
2. Data Preprocessing: Cleaning and preparing the data for modeling, including handling missing values and encoding categorical variables.
3. Feature Selection: Identifying the most significant features that influence the target variable.
4. Model Building: Building and training multiple classification models.
5. Model Evaluation: Evaluating the performance of the models using various metrics such as accuracy, precision, recall, and F1-score.

## Models Used
1. Random Forest
2. XGBoost
3. Decision Tree

## Conclusion

The credit risk model developed in this project provides insights into the likelihood of a borrower defaulting on a loan. Key findings include:

Model Performance: The Random Forest, XGBoost, and Decision Tree models achieved accuracies of 76.37%, 78%, and 71% respectively on the test dataset. XGBoost performed little better after performing hyperparameter tuning through GridSearchCV.
Classification Reports: Each model's precision, recall, and F1-score indicate their effectiveness in distinguishing between defaulters and non-defaulters.
