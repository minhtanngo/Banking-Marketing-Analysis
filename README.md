# Banking-Marketing-Analysis
This is Banking Marketing Analysis project for IBM Tech Demo Day

## Objective

In general, datasets which contain marketing data can be used for 2 different business goals:

- Prediction of marketing campaign results for each client, as well as explanation of factors that influence campaign outcomes. This aids in determining how to make marketing campaigns more effective.
- Identifying client categories based on data from customers who have signed up for a term deposit. This aids in the identification of a consumer profile that is more likely to purchase the product and the development of more focused marketing efforts.

This dataset contains banking marketing campaign data and we can use it to optimize marketing campaigns to attract more customers to term deposit subscription. 

## What is term deposit? 

A Term deposit is a deposit that a bank or a financial institurion offers with a fixed rate (often better than just opening deposit account) in which your money will be returned back at a specific maturity time.

## Attribute descriptions

age: Customers' age (numeric)

job: type of job (categorical: 'admin.','blue-collar','entrepreneur','housemaid','management','retired','self-employed','services','student','technician','unemployed','unknown')

marital: marital status (categorical: 'divorced','married','single','unknown'; note: 'divorced' means divorced or widowed)

education: (categorical: primary, secondary, tertiary and unknown)

default: has credit in default? (categorical: 'no','yes','unknown')

housing: has housing loan? (categorical: 'no','yes','unknown')

loan: has personal loan? (categorical: 'no','yes','unknown')

balance: Balance of the individual.

contact: contact communication type (categorical: 'cellular','telephone')

month: last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')

day: last contact day of the month (numeric: 1,2,3,....29,30)

duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

previous: number of contacts performed before this campaign and for this client (numeric)

poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

## Project workflow

![image](https://user-images.githubusercontent.com/74533550/138232029-e48dc9a5-2a9b-4a2a-9e99-9e8d7d5ec6ee.png)

