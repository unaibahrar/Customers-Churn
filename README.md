Customers-Churn
Project

Exploratory Data Analysis (EDA) & Feature Engineering
Overview
This project focuses on Exploratory Data Analysis (EDA) and Feature Engineering for a predictive modeling task. The goal is to understand the dataset, identify patterns, and create meaningful features to improve the performance of a machine learning model.

Tasks & Analysis
1. Exploratory Data Analysis (EDA)
Data Cleaning: Handled missing values, outliers, and inconsistencies.
Data Distributions: Analyzed skewness and distribution of key variables.
Feature Correlations: Identified relationships between variables and their influence on the target.
Key Insights:
Some numerical features were highly skewed and required transformations.
Certain categorical variables had low variance and were dropped.
Features such as tenure and pricing trends showed potential predictive power.
2. Feature Engineering
Transformation of Date Features: Converted dates into meaningful numerical values.
Price Change Analysis: Created features analyzing price fluctuations over time.
Categorical Encoding: Applied label encoding and one-hot encoding where necessary.
Skewness Treatment: Applied log transformation for highly skewed numerical features.
Feature Selection: Removed redundant or highly correlated features to improve model efficiency.
3. Model Training & Evaluation
Implemented a Random Forest Classifier for churn prediction.
Train-Test Split: 75%-25% split for model training and validation.
Performance Metrics:
Accuracy: High but misleading due to class imbalance.
Precision & Recall: The model struggled with recall, missing many true churn cases.
Feature Importance: Tenure, pricing, and contract renewal showed high predictive influence.
Conclusion & Next Steps
Key Takeaways
The dataset required significant preprocessing due to missing values, skewness, and categorical variables.
Price sensitivity was a weak predictor of churn, while contract renewal and tenure were stronger indicators.
The model needs further improvements, especially in handling class imbalance and recall.
Action Items
Improve Feature Engineering: Create more predictive features related to customer behavior.
Optimize Model Parameters: Experiment with hyperparameter tuning.
Balance the Dataset: Use SMOTE or class weighting to improve recall.
Try Alternative Models: Consider boosting algorithms like XGBoost or LightGBM.
