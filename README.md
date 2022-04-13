# Bank Customer Churn Prediction
This project compares the performance of three supervised classification techniques to suggest an efficient model to predict customer churn in banking industry

## Objective
1. Design and implement a data pipeline for pre-processing the raw dataset. 
2. Compare the performance of two supervised regression techniques to suggest an efficient model for predicting the price

## Dataset overview
**Dataset:** [Link](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers) 

**Summary:** This dataset comprises of bank customers and their behavior. It is an advantageous dataset for banks to know what leads a client towards the decision to leave the bank. Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.

**Problem:** Predict which customer can leave the bank

**Describe:** Dataset has 10000 rows and 14 columns (features) as described below:
+ RowNumber: Corresponds to the record (row) number and has no effect on the output.
+ CustomerId: Contains random values and has no effect on customer leaving the bank.
+ Surname: The surname of a customer has no impact on their decision to leave the bank.
+ CreditScore: Can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
+ Geography: A customer’s location can affect their decision to leave the bank.
+ Gender: Tt’s interesting to explore whether gender plays a role in a customer leaving the bank.
+ Age: This is certainly relevant, since older customers are less likely to leave their bank than younger ones.
+ Tenure: Refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
+ Balance: Also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
+ NumOfProducts: Refers to the number of products that a customer has purchased through the bank.
+ HasCrCard: Denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
+ IsActiveMember: Active customers are less likely to leave the bank.
+ EstimatedSalary: As with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
+ Exited: Whether or not the customer left the bank.

## Technologies
**Language:** Python

**Framework/Libary:** Python, Pandas, Numpy, Scikit-Learn

**Machine Learning Algorithms:** Logistic Regression, Decision Trees, XGBoost (Extreme Gradient Boosting)

**Metrics:** Accuracy, F1-score, Precison, Recall
## Contact
Author: Nguyen Hoang Long

Facebook: https://www.facebook.com/umhummmm/

Email: nghoanglong.17december@gmail.com
