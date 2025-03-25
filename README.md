# Heart-Disease-Prediction
Project Overview

This project focuses on predicting the presence or absence of heart disease using three machine learning models by utilizing the UCI Heart Disease dataset. The dataset was preprocessed, followed by model development, evaluation, and optimization. The models used in this project include Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM). The project demonstrates data preprocessing, model development, evaluation, and optimization, successfully achieving accuracy scores of 83%, 84%, and 85%, respectively for each model.


The Three Chosen Models

(1) Logistic Regression
(2) Random Forest Classifier
(3) Support Vector Machine (SVM)


Included Tasks in this Project

1. Data Preprocessing
Handling Missing Values
Outlier Detection
Data Encoding
Feature Selection
Train-Test Split
Feature Scaling

2. Model Development and Evaluation
Model Implementation
Model Training
Making Predictions
Model Evaluation using Classification Reports

3. Model Optimization
Hyperparameter tuning using GridSearchCV
Cross-validation to ensure generalization
Model Performance Evaluation (Accuracy, Confusion Matrix, Classification Reports)
Model Comparison and Selection of the Best-Performing Model

Best Model Selection - SVM model

The SVM model achieved the highest test accuracy of 85%, indicating strong generalization.

The Random Forest model achieved 84% accuracy but showed slight performance variations across validation folds.

The Logistic Regression model had 83% accuracy but was outperformed by the other models.

Confusion Matrices Analysis:
Logistic Regression: Moderate misclassifications but stable results.

Random Forest: High recall for class 1 but some misclassification in class 0.

SVM: Best balance between precision and recall.

Precision-Recall Curves: The SVM model demonstrated a strong balance between precision and recall, further supporting its selection as the best-performing model.

