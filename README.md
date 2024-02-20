# Telco Customer Churn Analysis

## Overview
This project aims to analyze customer churn in a telecommunications company and develop predictive models to identify at-risk customers. By understanding the factors influencing churn and improving retention strategies, the goal is to reduce churn rates and enhance customer satisfaction.

## Data
The dataset used in this analysis is sourced from (https://www.kaggle.com/datasets/blastchar/telco-customer-churn?select=WA_Fn-UseC_-Telco-Customer-Churn.csv) containing 21 columns and 7043 rows.

## The columns are:
['customerID', 'gender', 'SeniorCitizen', 'Partner', 'Dependents', 'tenure', 'PhoneService', "MultipleLines', 'InternetService'. 'Online Security', 'OnlineBackup', 'Device Protection', TechSupport', 'Streaming TV". 'StreamingMovies', 'Contract', 'PaperlessBilling', 'PaymentMethod", "Monthly Charges'. "Total Charges', 'Churn']


## Objectives
1. To identify key factors driving customer churn.
2. To explore data to understand churn patterns.
3. To select relevant features for churn prediction.
4. To develop and compare machine learning models.
5. To deploy the model for real-time churn prediction.
6. To provide recommendations for improving retention strategies.

## Analysis Process
1. **Exploratory Data Analysis (EDA)**: Explored the dataset to understand churn patterns and identify key factors influencing customer churn.
2. **Feature Engineering**: Extracted relevant features from the dataset and preprocess them for model development.
3. **Model Development**: Built and compared different machine learning models for churn prediction, including logistic regression, decision trees, and random forests.
4. **Model Evaluation**: Evaluated model performance using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.
5. **Interpretation**: Interpreted the trained models to understand feature importance and derive actionable insights for the telco company.
6. 
## Results
- Key Findings from EDA:
  - Demographic factors (e.g., age, gender) have a significant impact on churn.
  - Service usage patterns (e.g., monthly charges, contract type) are strong predictors of churn.

## - Model Performance:

## Technique used for balancing the data
 - SMOTE-ENN (Synthetic Minority Over-sampling Technique with Edited Nearest Neighbors) is
   a combination of two techniques: 
     - SMOTE (for over-sampling the minority class) and 
     - ENN (Edited Nearest Neighbors, for under-sampling both classes). 
 - SMOTE-ENN is designed to address class imbalance in binary classification problems.

### - For imbalanced data:
  - Logistic Regression: Accuracy - 80%, Precision - 83%, Recall - 92%, AUC - 84%
  - Decision Tree: Accuracy - 79%, Precision - 84%, Recall - 89%, AUC - 82%
  - Random Forest: Accuracy - 78%, Precision - 80%, Recall - 94%, AUC - 84%

### - For balanced data:
  - Logistic Regression: Accuracy - 93%, Precision - 91%, Recall - 94%, AUC - 98%
  - Decision Tree: Accuracy - 93%, Precision - 94%, Recall - 92%, AUC - 96%
  - Random Forest: Accuracy - 93%, Precision - 95%, Recall - 92%, AUC - 98%

## - Business Insights:
  - Targeting high-risk customer segments for retention efforts could effectively reduce churn rates.
  - Improving service quality and offering personalized incentives to loyal customers may enhance customer satisfaction and loyalty.

## Usage
To use the trained model for predicting customer churn for the new or unseen data points. From this information we can easily identify the loyal customers quickly when a new one joins. So we can provide good service ls to those who lokely to churn to stop them from churning.


## Conclusions
This analysis provides valuable insights into customer churn behavior in the telco industry. By leveraging predictive models, the telco company can proactively identify and retain at-risk customers, ultimately improving customer satisfaction and business profitability.
