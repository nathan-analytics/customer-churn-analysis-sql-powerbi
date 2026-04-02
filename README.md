# Telco Customer Churn Analysis

Analyzed 7,043 telecom customers using SQL and Power BI to identify key drivers of churn and improve customer retention.

## Project Summary

Evaluated customer behavior to understand why customers churn and what factors increase retention.

Key findings:
- Overall churn rate is 26.54% (1,869 customers)
- Month-to-month contracts have the highest churn (~42.7%)
- First-year customers are the highest-risk group (~48% churn)
- Electronic check users churn the most (~45%)
- Long-term contracts and auto-pay significantly reduce churn

Business impact:
- Identifies high-risk customer segments for targeted retention strategies
- Highlights contract structure as a major driver of churn
- Supports improving onboarding to reduce early customer loss
- Provides actionable insights to improve long-term customer value

## Dashboard Highlight

Month-to-month customers show significantly higher churn (~43%), 
making contract structure the most critical driver of customer retention.

![Churn Dashboard](https://github.com/user-attachments/assets/ca92515c-bb0d-47ff-88c8-fa03b2c00693)

## Case Study

[Customer Churn Analysis Case Study](case_study.pdf)

## Key Insights

- Contract type is the strongest predictor of churn
- Early-tenure customers are significantly more likely to leave
- Payment method impacts retention, with manual methods increasing churn risk
- Retention improves as customer tenure increases

## Project Overview

This project simulates a real-world churn analysis workflow using customer-level telecom data.

Workflow:
- Cleaned and transformed raw data using SQL
- Created derived fields and analytical tables
- Built SQL views for structured analysis
- Developed a Power BI dashboard to visualize churn patterns

## Data Cleaning

- Renamed columns to snake_case for consistency
- Cleaned and converted total_charges to numeric
- Handled missing values using NULL logic
- Created churn_flag (1 = churn, 0 = retained)
- Built a clean analytical table (churn_clean)

## SQL Analysis

Created queries and views to analyze churn behavior:
- Overall churn KPIs
- Contract type churn comparison
- Customer tenure analysis
- Payment method churn patterns

## Dashboard Features

- Overall churn rate KPI
- Churn breakdown by contract type
- Churn by tenure groups
- Payment method analysis
- Customer segmentation insights

## Business Recommendations

- Promote longer-term contracts to reduce churn risk
- Improve onboarding for first-year customers to increase retention
- Encourage automatic payment methods to reduce churn associated with manual payments
- Monitor high-risk segments for targeted retention efforts

## Tools Used

- SQL (PostgreSQL)
- Power BI

## Dataset

Customer churn dataset (~7,043 customers)

Key fields:
- contract
- tenure
- payment_method
- monthly_charges
- internet_service
- tech_support
- online_security

## Project Structure

customer-churn-analysis/  
├── 01_data_raw/  
├── 02_sql/  
├── 03_powerbi/  
├── 04_screenshots/  
├── case_study.pdf  
└── README.md
