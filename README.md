# Loan-Prediction
**Project Overview**

The Loan Approval Prediction project aims to develop a predictive model that estimates the probability of a loan application being approved or rejected. The project utilizes historical loan application data to train a logistic regression model, which can then score new applications. This model aids financial institutions in making informed decisions regarding loan approvals.

**Components and Workflow**
1. Data Collection and Preparation - Data was collected from Kaggle Datasets

    Dataset: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset
   
2. Model Development

3. Prediction and Results Display

# **Data Collection and Preparation**

The data consists of historical loan application records, including various features that might influence the loan approval decision such as:

**GENDER**: Gender of the applicant

**MARITAL_STATUS**: Marital status

**FAMILY_MEMBERS**: Number of family members

**QUALIFICATION**: Educational qualifications

**EMPLOYMENT**: Employment status

**LOAN_HISTORY**: Past loan history

**LOAN_LOCATION**: Location of the loan application

**CANDIDATE_INCOME**: Income of the loan applicant

**GUARANTEE_INCOME**: Income of the guarantor (if any)

**LOAN_AMOUNT**: Amount of the loan applied for

**LOAN_DURATION**: Duration of the loan

This data is cleaned and preprocessed to ensure consistency and handle missing values. The dataset is then split into training and testing sets.

# **Model Development**

The model is developed using SAS, a powerful software suite used for advanced analytics, multivariate analysis, business intelligence, and data management. The logistic regression model is chosen for this task due to its suitability for binary classification problems (e.g., approved vs. not approved).

Here is a snippet of the SAS code used to train the logistic regression model:
![image](https://github.com/nmirpuri/Loan-Prediction/assets/171285926/72c9e1f7-6e10-4f25-848c-1f30eeabf188)

# **Prediction and Results Display**
**Screenshot of the Output:**

![image](https://github.com/nmirpuri/Loan-Prediction/assets/171285926/73331d2f-6924-4062-9d58-f56f0b354297)

**Understanding the Results**

The columns created in this project are P_N and P_Y. These correspond to the probability of the loan being rejected (P_N) and the loan being approved (P_Y). When analyzing the results, it was found that loans with a probability of 80% or higher of being approved generally receive a Yes, while those with a probability of 20% or lower generally get rejected. There are outliers that exist within the predictive model. 

# **Summary**
This project integrates data analytics and statistical modeling to provide a robust solution for predicting loan approvals. By leveraging SAS for model development and prediction, the project ensures accurate predictions and insightful analysis.

**Tools and Technologies**.

**SAS:** For data manipulation, statistical modeling, and prediction.

**SQL:** For table and data storage and processing

By following this structured approach, the project achieves a seamless integration of predictive modeling with accurate and insightful loan approval probability predictions.

