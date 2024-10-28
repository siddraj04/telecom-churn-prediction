
Telecom Customer Churn Prediction Project
Overview
This project aims to predict churn among high-value customers for a telecom company, using data from the three months preceding churn. By identifying potential churners, the company can take proactive steps to retain customers through targeted interventions.

Business Objective
Goal: Predict customer churn in the fourth month (September) based on customer behavior data from the previous three months (June–August).
Importance: Reducing churn among high-value customers increases revenue stability and customer satisfaction, providing a competitive advantage.
Data
The dataset contains customer usage data across four months, including information on call volumes, recharge amounts, and data usage.

Data Phases
Good Phase: First two months (June and July), indicating regular customer behavior.
Action Phase: Third month (August), where customers may start exhibiting signs of churn.
Churn Phase: Fourth month (September), where churn is defined based on lack of customer activity.
Key Steps
Data Preparation

Filtered high-value customers (top 30% based on recharge in the first two months).
Tagged churners based on activity in the churn phase.
Removed columns specific to the churn phase for unbiased modeling.
Exploratory Data Analysis (EDA)

Analyzed churn rates and recharge patterns.
Identified features most correlated with churn to inform model building.
Modeling

Built a logistic regression model to predict churn, accounting for class imbalance.
Evaluated the model using accuracy, F1-score, and AUC-ROC metrics.
Feature Importance and Recommendations

Key predictors such as recharge amount and call volume were identified.
Developed actionable recommendations for retention strategies based on the analysis.
