# Customer Churn Analysis

## Problem statement:
The company is facing a severe customer churn crisis, with 47.4% of 64,374 subscribers canceling their service, resulting in an estimated $18,991,722 in lost revenue and substantially higher customer acquisition costs.

## Executive Summary

This project establishes an end-to-end predictive machine learning framework to identify and mitigate customer churn. The workflow encompassed rigorous data cleaning, handling of missing values, and engineering targeted behavioral features, including binned age groups (`Age_Group`), segmented support interaction tiers (`Calls_Level`), payment delay indicators (`Delay_Level`), and tenure categories (`Tenure_Group`). Exploratory data analysis was conducted to uncover critical churn drivers across demographic lines, tenure bands, and support frequencies. Multiple supervised classification algorithms—including Logistic Regression, Decision Trees, Random Forest, and XGBoost—were trained and evaluated using Precision, Recall, F1-Score, and ROC-AUC metrics, prioritizing high Recall to effectively capture at-risk customers.

Model performance demonstrated high predictive accuracy, with ensemble models (Random Forest and XGBoost) achieving the highest Recall and ROC-AUC scores in detecting churn events. Key findings indicate that customer attrition is strongly influenced by specific demographic segments (gender and age groups) and severe payment delays (`High` Delay_Level). Crucially, analysis revealed that long-tenured customers (`High Tenure`) exhibit higher churn vulnerability, counteracting traditional retention assumptions. Furthermore, support call volume serves as an operational tipping point: while low call counts indicate stability, churn spikes past 60% once customers cross the threshold of 5 or more support calls, signalling underlying service or system friction.

In conclusion, customer churn stems from a combination of demographic friction, long-term subscription fatigue, and unresolved service issues. To improve retention, the business should implement targeted marketing and engagement campaigns for high-risk demographic groups, establish VIP loyalty and contract renewal incentives specifically for high-tenure accounts, launch proactive outbound support interventions at the 3rd or 4th call flag (`Calls_Level`), and provide flexible payment arrangements for accounts experiencing payment delays (`Delay_Level`).

## File Directory/table of contents


## Data and Data Dictionary
CustomerID: Unique identifier for each customer.

Age: Customer age in years.

Gender: Customer gender identity.

Tenure: Duration of the customer's subscription or relationship in months.

Usage_Frequency: Average monthly usage or session frequency.

Support_Calls: Total number of support calls placed by the customer.

Payment_Delay: Number of days payments have been delayed.

Subscription_Type: Tier or category of the customer's subscription plan.

Contract_Length: Duration type of the active contract.

Total_Spend: Cumulative monetary spend over the customer's lifespan.

Last_Interaction: Number of days since the customer's last platform login or interaction.

Churn: Target binary label indicating if the customer churned (1) or remained (0).

Engineered Features:

Age_Group: Categorical binned age tiers used to evaluate demographic churn patterns across age groups.
Delay: Categorical binary indicator categorizing customer payment delays into Low or High risk levels.
Calls_Level: Categorical risk tiers segmenting customers based on support call volume.


## Reco

Monitor customers who make frequent support calls and follow up on existing issues.

Offer flexible payment options and reminders to customers who are more likely to be late with payments.

Offer tiered upgrades based on tenure, giving long-standing customers added value that discourages them from cancelling their subscription.

Encourage customers to switch to longer-term contracts, such as annual ones.




