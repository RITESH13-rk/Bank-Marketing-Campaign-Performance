# 📊 Bank Marketing Campaign Analysis | Power BI Dashboard
An interactive Power BI dashboard to analyze bank marketing campaign effectiveness and customer subscription behavior.

---

## 📊 Dashboard Preview
<img width="1156" height="652" alt="Screenshot 2026-01-11 133019" src="https://github.com/user-attachments/assets/88f589c5-6503-47df-932e-bdbf25db9d94" />

---

## 📌 Project Overview

This project focuses on analyzing a Bank Marketing Campaign to understand customer behavior and campaign effectiveness using Power BI.

The dashboard provides key insights into customer subscriptions, contact methods, and monthly trends, helping stakeholders make data-driven marketing decisions.

The dataset represents direct marketing campaigns (phone calls) of a banking institution, where the objective is to predict whether a client will subscribe to a term deposit.

---

## 🎯 Business Objective

- Analyze marketing campaign performance
- Identify customer segments with higher subscription rates
- Evaluate the effectiveness of contact methods
- Understand monthly subscription trends
- Improve future marketing strategies using insights

---

## 📂 Dataset Information

- **Dataset Name:** Bank Marketing Campaign
- **Source:** Kaggle
- **File Format:** CSV
- **Records:** 41,000+ customer interactions
- **Data Type:** Structured
- **Target Variable:** `subscribed` (Yes/No indicating whether term deposit was subscribed)


---

**Key Columns Used:**

- `job` – Customer occupation
- `education` – Education level
- `contact` – Contact communication type
- `month` – Last contact month
- `campaign` – Number of contacts performed
- `subscribed` – Target variable (Yes / No)

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Data Cleaning & Transformation**
- **Data Visualization**

---

## 📈 Key KPIs Created

- **Total Customers Contacted**
- **Total Subscriptions**
- **Average Contacts per Customer**
- **Subscription Rate (%)**

---

### 🔥 Core Highlights
- Identified the most effective contact method for customer subscriptions
- Found which customer segments have higher response rates
- Trend analysis over months to plan campaign timing

---


## 📊 Dashboard Visualizations

- Subscriptions by **Job Role**
- Subscriptions by **Education Level**
- Subscriptions by **Contact Method**
- **Monthly Subscription Trend**
- Interactive **Filters & Slicers**

---

## 🧮 DAX Measures Used

- **Total number of customers contacted**

      Total Customers Contacted = COUNTROWS ('bank_data')

- **Total customers who subscribed to a term deposit**

      Total Subscribed = CALCULATE (COUNTROWS ('bank_data' ),'bank_data'[subscribed] = "Yes")

- **Average number of contacts per customer**

      Average Contacts = AVERAGE ('bank_data'[campaign])

- **Subscription conversion rate**

      Subscription Rate (%) = DIVIDE ([Total Subscribed],[Total Customers Contacted], 0)

---

## 🔍 Key Insights

- Customers contacted via **cellular** channels show significantly higher subscription rates compared to other contact methods.
- **Management** and **Technician** roles demonstrate better conversion performance, indicating stronger targeting opportunities.
- Subscription trends vary noticeably across months, highlighting potential **seasonal effects** in campaign performance.
- Increasing the number of contacts does not consistently improve conversion, suggesting the importance of **contact quality over frequency**.

---

## 📁 Project Structure

       Bank-Marketing-Campaign-Performance/
       │
       ├── Data/
       │   └── bank_marketing.csv
       │
       ├── Dashboard/
       │   └── Bank_Marketing_Campaign_Dashboard.pbix
       │
       ├── Screenshots/
       │   └── Dashboard_Preview.png
       │
       ├── README.md
       └── LICENSE

---

## 🚀 How to Use

1. Download or clone the repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Refresh the dataset if required
4. Explore insights using slicers and filters

---

### 🧠 What I Learned
- How to build data models in Power BI
- Creating and optimizing DAX measures for KPIs
- Designing dashboards with user-friendly visuals

---

## 👤 Author
**Ritesh Koushal**

Aspiring Data Analyst | Power BI | Data Visualization
