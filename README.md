# Project Name - Lending Club Case Study
> Lending Club company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. In this project we need to identify risky loan applicants, thereby to cut down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Table of Contents
* [General Information](#general-information)
* [Steps Performed] (#steps-performed)
* [Recommendations](#recommendations)
* [Libraries Used](#libraries-used)



## General Information
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank's decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.


## Steps Performed
1. Data understanding
2. Data cleaning 
3. Data Analysis - Univariate and Bivariate

## Recommendations
There is more probability of defaulting when:
      1. Interest rate beyond certain threshold for specific income category
         Ex- Income greater than 1L if interest rate is above 15
      2. Loan amount sanctioned should not be more than a threshold for specific annual income category
         Ex - For income greater than 1L, loan amount of 15K is fully paid but loan amount of 20K is charged off
      3. Applicants having dti ratio between 18-24
      4. Applicants having grade with B and C
      5.Applicants taking loan for 60-month terms
      6. Applicants having home_ownership status with rent and mortgage



## Libraries Used
- pandas
- plotly 
- matplotlib 
- seaborn



## Contact
Created by AparnaBindage, KajalKankariya - feel free to contact me!

