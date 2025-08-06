# Bank-Loan-Portfolio-Performance-Risk-Analysis
Interactive analytics project using SQL and Tableau to monitor bank loan performance. Visualizes KPIs, tracks trends, segments risk, and delivers actionable business insights for loan origination, funding, repayment, and portfolio health.



## Project Overview

A full-stack analytics solution for monitoring and assessing a bank's loan portfolio. Built with **SQL** for data extraction and **Tableau** for interactive dashboards, this project enables data-driven decision-making by tracking loan performance, identifying risks, and uncovering business trends.

> **Live Demo:** [View on Tableau Public](https://public.tableau.com/app/profile/surya.vamshi/viz/Bank_Loan_Project_17449475966680/Intro?publish=yes)

---

## Problem Statement

A bank needs to monitor loan origination, funding, and repayments. The goal:  
- **Track key KPIs** (applications, funded amount, collections, interest, DTI)
- **Classify loans** as Good (Fully Paid/Current) vs. Bad (Charged Off)
- **Visualize trends** over time, regions, loan purposes, borrower segments
- **Enable drill-down analysis** for risk, growth, and compliance.

---

## Solution Architecture

- **SQL**: Advanced queries for data wrangling, KPI calculation, MoM/MTD metrics
- **Tableau**: Dashboards for summary, trends, segmentation, and detail views

---

## Objectives 

Objectives of Each Dashboard

1. Summary Dashboard:
To provide an at-a-glance overview of the bank’s lending portfolio, including total loan applications, funded and received amounts, interest rates, and the overall distribution of good and bad loans. This helps decision-makers quickly assess portfolio health and recent performance trends.

2. Overview Dashboard:
To break down loan performance and funding trends by different segments—such as state, loan purpose, employee length, and home ownership. This dashboard uncovers patterns and highlights growth opportunities or emerging risks across borrower demographics and regions.

3. Details Dashboard:
To enable granular analysis of individual loan records with comprehensive filters. This dashboard supports deep dives into specific loans, facilitating validation, audit, or in-depth risk analysis at the transaction level.

4. Business Insights: Actionable recommendations for risk and growth

---

## Data Description
Our analysis is based on a comprehensive loan dataset capturing multiple facets of lending operations:

1. Loan Application Details:
Includes information on each loan request, such as application date, purpose, requested amount, and borrower employment details. Analyzing these records helps us track lending demand, applicant profiles, and overall portfolio growth.

2. Borrower Attributes:
Captures borrower demographics and risk factors, including home ownership status, employment length, and debt-to-income (DTI) ratio. These features are essential for profiling creditworthiness and predicting default risks.

3. Loan Performance Metrics:
Tracks key figures for every loan—funded amount, total amount received, interest rate, monthly installment, and loan term. These data points allow us to evaluate loan performance, calculate repayments, and monitor cash flow.

4. Loan Status and Repayment Outcomes:
Records the current status of each loan (e.g., fully paid, current, charged off) and payment history. This enables assessment of portfolio health, identification of high-risk or delinquent loans, and insights into repayment behaviors.

5. Geographic and Segment Data:
Includes information such as borrower state and loan purpose, supporting regional analysis and segmentation by loan type. This helps identify market trends, growth opportunities, and regional risk concentrations.

---

## How It Works

1. **Data Extraction**:  
   - See [`sql/SQL_Outputs_For_Quality_Analysis.docx`](sql/SQL_Outputs_For_Quality_Analysis.pdf) for queries.
   - Source: [`data/financial_loan.csv`](data/financial_loan.csv)


2. **Interactive Dashboards**:  
   - Tableau workbook in `tableau/`
   - [View Demo](https://public.tableau.com/app/profile/surya.vamshi/viz/Bank_Loan_Project_17449475966680/Intro?publish=yes)

---

## Sample Insights

- Over **86%** of loans are classified as Good, indicating strong underwriting.
- Debt consolidation is the most common purpose but may carry higher risk.
- Longer-employed and homeowner borrowers have lower default rates.

---

## How to Run

1. Download the data and Tableau workbook.
2. Open `.twb(x)` file in Tableau Desktop or Public.
3. (Optional) Run SQL queries for custom metrics.


