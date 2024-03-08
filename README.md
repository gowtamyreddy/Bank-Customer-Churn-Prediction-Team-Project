# Bank Customer Churn Prediction

## Team Members

- Casey Gilliam - cgilli10@students.kennesaw.edu
- Rohini Paithanker - rpaithan@students.kennesaw.edu
- Gowtamy Reddy Godhala - ggodhala@students.kennesaw.edu
- Tomas King - tking109@students.kennesaw.edu

## Project Overview

This project aims to develop a predictive model to forecast bank customer churn. We use a dataset from a U.S. bank, available on Kaggle, containing information about customers' likelihood of leaving the bank. The model will help the bank implement focused retention strategies to retain its client base.

## Dataset

The dataset comprises 10,000 rows and 13 columns, with the following attributes:

- CustomerId: An ID for each customer.
- Surname: Last name of the customer.
- CreditScore: Credit score of the customer.
- Geography: Customer's geographical location.
- Gender: Gender of the customer.
- Age: Age of the customer.
- Tenure: Number of years the customer has been with the bank.
- Balance: Account balance of the customer.
- NumOfProducts: Number of products the customer uses.
- HasCrCard: Indicates whether the customer has a credit card or not.
- IsActiveMember: Indicates whether the customer is an active member.
- EstimatedSalary: Estimated salary of the customer.
- Exited: Target variable indicating whether the customer has churned the bank or not.

## Objectives

The primary goal is to create a classification model that predicts whether a customer will churn (leave the bank) based on the given attributes. The target variable is "Exited," and the model will focus on identifying key factors influencing customer churn.

## Hypotheses

1. Customer engagement measures such as "IsActiveMember" and "NumOfProducts" are key indicators of customer churn. Less active customers may be more prone to churn.
2. Tenure is a significant factor in churn prediction. Long-term clients might be less likely to churn, whereas newer clients might be more susceptible to leaving the bank.

## Usage

Details on how to run and use the model will be provided here, including any required dependencies, installation instructions, and example usage.

## Results

The predictive model for bank customer churn has shown promising results. After training and testing on the dataset, the model achieved an accuracy of approximately 85%, indicating a strong ability to predict customer churn based on the given attributes. Key predictors of churn identified by the model include IsActiveMember, NumOfProducts, Age, and Balance. These factors align with our initial hypotheses, suggesting that customer engagement and financial stability are crucial in determining the likelihood of churn.

## Conclusion
 This project highlights the effectiveness of the predictive model in identifying potential churners among bank customers. By leveraging key indicators such as customer activity and financial metrics, the bank can implement targeted retention strategies to prevent customer churn. Future work could involve refining the model with additional data, exploring alternative algorithms, and integrating the model into the bank's customer relationship management system for real-time churn prediction.







