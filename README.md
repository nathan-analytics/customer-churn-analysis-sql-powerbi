# Customer Churn Analysis

Analysis of ~7,000 telecom customers to identify churn drivers and high-risk segments.

---

## Project Summary

Analyzed ~7K customers using SQL and Power BI to identify which customers churn and why.

Cleaned and transformed data in PostgreSQL, handled missing values, and created a churn_flag to support analysis.

Built SQL queries and a dashboard to segment churn by contract type, tenure, and payment method.

---

## Dashboard Preview

**Churn Overview**  
<img width="1314" height="709" alt="churn_rate_powerbi" src="https://github.com/user-attachments/assets/594e727e-75e3-49ac-a2db-6f820082b76a" />

---

## Case Study

Full breakdown of the business problem, methodology, and recommendations:

[customer churn analysis.pdf](https://github.com/user-attachments/files/26551235/customer.churn.analysis.pdf)

---

## Key Insights

- Month-to-month contracts have ~43% churn rate  
- Customers in their first year have the highest churn risk  
- Electronic check users show the highest churn levels  
- Long-term contracts significantly reduce churn  
- Churn is driven by customer lifecycle and payment behavior

These results highlight clear opportunities to reduce churn through contract strategy, onboarding improvements, and payment optimization.

---

## Business Problem

Customer churn directly impacts revenue and growth. Without understanding why customers leave, companies struggle to:

- Retain high-value customers  
- Reduce revenue loss  
- Improve long-term customer relationships  

This project identifies key churn drivers and highlights actionable retention opportunities.

---

## Business Impact

- Encourage long-term contracts to reduce churn  
- Improve onboarding experience for new customers  
- Promote auto-pay options to increase retention  
- Target high-risk segments with retention campaigns  

---

## Data Pipeline

Raw Data (Customer Dataset)  
→ PostgreSQL (Data Cleaning and Feature Creation)  
→ SQL (Churn Analysis and Segmentation)  
→ Power BI (Dashboard and Visualization)

---

## Methodology

### Data Cleaning & Preparation
- Cleaned and transformed raw customer data in PostgreSQL  
- Handled missing values and standardized data types  
- Created `churn_flag` for easier analysis  

### Analysis & Segmentation
- Segmented churn by contract type, tenure, and payment method  
- Calculated churn rates across key customer groups  
- Identified high-risk segments and behavioral patterns  

### Visualization
- Built Power BI dashboard to highlight churn drivers  
- Designed visuals for quick stakeholder understanding  

---

## Tech Stack

- PostgreSQL (data cleaning, transformation, analysis)  
- Power BI (dashboard development and visualization)  

---

## Project Structure

```
customer-churn-analysis/  
├── 01_data_raw/  
├── 02_sql/  
├── 03_powerbi/  
├── 04_screenshots/  
├── case_study.pdf  
└── README.md
```

---

## What This Project Demonstrates

- Customer segmentation and behavioral analysis  
- Strong SQL data transformation skills  
- Ability to identify business risk and retention opportunities  
- Translating data into actionable strategies  

---

## Business Recommendations

- Encourage long-term contracts to reduce churn risk
- Improve onboarding experience for first-year customers
- Promote auto-pay adoption to reduce churn associated with payment friction

---

## Key Takeaway

Churn is concentrated in early-stage and short-term customers, making retention efforts in the first year the highest-impact lever for reducing revenue loss.
