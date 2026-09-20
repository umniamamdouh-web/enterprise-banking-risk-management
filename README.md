# Enterprise Banking Risk Management Analytics

End-to-end banking credit risk analytics project using **SQL, Power BI, and Machine Learning** to monitor portfolio performance, analyze delinquency and default risk, evaluate collections, and identify high-risk loans for early intervention.

## Project Overview

This project provides a comprehensive analytical view of a banking loan portfolio, helping stakeholders understand portfolio performance, identify credit risk, monitor delinquency and defaults, evaluate collection efficiency, and prioritize high-risk accounts.

The solution follows an end-to-end analytics workflow from data preparation and modeling to interactive dashboards and predictive risk analysis.

## Business Objectives

- Monitor the overall loan portfolio and financial exposure.
- Identify delinquent and defaulted loans.
- Analyze risk concentration across products and branches.
- Evaluate collection and recovery performance.
- Detect high-risk loans before default occurs.
- Support data-driven credit risk and collection decisions.

## Tools & Technologies

- **SQL** — Data cleaning, transformation, and analytical data modeling
- **Power BI** — Data modeling, KPI development, visualization, and dashboard design
- **Python / Machine Learning** — Probability of default prediction and risk segmentation
- **Excel / CSV** — Data validation and supporting analysis

## Analytics Workflow

Data Sources → Data Preparation → Bronze Layer → Silver Layer → Gold Analytical Layer → Power BI Data Model → Dashboards → Machine Learning → Business Insights

## Power BI Dashboards

### 1. Portfolio Overview & Concentration
Provides an executive view of portfolio size, approved amounts, outstanding balances, product concentration, branch exposure, and portfolio growth.

### 2. Delinquency & Default Risk
Analyzes overdue loans, Days Past Due (DPD), default rates, default exposure, product-level risk, and branch risk concentration.

### 3. Risk Drivers & Early Warning
Identifies patterns and indicators associated with increasing credit risk and supports early intervention.

### 4. Collections & Recovery
Evaluates due amounts, paid amounts, collection rates, overdue accounts, payment performance, and recovery efficiency.

### 5. Predictive Risk & Customer Segmentation
Uses machine learning outputs to segment loans into risk categories and identify high-risk accounts requiring proactive monitoring.

## Key Portfolio Insights

- **Delinquency Rate:** 20.8%
- **Overdue Loans:** 6K
- **Total Overdue Amount:** 112.55M
- **Default Rate:** 8.57%
- **Defaulted Loans:** 2,572
- **Total Default Amount:** 1.39B
- **Collection Rate:** approximately 98.9%
- **High-Risk Loans:** 4,202
- **High-Risk Portfolio Share:** 14.01%
- **High-Risk Default Rate:** 31.65%

## Machine Learning

The predictive component estimates the **Probability of Default (PD)** and segments loans into:

- Low Risk
- Medium Risk
- High Risk

The objective is to move from reactive risk reporting toward proactive identification of loans requiring early intervention.

## Business Value

The solution enables stakeholders to:

- Detect emerging credit risk earlier.
- Prioritize collection activities.
- Monitor portfolio concentration.
- Identify high-risk loans.
- Compare risk across branches and loan products.
- Support more informed risk-management decisions.

## Repository Structure

```text
├── SQL/
├── PowerBI/
├── Machine-Learning/
├── Data/
├── Dashboard-Screenshots/
├── Presentation/
└── README.md
