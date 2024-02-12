
# Telecom Churn Case Study


A brief description of what this project does and who it's for


## Problem Statement
### Business Problem Overview


In the telecommunications industry, consumers have the option to choose from multiple service providers and frequently switch between them. With an average annual churn rate of 15-25%, retaining existing customers has become a priority for telecom companies. Acquiring new customers is significantly more expensive than retaining existing ones, making customer retention a critical aspect of business strategy.

In this competitive landscape, predicting which customers are likely to churn is essential for telecom companies to implement proactive retention strategies.
## Understanding and Defining Churn

Churn can be defined in various ways depending on the context:

Revenue-based churn: Identifying customers who have not generated any revenue from service usage over a specified period.

Usage-based churn: Identifying customers who have not utilized any services, such as calls or data, over a given period.

For this project, we'll focus on usage-based churn to define customers who are at risk of leaving the service.
## High-value Churn

In markets like India and Southeast Asia, approximately 80% of revenue comes from the top 20% of customers, known as high-value customers. Reducing churn among these high-value customers can significantly impact revenue retention.
## Understanding Customer Behavior During Churn

Customer churn typically occurs in three phases:

1. The 'good' phase: Customers are satisfied and behave normally.
2. The 'action' phase: Customers experience issues or receive offers from competitors, leading to changes in behavior.
3. The 'churn' phase: Customers decide to leave the service.
In this project, we'll focus on predicting churn during the action phase using data from the preceding months.
## Dataset and Data Dictionary

The dataset contains customer-level information spanning four consecutive months (June, July, August, and September). Each month is represented by the numbers 6, 7, 8, and 9, respectively.

The goal is to predict churn in the ninth month using data from the first three months.
## Data Preparation

Key data preparation steps include:

1. Deriving new features: Creating meaningful features based on business understanding.
2. Filtering high-value customers: Identifying customers with high revenue potential.
3. Tagging churners: Identifying customers who exhibit churn behavior based on usage patterns.
## Modelling

We'll build predictive models to achieve two main objectives:

Predict churn among high-value customers in the near future.
Identify important predictors of churn to understand customer behavior.
Steps include preprocessing data, exploratory analysis, feature engineering, dimensionality reduction using PCA, training various models, and evaluating model performance.

We'll prioritize models that accurately predict churn and identify significant predictor variables for business insights. Finally, we'll recommend strategies to manage customer churn based on our findings.