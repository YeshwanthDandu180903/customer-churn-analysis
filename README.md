# 📊 Customer Churn Prediction (SQL + Power BI + Python)

This project demonstrates a complete data analytics and machine learning pipeline — from **ETL in SQL Server** to **Power BI dashboards** and **churn prediction using Python**.  
It aims to help businesses identify at-risk customers, understand churn drivers, and support marketing strategies.

---

## 🚀 Project Overview
The project followed a four-stage process:
1. **ETL and Database Preparation (SQL Server)**
   - Imported raw data into a staging table (`stg_churn`) and applied data integrity checks.
   - Cleaned, transformed, and stored processed data in a production table (`prod_churn`).
   - Created analytical SQL views (`vw_churn_data`, `vw_join_data`) for downstream ML integration.

2. **Dashboard Development (Power BI)**
   - Connected Power BI to SQL Server and performed transformations in Power Query.
   - Built reference tables (`mapping_age_grp`, `mapping_tenure_grp`) for categorized visual insights.
   - Designed an interactive dashboard showing KPIs like **Total Customers**, **Churn Rate**, and **New Joiners**.
   - Visualized churn by demographics, geography, contract type, payment mode, and service usage.

3. **Machine Learning Model (Python)**
   - Imported SQL view data into Python for modeling using **pandas** and **scikit-learn**.
   - Encoded categorical data, split dataset (80/20), and trained a **Random Forest Classifier**.
   - Achieved **~84% accuracy** and analyzed feature importance to identify churn predictors.
   - (Model deployment in progress — will be integrated into Power BI dashboard and Flask app.)

---

## 🧠 Tech Stack
**Languages & Tools:**  
SQL Server | Power BI | Python | pandas | NumPy | scikit-learn | GitHub

**Key Skills Demonstrated:**  
ETL Pipelines · Data Cleaning · Feature Engineering · Data Visualization · Machine Learning · Dashboard Design

---

## 📊 Dashboard Preview
![Churn Dashboard](./reports/churn_dashboard.png)

---

## 📈 Results
- Identified key churn drivers like contract type, payment method, and service usage.  
- Built predictive model for proactive churn management (84% accuracy).  
- Created an interactive BI dashboard for decision-makers.

---

## 📅 Project Status
✅ ETL Process Completed  
✅ Power BI Dashboard Built  
⚙️ Machine Learning Model (In Progress)  
🚀 Deployment Pending

---

## 📬 Author
**Yeshwanth Dandu**  
B.Tech (CSE - Data Science), Institute of Aeronautical Engineering, Hyderabad  
📧 [yeshwanthdandu2003@gmail.com](mailto:yeshwanthdandu2003@gmail.com)  
🌐 [LinkedIn](https://www.linkedin.com/in/yeshwanthdandu) | [GitHub](https://github.com/YeshwanthDandu180903)
