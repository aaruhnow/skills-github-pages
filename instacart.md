---
title: "Instacart User Behavior Analysis"
layout: default
---

# Instacart User Behavior Analysis

---

##Introduction

Instacart is an online grocery service with strong sales performance. This analysis was conducted to uncover customer behavior patterns, support marketing segmentation, and guide strategic decisions.

**Goal:** Perform an initial data and exploratory analysis of Instacart’s customer and order data to derive insights and suggest segmentation strategies.  
**Role:** Data Analyst  
**Stakeholders:** CareerFoundry Instructor  
<a href="https://docs.google.com/spreadsheets/d/1UiZfDS4s-9FotKKrEzLuZkkWU9IT5qaX/edit?usp=drive_link&ouid=102883752544520383313&rtpof=true&sd=true" target="_blank">
  View Final Report
</a>

---

##Data & Skills

**Data Summary:**
- Final merged dataset: 32,434,489 rows and 33 columns
- Includes customer demographics, order history, product details, and regional groupings across the U.S.
- Data was merged and processed in Python

**Skills Used:**
- Python (Pandas, NumPy, Seaborn), Jupyter Notebook
- Merged and cleaned large datasets
- Created derived columns and grouped variables
- Generated visualizations and population-based summaries
- Final report created using Excel

---

##Project Planning

**Data Source:** Instacart’s open grocery order dataset  
**Tools Used:** Python (Pandas, NumPy, Seaborn), Jupyter Notebook

**Steps Taken:**
- Combined multiple CSVs (orders, products, departments, etc.)
- Cleaned and joined datasets to analyze customer behavior
- Explored order frequency, product popularity, and segmentation
- Visualized trends by day, hour, price range, and demographics
- Identified high-value opportunities for targeted marketing

---

##Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Large dataset (32M+ rows) | Used chunk loading and sampling in Pandas |
| Complex table relationships | Merged using product/order/customer IDs |
| Difficult-to-spot segments | Grouped by behavior (cart size, order time, income) |

---

##Key Insights

###Order Timing Patterns

<a href="/images/instacart-busiest-days.png" target="_blank">
  <img src="/images/instacart-busiest-days.png" alt="Busiest Days" style="max-width:100%; height:auto;">
</a>

<a href="/images/instacart-busiest-times.png" target="_blank">
  <img src="/images/instacart-busiest-times.png" alt="Busiest Times" style="max-width:100%; height:auto;">
</a>

**Insights:**
- Saturday is the busiest day; Sunday and Friday follow
- Peak hours are 10 a.m. (10:00) to 4 p.m. (16:00); slowest are 12 a.m. (00:00) to 5 a.m. (05:00)

---

###Price Sensitivity

<a href="/images/instacart-price-hour-day.png" target="_blank">
  <img src="/images/instacart-price-hour-day.png" alt="Price by Hour" style="max-width:100%; height:auto;">
</a>

<a href="/images/instacart-price-frequency.png" target="_blank">
  <img src="/images/instacart-price-frequency.png" alt="Price Frequency" style="max-width:100%; height:auto;">
</a>

**Insights:**
- Most products purchased are under $15
- Price is highest 3–4 a.m., lowest around 9–10 a.m.

---

###Customer Demographics

<a href="/images/instacart-age.png" target="_blank">
  <img src="/images/instacart-age.png" alt="Age vs Income" style="max-width:100%; height:auto;">
</a>

<a href="/images/instacart-family-status.png" target="_blank">
  <img src="/images/instacart-family-status.png" alt="Family Status & Age" style="max-width:100%; height:auto;">
</a>

**Insights:**
- Higher incomes observed in customers over 40
- Most users are married, especially in adult/middle-age/senior brackets

---

##Conclusions & Recommendations

**Sales & Marketing Insights – Instacart**

**Timing Strategy:**
- Avoid outreach during peak hours (9 a.m.–4 p.m. Sat–Sun)
- Target quieter periods (Tues–Wed, outside 9–4)
- Promote high-value items during peak spending windows: 2–4 a.m. and 9–11 p.m., especially weekends

**Pricing Insights:**
- Most purchases are under $15. Suggested price brackets:
  - $0–5
  - $5–10
  - $10–15

**Target Demographics:**
- **Income:** Focus premium campaigns on $100K–$300K earners; higher spenders are often 40+  
- **Family:** Target adults managing dependents (under 20 or over 60)  
- **Marital Status:** Prioritize campaigns for married, senior, and adult customers

---

