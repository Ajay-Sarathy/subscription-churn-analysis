##Subscription Churn Early-Warning & Retention Strategy##
Project Overview

This project analyzes customer churn behavior for a subscription-based OTT platform called Immensity. The goal is to identify early warning signals of churn, build a predictive model to detect churn risk, and recommend targeted retention strategies.

Subscription-based businesses rely on long-term customer retention to sustain recurring revenue. By analyzing user engagement patterns, subscription activity, and payment behavior, this project develops a data-driven framework to predict churn and support proactive retention efforts.

##Business Objective##

The objectives of this project are:

Identify behavioral patterns associated with subscriber churn

Predict churn risk 7–14 days in advance

Estimate revenue exposure due to churn

Recommend targeted retention strategies

##Dataset##

The analysis uses multiple datasets including:

Users dataset – user demographics and signup information

Subscriptions dataset – subscription plan and billing details

Usage dataset – daily platform activity and engagement metrics

Payments dataset – payment attempts and failures

Campaign touchpoints dataset – marketing interaction history

##Data Engineering (ETL Pipeline)##

A Python ETL pipeline was built to clean and standardize the raw data.

The pipeline produces three curated datasets:

dim_users_enriched
fact_user_weekly
model_churn_dataset

These datasets support cohort analysis, churn diagnostics, and machine learning modeling.

##Key Analysis Performed##
**Cohort Retention Analysis**

Cohort analysis was used to track user retention trends over time and identify periods where churn risk increases.

**Churn Driver Investigation**

User engagement metrics were analyzed to identify behavioral signals associated with churn. The analysis found that declining platform usage is a strong predictor of churn.

**Segmentation Analysis**

Churn patterns were analyzed across different price bands, tenure groups, and engagement levels to identify high-risk segments.

**Churn Prediction Model**

Two machine learning models were trained:

Logistic Regression

Random Forest

**Model Performance**

ROC-AUC ≈ 0.92

Accuracy ≈ 89%

##Key predictive features include:##

Usage decline

Average session activity

Minutes used

Days since last activity

Subscription price band

Business Insights

##Key insights from the analysis include:##

Users who churn show 80–90% lower engagement prior to cancellation

Retention declines significantly within the first few months of subscription

Medium-priced plans represent the largest revenue exposure to churn

##Recommended Retention Strategy##

Based on the churn analysis and prediction model, the following strategies are recommended:

User Segment	Retention Strategy
High Risk + High Revenue	Immediate retention offer
Medium Risk	Engagement campaigns
Low Risk	Monitor user behavior

##Dashboard##

An executive dashboard was developed to summarize key findings including:

Churn distribution

Cohort retention trends

Churn drivers

Revenue at risk

Model insights

##Tools & Technologies##

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook
Excel (Dashboard).
