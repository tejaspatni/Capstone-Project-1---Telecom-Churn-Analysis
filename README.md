# Capstone-Project-1---Telecom-Churn-Analysis
## Introduction
Telecom industry is a highly competitive market with multiple service providers where customers can actively switch from one operator to another resulting in a high churn rate. Here customer retention becomes more important than customer acquisition for a profitable business. In this project we will perform EDA on the given Telecom dataset to discover key factors responsible for customer churn and recommend business strategies to ensure customer retention.Churn Customer can be defined as a user who is likely to discontinue using the services. So, the target variable confirm if the customer has churned
## Problem Statement
Orange S.A., formerly France Télécom S.A., is a French multinational telecommunications corporation. The Orange Telecom's Churn Dataset, consists of cleaned customer activity data (features), along with a churn label specifying whether a customer canceled the subscription.
In this problem statement we were required to explore and analyze the data to discover key factors responsible for customer churn and come up with ways/recommendations to ensure customer retention.
## Dataset
The data included 3333 users and by the exploratory analysis, it is observed that:

14.5% of the base are classified as churn.

50% of the customers who called the company more than 5 times are classified as Churn.

11.4% of those with no international plan are classified as Churn vs 42.4% of those with an international plan are Churn.

Columns : 'state','area_code','account_length','international_plan','voice_mail_plan','number_vmail_messages','total_day_minutes','total_day_calls','total_day_charge','total_eve_minutes','total_eve_calls','total_eve_charge','total_night_minutes','total_night_calls','total_night_charge','total_intl_minutes','total_intl_calls','total_intl_charge','number_customer_service_calls'.


## Total Churning and analysis

![image](https://user-images.githubusercontent.com/118215277/209218142-64c189a8-1e1e-4ece-a264-7f9210c548f5.png)

From the above chart I got to know that, there are 2850 customers which are not churned which is 85.5% of the whole customers data given in the dataset. In other hand, 483 customers are churned which is 14.5% of the whold customers data given in the dataset.

![image](https://user-images.githubusercontent.com/118215277/209219648-d02278eb-d8ff-412c-9a24-0f6a05588cbb.png)

The people that are churning pay more charge that non-churn customers.
We can retain churn customers if we include benefit plan. In benefit plan if a customer is talking more minutes then we can charge a little less amount from him or he can get discount or additional few free minutes to talk.

This will make customers who are going to churn happy and they will not leave the company.

## Solution to Reduce Customer Churn

Modify International Plan as the charge is same as normal one.

Modify Dynamic Pricing

Periodically throw Offers to retain customers.

Look at the customers facing problem in the most churning states.

Lean into best customers.

Regular Server Maintenance.

Solving Poor Network Connectivity Issue.

Define a roadmap for new customers.

Analyze churn when it happens.

Stay competitive.

## Conclusion
The area code field and/or the state field are anomalous, and can be omitted.

Customers with the International Plan tend to churn more frequently.

Customers with four or more customer service calls churn more than four times as often as do the other customers.

Customers with high Total minutes tend to churn at a higher rate than do the other customers because of high charges

There is no obvious association of churn with the variables Total calls, Total Minutes, international calls, international minutes, account length, or voice mail messages.
