# Wine Quality Prediction with Random Forest

## Overview
This project employs the Random Forest algorithm to predict red wine quality based on chemical properties. The dataset, sourced from Kaggle, contains features like acidity, residual sugar, and alcohol content, alongside a quality rating.

## Methodology
### Data Preprocessing:

Loaded and inspected the dataset using Pandas.
Handled missing values and checked data types.
Visualized data distributions using histograms.

### Stratified Splitting:

Stratified split of the data to maintain quality category proportions in training and testing sets.
Feature Scaling:

Standardized features using the StandardScaler to ensure uniform scales for model training.

### Model Building:

Utilized a Logistic Regression model as a baseline, achieving an initial accuracy of 95%.
Addressed class imbalance by adjusting class weights in the model.
Handling Imbalanced Classes:

Implemented Synthetic Minority Over-sampling Technique (SMOTE) to balance class distribution in the training set.
Random Forest Model:

Implemented a Random Forest Classifier with hyperparameter tuning.
Achieved improved accuracy, precision, recall, and F1 score metrics on the test set.
Model Evaluation:

Generated a confusion matrix and a classification report for a detailed performance overview.

## Results
The Random Forest model demonstrates enhanced predictive capabilities, providing accurate and balanced predictions for red wine quality categories.
