# Credit EDA & Credit Score Calculation with Python

## Overview
This project focuses on analyzing a financial dataset to understand customer credit behavior and calculate a hypothetical credit score based on various financial factors. The analysis uses Python to perform Exploratory Data Analysis (EDA), feature engineering, and build a model to calculate a credit score.

### The study includes:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Credit Score Calculation
- Business Recommendations

## Project Scope
The goal of this project is to:

- Perform an in-depth analysis of customer credit data to uncover patterns in credit behavior.
- Engineer features that are predictive of creditworthiness.
- Calculate a hypothetical credit score for each customer based on financial details.
- Provide actionable insights for financial institutions to optimize credit scoring models.

## Dataset Overview
The dataset used in this study contains the following columns:

- **customer_id**: Unique identifier for each customer
- **age**: Age of the customer
- **gender**: Gender of the customer
- **income**: Monthly income of the customer (USD)
- **loan_amount**: Total loan amount requested
- **loan_term**: Term of the loan in months
- **credit_history**: Historical credit data (e.g., number of late payments, credit utilization)
- **employment_status**: Employment status (employed, self-employed, unemployed)
- **current_balance**: Current balance on loans
- **credit_score**: Actual credit score (used as a reference for calculating new scores)

## Methods and Techniques

### Exploratory Data Analysis (EDA)
The dataset was explored to understand key features and patterns, including:

- Distribution of customer income, loan amounts, and credit scores.
- Correlation analysis between financial variables such as income, loan amount, and credit history.
- Identification of outliers and missing values in key features.
- Distribution of credit scores and factors influencing them.

### Feature Engineering
New features were created to help predict credit scores more accurately:

- **Debt-to-Income Ratio (DTI)**: Ratio of total debt to monthly income.
- **Credit Utilization**: Ratio of credit balance to total available credit.
- **Credit History Score**: Aggregate score based on past payment behaviors.

### Credit Score Calculation
A hypothetical credit score was calculated using a weighted formula considering factors such as income, debt, loan amount, and credit history. This credit score can be used by financial institutions to assess customer creditworthiness.

## Key Findings
- **Income vs. Credit Score**: Higher income is generally associated with a better credit score.
- **Debt-to-Income Ratio**: A higher DTI ratio correlates with lower credit scores.
- **Credit History Impact**: A positive credit history (e.g., fewer late payments) is a strong indicator of a higher credit score.

## Strategic Business Recommendations
Based on the findings, several strategic recommendations for financial institutions:

- **Optimize Lending Decisions**: Use the derived credit score for better decision-making on loan approvals.
- **Personalized Financial Products**: Tailor financial products such as loans or credit cards based on credit score and customer profile.
- **Monitor Credit Utilization**: Focus on customers with high credit utilization as they may be at risk of default.
- **Improve Credit History Tracking**: Provide tools to customers to improve their credit history and, in turn, their credit scores.

## Project Structure
```
├── data
│     └── credit_score.csv                           # The dataset used in the analysis
├── notebooks
│     └── credit-eda-and-scoring.ipynb # Jupyter notebook containing the EDA, feature engineering, and credit score calculation
├── README.md                                       # Project documentation
```


## Results and Insights
- **Credit Behavior**: The analysis confirmed that income, credit history, and debt-to-income ratio are key determinants of credit score.
- **Feature Importance**: Credit history and debt-to-income ratio have the highest impact on the credit score calculation.

## Conclusion
This study provides actionable insights into customer credit behavior, offering financial institutions a better understanding of their customer base. By leveraging the credit score model, institutions can optimize lending decisions, improve risk assessment, and create tailored financial products for their clients.



