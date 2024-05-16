# Home Credit Risk Analysis
# Overview
This project, created by a team of 2, conducts an audit on the Home Credit Risk Automated Decision System (ADS), which is designed to predict loan repayment difficulties based on a Home Credit Default Risk dataset from a Kaggle competition. 
The goal is to enhance financial inclusion by identifying potential biases and ensuring fairness in the ADS used to evaluate subpopulations. 

# Objectives
- Evaluate ADS Performance: Analyze the predictive accuracy of the ADS in identifying loan repayment difficulties.
- Assess Fairness: Examine the fairness of the ADS across different demographic groups to ensure equitable decision-making.
- Identify Biases: Detect and quantify any biases in the ADS to suggest potential improvements.

# Audit Methods
- Data Analysis: Examine input data quality, including missing values and distribution of protected features.
- Model Evaluation: Implementation and comparison of logistic regression and random forest models.
- Fairness Analysis: Detailed analysis of model predictions across different demographic subgroups using AUC/ROC curves and fairness metrics such as demographic parity and selection rates.
- Explainability Analysis: Utilization of SHAP values to understand which features most significantly impact the ADS predictions, indicating areas of potential bias.

# Key Findings
Model Performance: 
- Models show moderate predictive power but, random forest model was more accurate overall
- Subgroups show differences in performance, which suggests potential biases

Demographic Disparities:
- Analysis reveals disparities in model predictions across different demographics, highlighting areas for improvement in model fairness.
- Certain family statuses had accuracy and selection rates higher than the rest (e.g. higher chance of selecting widows)

SHAP Analysis:
- Significant features include external credit scores and demographic details, pointing to sensitive features that may influence fairness.

# References
[Home Credit Default Risk Kaggle Competition](https://www.kaggle.com/competitions/home-credit-default-risk)  
	[Solution to Audit on](https://www.kaggle.com/code/willkoehrsen/start-here-a-gentle-introduction)
