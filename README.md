# Credit-Card-Recommender-System

A machine learning project designed to recommend the most suitable type of credit card for clients based on their personal and financial details. This project leverages various ml algorithms to analyze data and predict the best card option, aiming to enhance customer satisfaction and streamline the card issuance process for financial institutions.

## Overview

Credit cards are a good source of income for banks because of different kinds of fees charged by the banks like annual fees, balance transfer fees, and cash advance fees, late payment fees, foreign transaction fees, and others. Some fees are charged to every user irrespective of usage, while others are charged under specified circumstances.
The bank offers various different credit cards to its clients and wants us to analyze its customer data to identify which will be the best suitable card for its future customer based on its clients usage. This will help the bank to automate the card issuance process and also avoid risk of credit defaults, operational Costs, misalignment of rewards, regulatory Sanctions, etc.

As a Data scientist, we need to come up with a classification model that will help the bank improve its services.

### Objective:
- Explore and visualize the dataset
- Build a multi-class classification model to predict what is the best suitable card for the client based on the given information
- Optimize the model using appropriate techniques

### Data Overview: 

- CLIENTNUM : Unique identifier for the customer holding the account
- Attrition_Flag : Internal event (customer activity) variable - if the account is closed then "Attrited Customer" else "Existing Customer"
- Customer_Age : Age in Years
- Gender : Gender of the account holder
- Dependent_count : Number of dependents
- Education_Level : Educational Qualification of the account holder - Graduate, High School, Unknown, Uneducated, College(refers to a college student), Post-Graduate, Doctorate.
- Marital_Status : Marital Status of the account holder
- Income_Category : Annual Income Category of the account holder
- Card_Category : Type of Card
- Months_on_book : Period of relationship with the bank
- Total_Relationship_Count : Total no. of products held by the customer
- Months_Inactive_12_mon : No. of months inactive in the last 12 months
- Contacts_Count_12_mon : No. of Contacts between the customer and bank in the last 12 months
- Credit_Limit : Credit Limit on the Credit Card
- Total_Revolving_Bal : The balance that carries over from one month to the next is the revolving balance
- Avg_Open_To_Buy : Open to Buy refers to the amount left on the credit card to use (Average of last 12 months)
- Total_Trans_Amt : Total Transaction Amount (Last 12 months)
- Total_Trans_Ct : Total Transaction Count (Last 12 months)
- Total_Ct_Chng_Q4_Q1 : Ratio of the total transaction count in 4th quarter and the total transaction count in 1st quarter
- Total_Amt_Chng_Q4_Q1 : Ratio of the total transaction amount in 4th quarter and the total transaction amount in 1st quarter
- Avg_Utilization_Ratio : Represents how much of the available credit the customer spent

## Installation

Clone Repository
```
git clone https://github.com/Vikram-Git/React-Django-Todo
cd 'todo_backend'
```
Install Requirements
```
pip install -r requirements.txt
```
Open the jupyter notebook on your computer 
