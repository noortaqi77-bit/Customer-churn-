# Customer Churn Analysis

## Problem statement:
The company is facing a severe customer churn crisis, with 47.4% of 64,374 subscribers canceling their service, resulting in an estimated $18,991,722 in lost revenue and substantially higher customer acquisition costs.

## Executive Summary
This project analyzes customer churn using a dataset of 64,374 customers to identify the main factors associated with customer cancellation. The analysis was conducted using Python (Pandas and Matplotlib) through data cleaning, exploratory data analysis (EDA), feature engineering, and visualization.

The dataset shows an overall churn rate of 47.4%, indicating that nearly half of the customers discontinued the service. The analysis found that churn is strongly associated with contract length, customer tenure, payment delay, and the number of support calls, while demographic factors such as age and gender showed relatively smaller differences.

## File Directory/table of contents
README file : 
cleaned_customer_churn.csv : the cleaned data
customer_churn.csv : Original data
customer_churn_project2 : code file
customer churn - project 2 : presentation



## Data and Data Dictionary
CustomerID: Unique identifier for each customer.

Age: Customer age.

Gender: Customer gender identity.

Tenure: Duration of the customer's subscription in months.

Usage_Frequency: Average monthly usage or session frequency.

Support_Calls: Total number of support calls placed by the customer.

Payment_Delay: Number of days payments have been delayed.

Subscription_Type: category of the customer's subscription plan.

Contract_Length: Duration type of the active contract.

Total_Spend: Cumulative monetary spend over the customer's lifespan.

Last_Interaction: Number of days since the customer's last platform login or interaction.

Churn: Target binary label indicating if the customer churned (1) or remained (0).

Engineered Features:
Age_Group: Categorical binned age tiers used to evaluate demographic churn patterns across age groups.
Delay: Categorical binary indicator categorizing customer payment delays into Low or High risk levels.
Calls_Level: Categorical risk tiers segmenting customers based on support call volume.


## Recommendations

Monitor customers who make frequent support calls and follow up on existing issues.

Offer flexible payment options and reminders to customers who are more likely to be late with payments.

Offer tiered upgrades based on tenure, giving long-standing customers added value that discourages them from cancelling their subscription.

Encourage customers to switch to longer-term contracts, such as annual ones.




