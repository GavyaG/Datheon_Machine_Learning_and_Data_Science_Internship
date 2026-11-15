# Task 3: Predictive Customer Churn Classifier

### Random Forest & XGBoost

## 1. Project Overview

Customer churn occurs when customers stop using a company's products or services. Predicting customer churn helps businesses identify customers who are likely to leave and take preventive measures to improve customer retention.

This project develops a machine learning-based customer churn prediction system using the Telco Customer Churn dataset. Two classification algorithms, Random Forest and XGBoost, are implemented and evaluated to identify the better-performing model.

## 2. Dataset Information

**Dataset:** Telco Customer Churn

- Total Records: 7,043
- Total Features: 20 (after removing customerID)
- Target Variable: Churn
- Target Classes: Yes and No

The dataset contains customer information, subscription details, service usage, contract types, payment methods, and churn status.

## 3. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

## 4. Project Workflow

### Step 1: Data Loading
Loaded the Telco Customer Churn dataset using Pandas.

### Step 2: Data Cleaning
- Checked missing values and duplicate records.
- Converted TotalCharges into numeric format.
- Imputed 11 missing values using median.
- Removed the unnecessary customerID column.

### Step 3: Exploratory Data Analysis
Analyzed customer churn distribution using count plots and percentage calculations.

### Step 4: Data Splitting
Separated input features and target variable.
Split the dataset into 80% training data and 20% testing data using stratified sampling.

### Step 5: One-Hot Encoding
Converted categorical variables into numerical representations using OneHotEncoder.

### Step 6: Class Imbalance Handling
Applied SMOTE to balance the training dataset.

- Before SMOTE: 4,139 No Churn and 1,495 Churn.
- After SMOTE: 4,139 No Churn and 4,139 Churn.

### Step 7: Model Training
Trained two machine learning classifiers:

- Random Forest Classifier
- XGBoost Classifier

### Step 8: Model Evaluation
Evaluated both models using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

### Step 9: Performance Visualization
Generated:
- ROC-AUC Curve
- Confusion Matrix
- Top 10 Feature Importance Charts

### Step 10: Cross-Validation
Applied 5-Fold Stratified Cross-Validation to evaluate model performance and consistency.

## 5. Model Performance Comparison

| Evaluation Metric | Random Forest | XGBoost |
|---|---:|---:|
| Accuracy | 78.57% | 79.49% |
| Precision | 60.00% | 62.46% |
| Recall | 57.75% | 56.95% |
| F1-Score | 58.86% | 59.58% |
| ROC-AUC | 83.26% | 84.33% |

## 6. Best Performing Model

**XGBoost Classifier**

XGBoost achieved the best overall performance with:

- Accuracy: 79.49%
- Precision: 62.46%
- Recall: 56.95%
- F1-Score: 59.58%
- ROC-AUC: 84.33%

The model achieved an ROC-AUC score above the target of 80%.

## 7. Key Learning Outcomes

- Understanding customer churn prediction.
- Performing data preprocessing and cleaning.
- Handling missing values.
- Applying One-Hot Encoding.
- Managing imbalanced datasets using SMOTE.
- Implementing Random Forest and XGBoost.
- Evaluating classification models.
- Performing cross-validation.
- Visualizing feature importance and model performance.

## 8. Project Files

- `Task_3_Customer_Churn_Classifier.ipynb` – Complete Jupyter Notebook.
- `Telco-Customer-Churn.csv` – Dataset used for model development.

## 9. Conclusion

The project successfully developed and evaluated two machine learning classification models for predicting customer churn.

Among the two models, XGBoost achieved the highest ROC-AUC score of 84.33%, outperforming Random Forest in overall evaluation metrics.

This project demonstrates how machine learning techniques can help businesses identify customers at risk of leaving and support effective customer retention strategies.

## 10. Author

**Gavya G**

B.Tech – Artificial Intelligence and Data Science

2024–2028
