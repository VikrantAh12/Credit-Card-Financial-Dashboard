# 💳 Credit Card Financial Dashboard | Power BI Project

This project presents a comprehensive **Credit Card Financial Dashboard** built using **Power BI**, **SQL**, and **CSV datasets**. The goal is to analyze transaction and customer demographic data to extract actionable insights for business decisions in the credit card domain.

---

## 📌 Objective

- Build an interactive dashboard to analyze credit card revenue, usage patterns, and customer profiles.
- Identify revenue trends by expenditure type, card category, usage method, and demographics.
- Support data-driven decisions to improve customer engagement and financial performance.

---

## 📂 Dataset Overview

Two main datasets were used:

1. **`customer.csv`** – Contains customer demographics:
   - Age, Gender, Education, Marital Status
   - Income, Job Role, Loan, Car/House ownership

2. **`cust_add.csv`** – Contains credit card transaction and financial data:
   - Card category, Annual fees, Activation status
   - Transaction count, amount, credit limit, utilization ratio, and interest earned

These datasets were linked via a common key: `Client_Num`.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – For creating interactive dashboards
- **PostgreSQL** – For storing and querying structured data
- **SQL** – For data cleaning, transformation, and integration
- **Excel/CSV** – For raw data formatting

---

## 📊 Key Metrics Visualized

### 📈 Revenue & Transactions
- Revenue by Quarter (Q1–Q4)
- Revenue by Expenditure Type (Bills, Fuel, Travel, etc.)
- Revenue by Usage Method (Swipe, Chip, Online)
- Revenue and Transactions by Card Category

### 👥 Customer Demographics
- Revenue by Age Group, Gender, Education, Marital Status
- Income and Revenue by Customer Job
- Revenue by State and Dependent Count
- Customer Satisfaction Score distribution

---

## 🔍 Sample Insights

- **Blue Card** customers contributed the highest revenue (₹46M+).
- **Businessmen** generated the highest income and interest earnings.
- Highest revenue observed in **Q3 and Q4**.
- Most transactions occurred through **Swipe**, followed by **Chip**.

---

## 📑 Files Included

| File | Description |
|------|-------------|
| `customer.csv` | Customer demographics dataset |
| `cust_add.csv` | Credit card financial transactions dataset |
| `sqlquery.sql` | SQL script to create tables and import data |
| `Credit Card Customer Report.pdf` | Dashboard report: demographics-focused |
| `Credit Card Transition Report.pdf` | Dashboard report: transactions & card usage |

---

## 🚀 How to Run the Project

1. Create tables in PostgreSQL using `sqlquery.sql`.
2. Import `customer.csv` and `cust_add.csv` using the `COPY` command.
3. Connect Power BI to the PostgreSQL database.
4. Load data, clean and relate tables, and recreate visualizations as per the PDF dashboards.

---

## 📌 Future Enhancements

- Add predictive analytics for customer churn or fraud detection.
- Include drill-down reports for card category-wise trends.
- Build KPI cards for business performance monitoring.
