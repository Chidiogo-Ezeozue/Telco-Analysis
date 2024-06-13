# Telco-Analysis

## Introduction
This project conducts an in-depth analysis of customers from the telecommunications and subscription based sector to detect factors contributing to churn behavior and recommend strategies to improve retention. The dataset gives an overview of patterns and trends that inform customer behavior.

## Skills Demonstrated
* Data Cleaning
* Pivot Table
* Data Modeling
* Data Visualization
* Documentation

## Problem Statement

The aim of this analysis is to assess the rate of customer churn, analyze factors contributing to customer churn to improve retention strategies, and to create a churn prediction model to proactively identify and retain at-risk customers.

## Data Sourcing 
Dataset was retrieved from Kaggle and can be  accessed through the link below

https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1

## Data Cleaning/Transformation
Data was retrieved and loaded into the Power Query Editor in **MS Excel**. 

No duplicate values were found

Nulls were found in the “Total Charge” field; I studied the data and discovered that new customers with less than 1 month tenure do not have total charges yet.

Replaced “1” and “0” with “yes” and “no'' in the “Senior Citizen” field. Prior to that, I changed the numerical  data to a text data type.

Renamed the “Tenure” field to “Tenure(month)” for clarity.

Renamed “Churn” to “Churnstatus”

Replaced “No” with “Not Churned” and “Yes” with "Churned” in the now “Churnstatus” field.


Additionally, I created 3 more columns as follows,
* Churned
* Churned customers
* Not churned customers

## Analysis
I looaded 7,043 rows and 24 columns into Excel worksheet, and created two extra worksheet for analysis and visualization. 
With the use of **Pivot Table**, I carried out my analysis to display key indicators in the dataset


## Data KPIs
* Total Customers - 7043
* Churned Customers - 1869
* Retained Customers - 5174
* Churn rate - 26.54%
* Avg Monthly Charges - $64.8

## Findings 

* Gender Churn: No significant difference between male and female customers, although females churned more by 1%..

* Senior Citizen Churn: Senior citizens churn more than non senior citizens. Data shows low tech support; older customers might face difficulties in troubleshooting technical issues independently. Also, senior citizens might prioritize other expenses or services over telecom services making them more inclined to churn if they feel they are not getting adequate benefit.

* Dependent  Churn: Customers with dependents are less likely to churn compared to those without dependents.

* Churn by Partner: Customers with partners are more likely to churn less.

* Contract: Customers on a month-to-month Contract and are within a 12 month tenure have a highest churn rate of 43%

* Tech Support: The churn rate of customers with no tech support is very high showing 42% , hence reflecting poorly on the service delivery. Churn rate could be as a result of frustration due to unresolved technical issues leading to dissatisfaction or long wait time for support assistance causing inconvenience.

* Online Security:  Customers with no online security have a greater churn rate of 42%. This could be due to data breaches, security incidents, or even perceived vulnerabilities in the service platform raising concerns about personal information safety.

* Online Backup:  Churn rate of customers with no online backup is 40% showing deficiency in online support. This could lead to loss of critical data due to backup failures  and inconsistent backup processes leading to potential data loss, and resulting in a negative  customer experience.  

* Device Protection: No device protection rate is 39% high and customers without are likely to churn more. Unsatisfactory response or delays in device replacement or repair services can contribute to customer churn behavior.


Recommendations

1. I would recommend offering customers personalized contract options tailored to individual customer needs and usage patterns. This personalized approach can help increase customer satisfaction, reduce churn rate, and improve overall customer loyalty.

2. Customers should also be encouraged to extend their contract  term through an improved customer experience like available tech support, sufficient online security, stand-by online backup as well 24/7 device protection.
