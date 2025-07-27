# Customer Subscriptions Dataset

## Overview

This dataset originates from a fictional subscription-based streaming service that delivers digital content to customers across various countries. The business operates in a highly competitive market where customer acquisition costs are rising, and long-term profitability depends heavily on customer retention. Understanding user behaviour—particularly what drives cancellations versus long-term engagement—is essential to optimising subscription strategies and reducing churn.

## Business Context

The streaming service offers multiple subscription plans with varying pricing tiers, supported on several device types and accessed by users from diverse geographic regions. Customers join the platform via different referral channels and engage with the content at different levels. The company seeks to use this dataset to:

- Identify patterns that predict customer churn
- Evaluate how pricing, engagement, and support interactions influence retention
- Compare regional and behavioural trends across customer segments
- Optimise marketing and referral strategies to improve loyalty

## Objective

The primary objective is to enable exploratory and predictive analysis of customer retention behaviour. This supports the development of data products such as churn prediction models, retention dashboards, customer segmentation frameworks, and executive reports that drive strategic decisions.

## Dataset Description

The dataset includes a total of **15 variables**, each capturing a distinct aspect of the customer lifecycle or profile. Each row represents an individual customer record.

### Variables

| Variable              | Type         | Description                                                                 |
|-----------------------|--------------|-----------------------------------------------------------------------------|
| `CustomerID`          | Identifier   | Unique ID assigned to each customer                                         |
| `JoinDate`            | Date         | The date the customer subscribed to the platform                            |
| `LastLoginDate`       | Date         | The most recent login date recorded for the customer                        |
| `SubscriptionType`    | Categorical  | The tier of the subscription (e.g., Basic, Standard, Premium)               |
| `MonthlyFee`          | Numerical    | Monthly cost of the subscription plan in USD                                |
| `TotalWatchTime`      | Numerical    | Cumulative total of content watched, measured in minutes                    |
| `NumSupportTickets`   | Numerical    | Number of support tickets or help requests submitted by the customer        |
| `LoyaltyPoints`       | Numerical    | Accumulated points earned through engagement or loyalty schemes             |
| `ReferralSource`      | Categorical  | Origin of customer acquisition (e.g., Friend, Social Media, Advertisement)  |
| `PreferredDevice`     | Categorical  | Device type most frequently used (e.g., Mobile, Smart TV, Desktop)          |
| `PaymentMethod`       | Categorical  | Payment channel used (e.g., Credit Card, PayPal)                            |
| `PaymentFrequency`    | Categorical  | Frequency of billing (e.g., Monthly, Yearly)                                |
| `Country`             | Categorical  | Country of residence                                                        |
| `Region`              | Categorical  | Geographic subdivision such as state or province                           |
| `Cancelled`           | Categorical  | Customer status: 1 = Cancelled, 0 = Active                                  |

## Data Use Applications

This dataset can support various analytical and modelling tasks, including:

- Customer churn prediction using machine learning
- Retention cohort analysis by subscription start month
- Customer lifetime value estimation
- Revenue forecasting by segment or geography
- Behavioural clustering for targeted marketing
- Interactive business intelligence dashboards (e.g., in Power BI)
# Customer Subscriptions Dataset

## Overview

This dataset originates from a fictional subscription-based streaming service that delivers digital content to customers across various countries. The business operates in a highly competitive market where customer acquisition costs are rising, and long-term profitability depends heavily on customer retention. Understanding user behaviour—particularly what drives cancellations versus long-term engagement—is essential to optimising subscription strategies and reducing churn.

## Business Context

The streaming service offers multiple subscription plans with varying pricing tiers, supported on several device types and accessed by users from diverse geographic regions. Customers join the platform via different referral channels and engage with the content at different levels. The company seeks to use this dataset to:

- Identify patterns that predict customer churn
- Evaluate how pricing, engagement, and support interactions influence retention
- Compare regional and behavioural trends across customer segments
- Optimise marketing and referral strategies to improve loyalty

## Objective

The primary objective is to enable exploratory and predictive analysis of customer retention behaviour. This supports the development of data products such as churn prediction models, retention dashboards, customer segmentation frameworks, and executive reports that drive strategic decisions.

## Dataset Description

The dataset includes a total of **15 variables**, each capturing a distinct aspect of the customer lifecycle or profile. Each row represents an individual customer record.

### Variables

| Variable              | Type         | Description                                                                 |
|-----------------------|--------------|-----------------------------------------------------------------------------|
| `CustomerID`          | Identifier   | Unique ID assigned to each customer                                         |
| `JoinDate`            | Date         | The date the customer subscribed to the platform                            |
| `LastLoginDate`       | Date         | The most recent login date recorded for the customer                        |
| `SubscriptionType`    | Categorical  | The tier of the subscription (e.g., Basic, Standard, Premium)               |
| `MonthlyFee`          | Numerical    | Monthly cost of the subscription plan in USD                                |
| `TotalWatchTime`      | Numerical    | Cumulative total of content watched, measured in minutes                    |
| `NumSupportTickets`   | Numerical    | Number of support tickets or help requests submitted by the customer        |
| `LoyaltyPoints`       | Numerical    | Accumulated points earned through engagement or loyalty schemes             |
| `ReferralSource`      | Categorical  | Origin of customer acquisition (e.g., Friend, Social Media, Advertisement)  |
| `PreferredDevice`     | Categorical  | Device type most frequently used (e.g., Mobile, Smart TV, Desktop)          |
| `PaymentMethod`       | Categorical  | Payment channel used (e.g., Credit Card, PayPal)                            |
| `PaymentFrequency`    | Categorical  | Frequency of billing (e.g., Monthly, Yearly)                                |
| `Country`             | Categorical  | Country of residence                                                        |
| `Region`              | Categorical  | Geographic subdivision such as state or province                            |
| `Cancelled`           | Categorical  | Customer status: Cancelled, Active                                          |

## Data Use Applications

This dataset can support various analytical and modelling tasks, including:

- Customer churn prediction using machine learning
- Retention cohort analysis by subscription start month
- Customer lifetime value estimation
- Revenue forecasting by segment or geography
- Behavioural clustering for targeted marketing
- Interactive business intelligence dashboards (e.g., in Power BI)
