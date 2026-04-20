# 📊 Customer Churn Analysis & KPI Dashboard

## 🚀 Business Problem

Customer churn is a critical revenue risk for telecom companies, directly impacting profitability and growth.

This project builds an **end-to-end churn analytics solution** to identify at-risk customers and enable targeted, data-driven retention strategies.

---

## 🎯 Business Objective

* Identify **customers likely to churn**
* Understand **key drivers of churn**
* Enable **targeted retention actions** instead of blanket offers

---

## 🗂 Dataset

* **Rows:** 6,418 customers
* **Domain:** Telecom subscription data

**Key attributes:**

* Demographics (Age, Gender, State)
* Account & tenure information
* Pricing & revenue metrics
* Contract & service features
* Customer status (Stayed / Churned)

---

## 🧹 Data Preparation (SQL)

* Standardized categorical values
* Handled missing/blank values with meaningful defaults
* Built a **production-ready table (`prod_Churn`)**
* Preserved raw and intermediate layers for traceability

**Key principle:**

> Data cleaning handled in SQL, analytics & modeling handled downstream

---

## 📊 Power BI – Executive KPI Dashboard

Built a **1-page executive dashboard** designed for business decision-making.

### Dashboard Highlights

* Churn rate segmented by contract type and tenure
* Revenue contribution and revenue at risk
* Customer distribution across key segments
* Key churn drivers visualized for leadership insights

👉 Designed for **quick, executive-level interpretation**

---

## 🤖 Python – Churn Modeling

### Modeling Approach

Built and compared:

* **Logistic Regression** → interpretable baseline
* **Random Forest** → non-linear benchmark

Models were evaluated using **ROC-AUC** and business-aligned metrics.

### Evaluation & Threshold Strategy

* ROC Curve, Precision–Recall Curve, Confusion Matrix
* Decision threshold tuned to **prioritize recall for churned customers**

👉 This reflects real-world scenarios where **missing churners is more costly than false positives**

---

## 🔍 Key Insights

* Customers with **low tenure (<6 months)** show significantly higher churn risk
* **Month-to-month contracts** are the primary driver of churn
* **Higher monthly charges** increase churn probability (price sensitivity)
* Contract structure and pricing are stronger predictors than demographics

---

## 🎯 Retention Strategy (Business Interpretation)

The churn predictions enable:

* **Who to target:** High-risk customer segments
* **When to act:** Early lifecycle (low tenure customers)
* **How to act:** Tailored interventions based on churn drivers

**Example Actions:**

* Price-sensitive users → discounts or plan optimization
* Month-to-month users → incentivize long-term contracts
* Early-tenure users → onboarding & engagement programs

---

## 📈 Business Impact

* Enables proactive identification of high-risk customers
* Supports targeted retention campaigns instead of blanket discounts
* Improves efficiency of marketing spend and customer lifetime value

---

## 🛠 Tools & Technologies

* **SQL** – Data cleaning & transformation
* **Python** – Pandas, NumPy, Scikit-learn
* **Power BI** – KPI dashboard & visualization

---

## 📌 Project Type

* ✔ Churn Modeling
* ✔ Retention Analytics
* ✔ Customer / Product Analytics
* ✔ Executive KPI Reporting

---

## 📬 Author

**Bodhisatva Mukherjee**
