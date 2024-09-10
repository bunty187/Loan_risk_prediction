# Loan Risk Prediction

This project focuses on predicting loan default risk using various machine learning models. The data undergoes preprocessing, univariate and bivariate analysis, followed by model training using different imputation techniques. The goal is to accurately classify loan default risk, achieving high performance with several models.
The project is designed to predict whether a customer will default on a loan. We apply several machine learning models and preprocessing techniques to handle missing data and features. The top-performing model is the CatBoost Classifier with a Simple Imputer (constant) method, achieving a final accuracy of 96.17% and an F1 score of 89.29%.


## Exploratory Data Analysis (EDA)
We conduct univariate and bivariate analysis to understand the distribution and relationships within the data.

Univariate Analysis:
* **Distribution of Features**: We analyze individual feature distributions to understand the data's structure.
* **Outliers**: Violin plots are used to identify potential outliers in the data.

Bivariate Analysis:
* **Correlation Analysis**: Heatmaps are generated to identify correlations between features and the target variable.
* **Target vs Feature Relationships**: We use scatter plots and bar charts to analyze the relationships between features and the target variable (loan default risk).

## Best Model Performance
The best-performing model in this project is the CatBoost Classifier using the Simple Imputer (constant) method.

* Accuracy: 96.17%
* F1 Score: 89.29%
