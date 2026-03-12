# Subscription Churn Early-Warning & Retention Strategy
Business Analytics Capstone Project

## Project Overview
This project analyzes subscriber churn for a simulated OTT platform called Immensity. 
The goal is to identify early warning signals of churn, build a predictive model, and 
recommend targeted retention strategies.

## Dashboard Preview
![Dashboard](dashboard_preview.png)

## Project Workflow
```
Raw Data
   ↓
Data Cleaning & ETL (Python)
   ↓
Feature Engineering
   ↓
Exploratory Data Analysis
   ↓
Cohort Retention & Segmentation
   ↓
Churn Driver Analysis
   ↓
Churn Prediction Model
   ↓
Business Insights & Retention Strategy
   ↓
Executive Dashboard
```
## Key Features
- Python ETL pipeline for cleaning and transforming subscription data
- Cohort retention and segmentation analysis
- Churn driver investigation using engagement metrics
- Machine learning models (Logistic Regression, Random Forest)
- Revenue at risk estimation
- Executive dashboard for business insights

## Model Performance
ROC-AUC: ~0.92  
Accuracy: ~89%

## Key Insights

• Users with declining engagement are significantly more likely to churn.  
• Lower price bands show higher churn rates but medium tier plans carry the highest revenue risk.  
• Early churn signals appear 2–4 weeks before cancellation through reduced sessions and usage minutes.  

## Retention Strategy

Based on the analysis, the following actions are recommended:

• Trigger early engagement nudges for users with declining usage trends  
• Offer targeted retention incentives for high-revenue segments  
• Improve payment failure recovery flows to prevent involuntary churn  

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook, Excel

## Project Structure
```
Business Problem
↓
Data Engineering
↓
Exploratory Analysis
↓
Machine Learning
↓
Business Strategy
```

## Business Impact

This analysis identifies early warning signals of subscriber churn and estimates the revenue at risk across different customer segments.

The churn prediction model enables proactive retention strategies by identifying high-risk users 7–14 days before potential cancellation.

By targeting high-risk segments with engagement nudges and retention offers, the platform can reduce churn and protect recurring subscription revenue.

## Future Improvements

• Incorporate additional behavioral features such as content category preferences  
• Use advanced models like XGBoost or LightGBM for improved prediction accuracy  
• Deploy the model as a real-time churn monitoring system  
• Integrate campaign response data for measuring retention intervention effectiveness



