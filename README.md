# Telco Customer Churn Analysis  
SQL + Power BI  

Analyzed 7,043 telecom customers to identify key drivers of churn and opportunities to improve retention.

---

## Dashboard Preview  
<img width="1314" height="709" alt="churn_rate_powerbi" src="https://github.com/user-attachments/assets/ca92515c-bb0d-47ff-88c8-fa03b2c00693" />

---

## 📄 Case Study  
[customer churn analysis.pdf](https://github.com/user-attachments/files/26418184/customer.churn.analysis.pdf)

---

## Key Insights  
• Overall churn rate is 26.54% (1,869 customers)  
• Month-to-month contracts have the highest churn (~42.7%)  
• First-year customers have the highest churn (~48%)  
• Electronic check users churn the most (~45%)  
• Long-term contracts and auto-pay significantly reduce churn  

---

## Business Questions  
• What contract types have the highest churn?  
• What customer tenure groups experience the most churn?  
• What payment methods are associated with the highest churn?  

---

## Project Overview  
This project analyzes telecom customer data to identify the main factors driving churn.

The workflow simulates a real-world analytics process:
• Cleaned and transformed raw data using SQL  
• Created analytical tables and views for reporting  
• Built a Power BI dashboard to explore churn patterns  

The final output highlights how contract type, tenure, and payment behavior impact customer retention.

---

## Tools Used  
SQL (PostgreSQL), Power BI  

---

## Dataset  
Customer churn dataset (~7,043 customers)

Key fields:
contract, tenure, payment_method, monthly_charges, internet_service, tech_support, online_security  

---

## Data Cleaning  
• Renamed columns to snake_case for consistency  
• Cleaned total_charges field and converted to numeric  
• Handled missing values using NULL logic  
• Created churn_flag (1 = churn, 0 = retained)  
• Built a clean analytical table (churn_clean)  

---

## SQL Analysis  
Created queries and views to analyze churn behavior:
• Overall churn KPIs  
• Contract type churn comparison  
• Customer tenure analysis  
• Payment method churn patterns  

---

## Business Recommendations  
• Promote longer-term contracts to reduce churn  
• Improve onboarding experience for first-year customers  
• Encourage automatic payment methods to improve retention  

---

## Project Structure  
01_data_raw/ – Raw dataset  
02_sql/ – SQL scripts  
03_powerbi/ – Dashboard file  
04_screenshots/ – Dashboard images  
case_study.pdf – Project summary  
README.md – Documentation  
