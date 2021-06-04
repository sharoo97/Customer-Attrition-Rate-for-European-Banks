# Customer-Attrition-Rate-of-European-Banks
Visualized customer data from European banks to predict Churn rate

## Data Source
Deep Learning A-Z ANN Dataset: Bank Dataset to investigate high customer attrition rate.
Source: https://www.kaggle.com/filippoo/deep-learning-az-ann

## Objective
The aim of this project is to analyze a bank dataset and predict the factors causing the customer attrition rate. The dataset includes 14 features and 10,000 worth of data points that helped us investigate the high rate of customers leaving the bank. Attrition rate is an important KPI that  banks should track to ensure the implementation of right strategic decisions. We chose this dataset to explain the importance of customer attrition rate KPI so as to understand that retaining customers is equally important and cheaper than targeting new customers. We used different Python libraries in Anaconda to find out the contributing factors of this relatively high attrition rate in European banks and to aid other banks of the world helping them strucuture strategic decisions.

Features contributing to high customer attrition rate are as follows:

- Credit Score: Customer's current credit score.
- Geography: European country where the customer's bank account was opened.
- Gender Type: Whether the customer is Male or Female.
- Age: Customer's age.
- Tenure: Duration of a customer staying with the bank.
- Debit Balance: Debit balance available in customer's bank account.
- Number of Products: Products purchased by customers from the bank, i.e. loans, bonds,etc.
- Has Credit Card: Binary variable. Whether the customer has a credit card or not.
- IsActiveMember: Indication of customers having an active transaction with their bank account.
- Estimated Salary - The estimated salary of a customer.

## Analysis
The best predictive model acquired comprised of features like Geography, Gender, Age, Tenure, IsActiveMember and Age*IsActiveMember giving us an accuracy of 84% whether the customer would leave or stay at the bank.
