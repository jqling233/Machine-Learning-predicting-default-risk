# DNSC 6290 Machine Learning Project
## Home Credit Default Risk
### Background
This project is a Kagge competition raised by Home Credit, a financial institution strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. In this Kaggle cempetition, Home Credit provides a variety of alternative data--including telco and transactional information--to predict their clients' repayment abilities.
Detailed information could be found at: https://www.kaggle.com/c/home-credit-default-risk/overview

### Table of Content
1. Import and Check datasets
2. Data Explortary Analysis
3. Data Transformation
4. Feature Selection
5. Modeling and Evaluation

### Summary
1. This document shows how our group performed data cleaning, encoding, transformation, joining to get a combined training set from mulitple data sources.
2. Correlation, data quality and feature importance are considered in the feature selection process. Only 161 out of 746 variables are required for 0.90 of cumulative importance.
3. Finally, our group implemented LightGBM algorithm and developed an classfication model with a nearly 0.80 AUC.
