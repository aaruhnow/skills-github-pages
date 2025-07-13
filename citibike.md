---
title: Citi Bike Strategy Case Study
---

## Project Overview

Citi Bike users often face bike shortages during certain times and locations. This case study explores key data-driven insights to address availability gaps and guide expansion efforts.

**Role:** Data Analyst  
**Tools Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, Kepler.gl, Streamlit  
**Data Sources:** Citi Bike API, NOAA Weather API (New York, 2022)  

[Launch Interactive Dashboard](https://citibike-fmhbftchuaccupm3umqrwa.streamlit.app/){:target="_blank"}

---

## Objectives

- Identify high-demand stations and usage trends
- Understand weather’s impact on ridership
- Locate underused and underserved areas
- Recommend redistribution strategies and expansion zones

---

## Visualizations

### 1. Most Popular Stations

Bar chart showing the top 20 most-used Citi Bike stations in NYC, highlighting hotspots near major avenues, parks, and transit hubs.

<a href="images/Top_20_most_popular_stations.png" target="_blank">
  <img src="images/Top_20_most_popular_stations.png" alt="Top 20 Most Popular Stations" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 1: Top 20 most popular Citi Bike stations in NYC.</p>

<a href="images/Citibike_Top_20_png.png" target="_blank">
  <img src="images/Citibike_Top_20_png.png" alt="Top 20 Start Stations Annotated" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 1b: Annotated version with numeric bar labels and enhanced formatting.</p>

---

### 2. Monthly Trends and Weather Correlation

Dual-axis chart comparing trip volume with daily average temperature to understand how weather impacts ridership.

<a href="images/Weather_and_bike_usage.png" target="_blank">
  <img src="images/Weather_and_bike_usage.png" alt="Weather and Bike Usage" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 2: Seasonal bike usage trends vs. average temperature.</p>

<a href="images/Citibike_duel_axis_1.png" target="_blank">
  <img src="images/Citibike_duel_axis_1.png" alt="Dual-Axis Setup Chart" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 2b: Dual-axis plot showing bike rides and temperature with labeled axes and date formatting.</p>

<a href="images/Citibike_duel_axis_2.png" target="_blank">
  <img src="images/Citibike_duel_axis_2.png" alt="Dual-Axis Annotated Chart" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 2c: Annotated version highlighting peak summer ridership and coldest days.</p>

---

### 3. Trip Density and Station Distribution

Kepler.gl map showing ride density and station placement across NYC, revealing underserved and high-demand areas.

<a href="images/Aggregated_bike_trips_in_NY.png" target="_blank">
  <img src="images/Aggregated_bike_trips_in_NY.png" alt="Aggregated Bike Trips in NY" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 3: Interactive map showing aggregated bike trips in New York City.</p>

<a href="images/Citibike_kepler.gl.png" target="_blank">
  <img src="images/Citibike_kepler.gl.png" alt="Kepler.gl Map Config Screenshot" width="80%">
</a>
<p style="text-align: center; font-style: italic;">Figure 3b: Python code-driven Kepler.gl map setup showing default zoom, coordinates, and configuration for NYC.</p>

---

## Challenges and Solutions

| Challenge | Solution |
|----------|----------|
| Extra records from 2021/2023 | Filtered by date in Python to isolate 2022 data |
| Temperature conversion errors | Corrected Celsius-to-Fahrenheit formula |
| Incorrect geospatial plotting | Verified and corrected latitude/longitude mapping |
| Large dashboard file size | Filtered out low-frequency trips (under 65) to reduce size |

---

## Conclusions and Recommendations

- Seasonal Optimization: Reduce bike inventory by 20–30% in winter months. Use weather forecasts for dynamic inventory adjustments.
- Redistribution: Balance bike supply in high-traffic areas based on historical demand using predictive modeling.
- Expansion Opportunities: Increase capacity near parks, waterfronts, and underserved areas such as Northern Manhattan and parts of Brooklyn and Queens.

---

