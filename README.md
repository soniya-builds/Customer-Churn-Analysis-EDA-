# Exploratory Data Analysis (EDA) – Customer Churn Analysis

## Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a customer churn dataset to understand customer behavior, identify churn patterns, and uncover factors that influence customer attrition.

## Dataset Description
The dataset contains customer demographic details, service subscriptions, and churn information.  
The main feature groups include:
- Customer services (PhoneService, InternetService, StreamingTV, StreamingMovies)
- Add-on services (OnlineSecurity, OnlineBackup, TechSupport, DeviceProtection)
- Contract and billing-related attributes  
- Target variable: **Churn** (Yes / No)

## Objective of EDA
- Understand the structure and distribution of the data  
- Identify missing values and data quality issues  
- Explore relationships between customer services and churn  
- Detect trends and patterns affecting customer retention  

## Steps Performed
1. Data loading and initial inspection  
2. Data type validation and summary statistics  
3. Missing value analysis  
4. Univariate analysis of numerical and categorical variables  
5. Bivariate analysis with churn as the target variable  
6. Visualization using countplots, bar charts, and subplots  
7. Interpretation of churn-related patterns  

## Key Insights
- Customers without add-on services such as OnlineSecurity, TechSupport, OnlineBackup, and DeviceProtection show higher churn.  
- Fiber optic internet users churn more than DSL users, while customers with no internet service churn the least.  
- Streaming services have a weaker impact on churn compared to security and support services.  
- Bundled services and longer commitments improve customer retention.  

## Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Output
The EDA results provide insights useful for:
- Feature selection  
- Business decision-making  
- Building predictive churn models  

## Next Steps
- Feature engineering  
- Handling class imbalance  
- Model building and evaluation  


