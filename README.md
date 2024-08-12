# **📃Business Case: <font color=#9F2B68>LoanTap💸</font> - Logistic Regression**📈

<img src="https://pimwp.s3.ap-south-1.amazonaws.com/2024/04/Untitled-design-94-4-jpg.webp">


## **Content**
- **1) About LoanTap**
- **2) Problem Statement**
- **3) Objective**
- **4) Concept Used**
- **5) Libraries**
- **6) Exploring the data**
- **7) Observations on Data**
- **8) Exploratory data analysis**
    - 8.1) Univariate Analysis
    - 8.2) Bivariate Analysis
- **9) Data preprocessing**
    - 9.1) Check for Duplicate
    - 9.2) Missing value treatment
    - 9.3) Outlier detection
        - 9.3.1) Visualization Method
        - 9.3.2) Five point summery and percentage of outliers
        - 9.3.3) IQR Method
        - 9.3.4) Setting a threshold
        - 9.3.5) Outlier Treatment - Quantile-Based Capping
    - 9.4) Feature engineering
        - 9.4.1) Dealing with pub_rec and pub_rec_bankruptcies columns
        - 9.4.2) Dealing with issue_d and earliest_cr_line columns
        - 9.4.3) Dealing with address column
    - 9.5) Encoding
        - 9.5.1) Plan for Encoding
        - 9.5.2) One Hot Encoding  
        - 9.5.3) Label Encoding
    - 9.6) Train-Validation-Test-Split
    - 9.7) Feature scaling
- **10) Model Building**
    - 10.1) Choosing the classification Metrix
    - 10.2) Checking about data imbalance
    - 10.3) Base Model - Logistic Regression
        - 10.3.1) PR Curve Base Model
    - 10.4) Handling Imbalance Data - Class Weight
        - 10.4.1) ROC AUC curve for Class Weight Model
    - 10.5) Handling Imbalance Data - SMOTE
        - 10.5.1) ROC AUC curve for SMOTE Model
    - 10.6) Conclusion: Best Model Selection
    - 10.7) Final Check with X_test data
        - 10.7.1) Feature importance
- **11) Questionnaire**
- **12) Business Insights and Recommendations**

## **About <font color=#9F2B68>LoanTap**</font>💸

LoanTap is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.

The data science team at LoanTap is building an underwriting layer to determine the creditworthiness of MSMEs as well as individuals.

LoanTap deploys formal credit to salaried individuals and businesses 4 main financial instruments:

- Personal Loan
- EMI Free Loan
- Personal Overdraft
- Advance Salary Loan

This case study will focus on the underwriting process behind Personal Loan only

## <font color=#9F2B68>**Problem</font> Statement👀**

Given a set of attributes for an Individual, determine if a credit line should be extended to them. If so, what should the repayment terms be in business recommendations?

## **Objective🎯**

Analyze the dataset to determine the creditworthiness of potential borrowers. Our ultimate objective is to build a logistic regression model, evaluate its performance, and provide actionable insights for the underwriting process.

## **Concept Used📑**

- Exploratory Data Analysis
- Feature Engineering
- Logistic Regression
- Precision Vs Recall Tradeoff
