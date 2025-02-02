# CustomerChurnAnalysis
This repository implements a Customer Churn Prediction System for ConnectTel, addressing churn's impact on business growth. Using machine learning, it identifies at-risk customers, enabling targeted retention. It includes EDA, feature engineering, model training, evaluation, and documentation to enhance retention, loyalty, and profitability.

# Project Objectives
The key objectives of this project are:  
Identify At-Risk Customers: Predict customers likely to churn based on historical data.  
Improve Customer Retention: Implement proactive, personalised interventions to reduce churn.  
Optimise Marketing Spend: Target resources effectively for maximum return on investment.  
Gain Insights into Churn Drivers: Understand factors influencing customer churn to improve services.  
Enhance Long-Term Loyalty: Strengthen customer relationships to sustain business growth.  

# Dataset Description
The dataset includes the following key attributes:  
Demographics: Gender, Senior Citizen, Partner, Dependents.  
Service Details: Phone Service, Multiple Lines, Internet Service, Online Security, etc.  
Account Information: Tenure, Contract Type, Payment Method, Monthly Charges, Total Charges.  
Target Variable: Churn status indicating if a customer has left or stayed.  

# Exploratory Data Analysis (EDA)
Key findings from the EDA:  
Customers with month-to-month contracts have significantly higher churn rates.  
Senior citizens and customers with high monthly charges are more likely to churn.  
Retention improves as customer tenure increases, highlighting the importance of engaging new customers early.  
Lack of add-on services, such as online security and device protection, is linked to higher churn.  

# Feature Engineering  
Created tenure groups to categorise customers by their duration with ConnectTel.  
Dropped irrelevant or multicollinear features, such as CustomerID and Tenure.  
Categorical variables were encoded, and synthetic samples were generated using SMOTEENN for class balance.  

# Machine Learning Models  
  The following models were tested:  
Logistic Regression  
Decision Tree  
Random Forest  
SGDClassifier  
XGBClassifier  

# Recommendations, Based on insights from the analysis:  
Develop Targeted Retention Strategies: Focus on at-risk customers based on model predictions.  
Improve Service Offerings: Address issues like lack of add-ons and high monthly charges.  
Optimise Marketing Spend: Allocate resources to retention efforts with the highest impact.  
Continuous Monitoring: Regularly evaluate and update the model to maintain effectiveness.  

# Conclusion  
This project provides a robust, data-driven solution for mitigating customer churn at ConnectTel. It combines advanced analytics and machine learning to offer actionable insights and effective strategies for improving customer retention and strengthening ConnectTel's market position.
