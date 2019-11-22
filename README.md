# Loan Prediction

The loan prediction problem I am tackling here comes from the competition powered by Analytics Vidhya at https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/

This work is inspired by the tutorial [here](https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/).
## Problem Statement
### About Company
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.

### Problem
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

## Data
Variable | Description
----------|-------------
Loan_ID | Unique Loan ID
Gender | Male/Female
Married | Applicant married (Y/N)
Dependents | Number of dependents
Education | Applicant Education (Graduate/Under Graduate)
Self_Employed | Self employed (Y/N)
ApplicantIncome | Applicant Income
CoapplicantIncome | Coapplicant income
LoanAmount | Loan amount in thousands
Loan\_Amount\_Term | Term of loan in months
Credit_History | credit history meets guidelines
Property_Area | Urban/Semi Urban/Rural
Loan_Status | Loan approved (Y/N)

**Note**:
1. Evaluation Metric is accuracy i.e. percentage of loan approval you correctly predict
2. You are expected to upload the solution in the format of "sample_submission.csv"
