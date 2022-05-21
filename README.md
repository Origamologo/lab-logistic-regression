# lab-logistic-regression

## Objetive
The objetive of this project is to build a model that will provide insight into why some bank customers accept credit card offers.<br>
**Data:** The data set consists of information on 18,000 current bank customers in the study. These are the definitions of data points provided:

- Customer Number: This is a sequential number assigned to the customers (this column is hidden and excluded – this unique identifier will not be used directly).
- Offer Accepted: Did the customer accept (Yes) or reject (No) the offer. Reward: The type of reward program offered for the card.
- Mailer Type: Letter or postcard.
- Income Level: Low, Medium, or High.
- Bank Accounts Open: How many non-credit-card accounts are held by the customer.
- Overdraft Protection: Does the customer have overdraft protection on their checking account(s) (Yes or No).
- Credit Rating: Low, Medium, or High.
- Credit Cards Held: The number of credit cards held at the bank.
- Homes Owned: The number of homes owned by the customer.
- Household Size: Number of individuals in the family.
- Own Your Home: Does the customer own their home? (Yes or No).
- Average Balance: Average account balance (across all accounts over time). Q1, Q2, Q3, and Q4
- Balance: Average balance for each quarter in the last year

## Working plan
We will explore the data and create several csv files to test logistic regression models.<br>
Two data frames will be explored, one with all the information contained in the original csv properly processed for the machine learning algorithm and another one in which the columns that behaved exactly the same for Yes and have been dropped.

## Structure of the project files

1. Notebook folder:
  a) **1_main.ipynb**: explores the data and creates two csv with the outliers treated, one with all the information and another one without the columns that have been consideres irrlevant