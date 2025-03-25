# Heart-Disease-Prediction

## **Project Overview**

This project focuses on predicting the presence or absence of heart disease using three machine learning models with the UCI Heart Disease dataset. The dataset was preprocessed, followed by model development, evaluation, and optimization. The models used in this project include Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM). The project demonstrates data preprocessing, model development, evaluation, and optimization, achieving accuracy scores of 83%, 84%, and 85%, respectively for each model.

The dataset used in this project is sourced from [Kaggle - UCI Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data).

### **Dataset Information:**
- **Description**: The dataset contains 16 columns representing various medical attributes of patients, including factors like age, sex, cholesterol levels, blood pressure, and other health indicators related to heart disease.
- **Size**: 920 rows and 16 columns.
- **Data Types**: Columns consist of both numerical (e.g., age, cholesterol levels) and categorical (e.g., presence of disease, sex) data.

### **Data Preprocessing:**
- Missing values were handled by dropping rows/columns with a low percentage of missing values. For columns with high percentages of missing values, the missing values were imputed with the median.
- The target feature `'num'` was transformed from multi-class (0, 1, 2, 3, 4) to a binary class (0, 1), indicating the presence or absence of heart disease.
- Outliers were detected using z-scores, visualized with box plots, and irrelevant outliers were removed based on medical context.
- Two columns were dropped as they did not contribute to predictive power.
- Data were scaled using StandardScaler and encoded using One-Hot Encoding.
- Feature selection was based on the correlation matrix.
- The dataset was split into training and testing sets with an 80-20 ratio.

### **License**: Data files © Original Authors

### **Acknowledgment**:
The following investigators are acknowledged for their role in data collection:
- Hungarian Institute of Cardiology, Budapest: Andras Janosi, M.D.
- University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
- University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D.

## **The Three Chosen Models**
1. Logistic Regression
2. Random Forest Classifier
3. Support Vector Machine (SVM)

## **Included Tasks in this Project**

### 1. Data Preprocessing:
- Handling Missing Values
- Outlier Detection
- Data Encoding
- Feature Selection
- Train-Test Split
- Feature Scaling

### 2. Model Development and Evaluation:
- Model Implementation
- Model Training
- Making Predictions
- Model Evaluation using Classification Reports

### 3. Model Optimization:
- Hyperparameter tuning using GridSearchCV
- Cross-validation to ensure generalization
- Model Performance Evaluation (Accuracy, Confusion Matrix, Classification Reports)
- Model Comparison and Selection of the Best-Performing Model

## **Best Model Selection - SVM model**

### **Prediction Accuracy:**
- The SVM model achieved the highest test accuracy of 85%, indicating strong generalization.
- The Random Forest model achieved 84% accuracy, with slight performance variations across validation folds.
- The Logistic Regression model had 83% accuracy but was outperformed by the other models.

### **Confusion Matrices Analysis:**
- **Logistic Regression**: Moderate misclassifications but stable results.
- **Random Forest**: High recall for class 1 but some misclassification in class 0.
- **SVM**: Best balance between precision and recall.

### **Test Accuracy Higher Than Training Accuracy:**
- The SVM model exhibits a higher test accuracy (85%) compared to its training accuracy (82%), suggesting that it is not overfitting and generalizes well to unseen data.

### **Precision-Recall Curves:**
- The SVM model demonstrated a strong balance between precision and recall, further supporting its selection as the best-performing model.
