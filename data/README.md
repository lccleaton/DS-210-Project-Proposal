# Data Dictionary

## bank_churn_clean.csv

The ‘Bank Customer Churn’ dataset provides the account information of 10,000 customers at a European bank. Each row represents a customer’s account at the unnamed European bank, and there are 13 columns:
10,000 rows by 13 columns

| Variable         | Type        | Description                                                                 |
|-----------------|------------|-----------------------------------------------------------------------------|
| CustomerId       | Numeric     | ID number of the customer                                                   |
| Surname          | Character   | Customer’s last name                                                        |
| CreditScore      | Numeric     | Customer’s credit score                                                     |
| Geography        | Factor      | Country that customer lives in (France, Spain, or Germany)                  |
| Gender           | Factor      | Customer’s sex (Male or Female)                                            |
| Age              | Numeric     | Customer’s age                                                             |
| Tenure           | Numeric     | Number of years customer has been with the bank                             |
| Balance          | Numeric     | Customer’s account balance (in €)                                          |
| NumOfProducts    | Numeric     | Number of products from the bank that the customer owns (credit card, debit card, etc.) |
| HasCrCard        | Factor      | Does the customer have a credit card with the bank: Yes or No?             |
| IsActiveMember   | Factor      | Is the customer an active member of the bank: Yes or No?                   |
| EstimatedSalary  | Numeric     | Customer’s estimated salary (in €)                                         |
| Exited           | Factor      | Did the customer close account with the bank: Yes or No?                    |

**Source:** [Maven Analytics' Data Playground](https://mavenanalytics.io/data-playground/bank-customer-churn?page=7&pageSize=5)