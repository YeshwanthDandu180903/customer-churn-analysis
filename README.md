# 📊 Customer Churn Prediction

**SQL • Python (Machine Learning) • Power BI**

This project implements an **end-to-end customer churn analytics pipeline**, combining **SQL for data transformation**, **Python for machine learning**, and **Power BI for visualization** to identify at-risk customers and support data-driven retention strategies.

---
## 🚀 Project Overview

### 🔹 SQL (Data Cleaning, Transformation & Business Metrics)

- Raw customer data was processed using **Microsoft SQL Server Management Studio (SSMS)**.
- Performed comprehensive data preparation in SQL, including:
  - Data cleaning and validation
  - Data transformations based on business rules
  - Creation of customer-level metrics and aggregations
- Built clean, analytics-ready tables and SQL views for downstream usage.
- Exported the finalized dataset from SQL and loaded it into **Google Colab** for:
  - Exploratory Data Analysis (EDA)
  - Machine Learning model development using Python

### 🔹 Python (EDA & Machine Learning)

* Imported curated SQL data into Python
* Conducted:

  * Exploratory Data Analysis (EDA)
  * Feature engineering and encoding
  * Train / validation / test splitting
* Trained and evaluated multiple ML algorithms:

  * Logistic Regression
  * KNN
  * Naive Bayes
  * Decision Tree
  * Random Forest
  * AdaBoost
* Compared models using **Accuracy, Precision, Recall, and F1-score**
* **Random Forest** achieved the best performance and was selected as the final model

  * **~94% accuracy**
  * Outperformed Decision Tree and baseline models
* Generated **churn predictions** and **churn probability scores**

---

### 🔹 Power BI (Visualization & Insights)

* Loaded prediction outputs into Power BI
* Built interactive dashboards to visualize:

  * Predicted churners
  * Churn probability distribution
  * Churn by demographics, contract type, tenure, and geography
* Enabled business users to analyze churn risk and prioritize retention actions



## 📈 Output

* Final dataset includes:

  * Churn prediction (0/1)
  * Churn probability score per customer
* Outputs exported in **Power BI–ready format** for reporting and analysis

---

## 🧠 Key Technologies

* **SQL Server** – Data cleaning, transformation, aggregation
* **Python** – EDA, machine learning, model evaluation
* **Power BI** – Interactive dashboards and business insights

---

## 📬 Author

**Yeshwanth Dandu**
B.Tech (CSE – Data Science)
📧 [yeshwanthdandu2003@gmail.com](mailto:yeshwanthdandu2003@gmail.com)
🔗 LinkedIn | GitHub

---

