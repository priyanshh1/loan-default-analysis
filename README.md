# loan-default-analysis

# Loan Default Prediction

## Overview
Predicting loan defaults is crucial for financial risk assessment and lending decisions. This involves collecting historical loan data, preprocessing it (handling missing values, encoding categorical variables, and selecting relevant features), and training machine learning models such as XGBoost and Random Forest. The model’s performance is evaluated using metrics like accuracy, precision, recall, and AUC.

## Key Learning Outcomes
- Understand the significance of loan default prediction in financial risk assessment.
- Learn essential data preprocessing techniques, including handling missing values and encoding categorical variables.
- Apply machine learning algorithms (XGBoost, Random Forest) for prediction.
- Evaluate model performance using classification metrics like accuracy, precision, recall, and F1-score.

## Steps in Loan Default Prediction

### 1. Understanding the Dataset
- The dataset consists of 252,000 records with 13 features, including demographic details and a target variable (Risk_Flag).
- Numerical and categorical features are analyzed separately.
- No missing values are present in the dataset.

### 2. Exploratory Data Analysis (EDA)
- Histograms and box plots are used to analyze data distributions.
- Correlation heatmaps help identify relationships between features.
- Categorical data (e.g., marital status, house ownership, profession) is analyzed using count plots.

### 3. Data Preprocessing
- Categorical features are encoded using Label Encoding, One-Hot Encoding, and Count Encoding.
- High-cardinality features like Profession, CITY, and STATE are transformed.

### 4. Train-Test Split
- The dataset is split into 80% training and 20% testing using stratified sampling to maintain class balance.

### 5. Model Training: Random Forest
- Random Forest Classifier is chosen for its robustness in handling classification tasks.
- SMOTE (Synthetic Minority Over-sampling Technique) is used to balance class distribution.
- The trained model is evaluated on unseen test data.

## Conclusion
Using machine learning techniques like Random Forest and XGBoost, lenders can identify high-risk borrowers, optimize lending decisions, and minimize defaults. Proper data preprocessing and evaluation ensure reliable predictions, helping financial institutions enhance risk management strategies.
