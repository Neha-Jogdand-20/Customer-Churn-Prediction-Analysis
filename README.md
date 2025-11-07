# Customer Churn Prediction & Retention Analysis

This project focuses on identifying customers who are likely to churn and developing retention strategies based on behavioral patterns, service usage, financial data, and customer feedback.  
The project demonstrates end-to-end data analytics covering **Data Cleaning, SQL Operations, Power BI Dashboarding, and Business Insights.**

---

## 🎯 Problem Statement
Telecom and subscription-based businesses lose a significant number of customers every month.  
The objective of this project is to:

- Identify customers who are at **high risk of churn**
- Understand **key factors** influencing churn
- Provide **actionable insights** to improve retention and reduce revenue loss

---

## 🧠 Key Analytical Questions
- Which demographics show the highest churn?
- How spending behavior relates to churn probability?
- Does product usage / support / complaints influence churn?
- Which customer segments are most valuable to retain?
- How satisfaction and feedback impact churn decisions?

---

## 🗂️ Dataset Overview
The project uses **three datasets**:

| Table Name | Description | Source |
|-----------|-------------|--------|
| `customer_churn` | Main customer demographic and subscription data | Kaggle |
| `payment_info` | Billing region & total amount spent | SQL-created |
| `customer_feedback` | Feedback & complaint records | SQL-created |

---

## 🔧 Tools & Technologies Used
| Category | Tools |
|--------|-------|
| Programming | Python (Pandas, NumPy) |
| Database | MySQL / SQL Joins / Aggregations |
| Visualization | Power BI |
| File Formats | CSV, XLSX, PDF |
| Version Control | Git & GitHub |

---

## 🛠️ Project Workflow

### 1️⃣ Data Cleaning (Python / Pandas)
- Removed missing & inconsistent values  
- Created new features for contract type, service usage patterns  
- Exported cleaned dataset for SQL & BI  

### 2️⃣ Data Storage & SQL Analysis
- Created tables in MySQL  
- Inserted & linked additional tables (`payment_info`, `customer_feedback`)  
- Performed:
  - **LEFT / RIGHT Joins**
  - **Aggregations**
  - **Customer segmentation queries**
  - **Regional revenue analysis**

### 3️⃣ Power BI Dashboarding
- Built **interactive dashboards** to visualize:
  - Churn vs Non-Churn Customers
  - Customer Lifetime Value (CLV)
  - Feedback Score vs Churn Rate
  - Churn by Region (Map Chart)
  - Complaint Count vs Churn

---

## 📊 Dashboard Preview (Screenshots)

<img width="451" height="262" alt="image" src="https://github.com/user-attachments/assets/cefe14a0-1136-44c2-a9e7-bf7f06c882d9" />


---

## 🧩 Key Insights & Findings
| Insight | Business Impact |
|--------|----------------|
| Customers with **month-to-month contracts** churn more frequently | Recommend offering discounts for yearly plans |
| **Low Feedback Score** strongly correlates with high churn | Improve support responsiveness |
| Customers with **high complaint count** are more likely to leave | Introduce proactive support callbacks |
| Certain regions show **higher churn & lower revenue** | Regional retention strategy required |

---

## 🧑‍💼 Business Outcomes
✔ Reduced churn by identifying high-risk customer clusters  
✔ Supported retention planning and loyalty program design  
✔ Enabled data-driven decision making  

---

## 📦 Repository Structure
📂 Customer-Churn-Prediction-Analysis
│── Churn Analysis.ipynb
│── Customer Churn Query.sql
│── Cleaned_Customer_Churn.xlsx
│── customer_feedback.csv
│── payment_info.csv
│── Churn Analysis Dashboard.pdf
│── README.md


---

## 💡 Skills Demonstrated
- Data Cleaning & Pre-Processing
- Relational Database Design & SQL Joins
- DAX & Power BI Dashboard Building
- Analytical thinking and business insight storytelling

---

## ✨ Author
**Neha Jogdand**  
_Data Analyst | Python | SQL | Power BI| Excel_




