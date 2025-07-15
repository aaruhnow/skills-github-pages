---
title: "Summit Bank Customer Retention Analysis"
layout: default
---

# Summit Bank Customer Retention Analysis

---

## Project Overview

In this solo project, I stepped into the role of a sales data analyst at **Summit Bank** to identify the key factors that drive customer churn. Using historical client data and Excel-based data mining techniques, the goal was to support the bank’s customer retention strategy.

**Objective:**  
Uncover risk indicators that predict whether a customer will leave the bank, and model them in a decision tree.

---

## Tools & Techniques

- Microsoft Excel (formulas, pivot tables)
- Data quality checks & cleaning
- Descriptive statistics
- Customer segmentation
- Decision tree modeling

---

## Methodology

- **Data Quality Review:**  
  Assessed 991 client records for missing or inconsistent values. Cleaned fields including credit score, tenure, and account balance.

- **Segmentation:**  
  Split data into two groups:
  - **Exited Customers:** (`ExitedFromBank = 1`)
  - **Active Customers:** (`ExitedFromBank = 0`)

- **Descriptive Statistics:**  
  Analyzed patterns by country, gender, credit score band, product count, and estimated salary.

- **Top Risk Factors Identified:**
  - Inactive customer status (70% of churned clients)
  - Short tenure (under 2 years)
  - High account balance with low product count
  - Poor credit score (under 580)

- **Decision Tree Model:**  
  Designed a simple decision tree prioritizing the most predictive features, with `IsActiveMember = 0` at the root node.

---

## Key Insights

- **Customer activity** was the strongest predictor of churn: inactive users had double the churn rate.
- Customers with a **high balance but few products** are more likely to leave.
- Credit score and tenure also showed strong churn correlations.
- Retention strategies should focus on re-engaging **inactive, high-value customers** early.

---

## File Access

You can view the full workbook here:  
[**Open Summit Bank Analysis (Google Sheets)**](https://docs.google.com/spreadsheets/d/1XeS4H0yDwuiVj2NCoZTfAk1meX5ReLqQ/edit?usp=drive_link&ouid=102883752544520383313&rtpof=true&sd=true){:target="_blank"}

---

## Skills Demonstrated

- Exploratory data analysis (EDA)
- Data cleaning and integrity checks
- Churn segmentation logic
- Decision tree modeling and prioritization
- Visual storytelling through pivot tables

---
