# Customer Churn Analysis

## Problem statement:
The company is facing a severe customer churn crisis, with 47.4% of 64,374 subscribers canceling their service, resulting in an estimated $18,991,722 in lost revenue and substantially higher customer acquisition costs.

## Executive Summary
This project presents a data-driven investigation into customer churn using a dataset of 64,374 subscribers. The primary objective was to perform exploratory data analysis (EDA) to understand subscriber distribution and identify key demographic patterns driving customer attrition. The analysis involved mapping churn binary indicators to categorical labels and segmenting the subscriber base across gender and specific age groups to extract actionable business insights

## File Directory/table of contents


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




