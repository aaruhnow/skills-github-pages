---
title: Citi Bike Strategy Case Study
---

# Citi Bike Strategy Dashboard – Case Study

## 📌 Project Overview

Citi Bike users often face bike shortages during certain times and locations. This case study explores key data-driven insights to address availability gaps and guide expansion efforts.

**Role:** Data Analyst  
**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Kepler.gl, Streamlit  
**Data Sources:** Citi Bike API, NOAA Weather API (New York, 2022)  

➡️ [Launch Interactive Dashboard](https://citibike-fmhbftchuaccupm3umqrwa.streamlit.app/){:target="_blank"}

---

## 🎯 Objectives

- Identify high-demand stations and usage trends
- Understand weather’s impact on ridership
- Locate underused and underserved areas
- Recommend redistribution strategies and expansion zones

---

## 📊 Visualizations

### 1. Most Popular Stations
Bar chart showing top 20 bike stations with seasonal filtering.  
**Insight:** High-demand stations clustered near major avenues, parks, and transit hubs — especially in Central and Lower Manhattan.

### 2. Monthly Trends + Weather Correlation
Dual-axis line chart comparing trip volume and average temperature.  
**Insight:** Ridership peaks from May–October and declines with colder weather. Weather significantly influences usage.

### 3. Trip Density & Station Distribution
Geospatial heatmaps and distribution maps using Kepler.gl.  
**Insight:** Central Manhattan, Jersey City, and Brooklyn show high traffic; Northern Manhattan shows potential service gaps.

---

## 🧩 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Extra records from 2021/2023 | Filtered by date in Python to isolate 2022 data |
| Temperature conversion errors | Corrected Celsius-to-Fahrenheit formula |
| Incorrect geospatial plotting | Verified and corrected latitude/longitude mapping |
| Large dashboard file size | Filtered out low-frequency trips (under 65) to reduce size |

---

## ✅ Conclusions & Recommendations

- **Seasonal Optimization:** Reduce bike inventory 20–30% in winter; use weather data for demand forecasting.
- **Redistribution:** Balance bike supply in high-traffic areas using predictive models.
- **Expansion Opportunities:** Add capacity near parks, waterfronts, and underserved areas in Northern Manhattan and outer boroughs.

---
