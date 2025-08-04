# Bank-Loan-Portfolio-Performance-Risk-Analysis
Interactive analytics project using SQL and Tableau to monitor bank loan performance. Visualizes KPIs, tracks trends, segments risk, and delivers actionable business insights for loan origination, funding, repayment, and portfolio health.



## Project Overview

A full-stack analytics solution for monitoring and assessing a bank's loan portfolio. Built with **SQL** for data extraction and **Tableau** for interactive dashboards, this project enables data-driven decision-making by tracking loan performance, identifying risks, and uncovering business trends.

> **Live Demo:** [View on Tableau Public](https://public.tableau.com/app/profile/surya.vamshi/viz/Bank_Loan_Project_17449475966680/Intro?publish=yes)

---

## 📊 Problem Statement

A bank needs to monitor loan origination, funding, and repayments. The goal:  
- **Track key KPIs** (applications, funded amount, collections, interest, DTI)
- **Classify loans** as Good (Fully Paid/Current) vs. Bad (Charged Off)
- **Visualize trends** over time, regions, loan purposes, borrower segments
- **Enable drill-down analysis** for risk, growth, and compliance.

---

## 🏗️ Solution Architecture

- **SQL**: Advanced queries for data wrangling, KPI calculation, MoM/MTD metrics
- **Tableau**: Dashboards for summary, trends, segmentation, and detail views

---

## 🔍 Key Features

- **Summary Dashboard:** Snapshot of KPIs and portfolio health
- **Overview Dashboard:** Trends by month, region, purpose, employment, home ownership
- **Details Dashboard:** Filterable loan-level analysis
- **Business Insights:** Actionable recommendations for risk and growth

---

## ⚙️ How It Works

1. **Data Extraction**:  
   - See [`sql/SQL_Outputs_For_Quality_Analysis.docx`](sql/SQL_Outputs_For_Quality_Analysis.pdf) for queries.
   - Source: [`data/financial_loan.csv`](data/financial_loan.csv)


2. **Interactive Dashboards**:  
   - Tableau workbook in `tableau/`
   - [View Demo](https://public.tableau.com/app/profile/surya.vamshi/viz/Bank_Loan_Project_17449475966680/Intro?publish=yes)

---

## 💡 Sample Insights

- Over **86%** of loans are classified as Good, indicating strong underwriting.
- Debt consolidation is the most common purpose but may carry higher risk.
- Longer-employed and homeowner borrowers have lower default rates.

---

## 👨‍💻 How to Run

1. Download the data and Tableau workbook.
2. Open `.twb(x)` file in Tableau Desktop or Public.
3. (Optional) Run SQL queries for custom metrics.


