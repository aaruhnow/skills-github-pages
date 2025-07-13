---
title: "World Happiness Report Analysis"
layout: default
---

# World Happiness Report Analysis

---

## Introduction

The World Happiness Report ranks over 150 countries by how happy their citizens perceive themselves to be. This project explores trends from 2015–2019 to uncover which social, economic, and political factors are most closely associated with national happiness.

The goal was to support policy evaluation and regional recommendations by identifying the strongest contributors to happiness and understanding global disparities.

---

## Data and Skills

**Data Sources:**
- World Happiness Reports (2015–2019)
- Over 780 rows of merged, multi-year data
- Key fields: GDP, Social Support, Life Expectancy, Freedom, Trust, Generosity, and Happiness Score

**Skills and Tools Used:**
- Python and Pandas: Data cleaning, merging, and correlation analysis  
- Jupyter Notebook: Exploratory analysis and plotting  
- Tableau: Geospatial and interactive dashboard  
- Excel: Initial inspection and formatting

---

## Project Planning

1. Merge and clean data across five years  
2. Explore trends over time and by region  
3. Identify key happiness drivers using correlation and clustering  
4. Segment countries using unsupervised learning  
5. Share findings through dashboard and visual storytelling

---

## Challenges and Solutions

| Challenge | Solution |
|----------|----------|
| Inconsistent column names and missing values | Standardized columns and used `.fillna()` and `.dropna()` |
| Difficulty comparing across years due to score scale shifts | Normalized values and created year-agnostic trends |
| Multicollinearity among factors | Used pairplots and scatter matrices to explore overlap |
| Tableau import failed initially | Cleaned dataset in Excel and exported as `.csv` |

---

## Geospatial Analysis

**Key Insights:**
- Nordic countries (Finland, Denmark, Norway) rank highest in happiness.
- Sub-Saharan Africa, parts of South Asia, and the Middle East rank lowest.
- The U.S. and Eastern Europe show moderate scores, reflecting mixed results.

<a href="/images/happiness-map.png" target="_blank">
  <img src="/images/happiness-map.png" alt="Geospatial Map" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_map.png" target="_blank">
  <img src="/images/World_Happiness_map.png" alt="Folium World Map with Happiness Ranks" style="max-width:100%; height:auto;">
</a>

---

## Correlation Heatmap

**Key Insights:**
- Happiness Score and Rank show a near-perfect negative correlation (-0.99).
- Economy (GDP), Family (support), and Health (life expectancy) show the strongest positive correlations with happiness.
- Freedom, Trust, and Generosity have weaker correlations, suggesting supporting rather than primary effects.

<a href="/images/happiness-heatmap.png" target="_blank">
  <img src="/images/happiness-heatmap.png" alt="Correlation Heatmap" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Heatmap.png" target="_blank">
  <img src="/images/World_Happiness_Heatmap.png" alt="Correlation Table + Heatmap" style="max-width:100%; height:auto;">
</a>

---

## Cluster Analysis: Strong Factors

**Key Factors:**  
- Economy (GDP per Capita)  
- Health (Life Expectancy)  
- Family (Social Support)  

**Key Insights:**
- These factors had the highest correlation with happiness.
- Financial, physical, and emotional security are key to life satisfaction.

<a href="/images/happiness-cluster-strong.png" target="_blank">
  <img src="/images/happiness-cluster-strong.png" alt="Cluster: Strong Factors" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Economy.png" target="_blank">
  <img src="/images/World_Happiness_Economy.png" alt="Happiness Score vs GDP per Capita" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Health.png" target="_blank">
  <img src="/images/World_Happiness_Health.png" alt="Happiness Score vs Life Expectancy" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Family.png" target="_blank">
  <img src="/images/World_Happiness_Family.png" alt="Happiness Score vs Family Support" style="max-width:100%; height:auto;">
</a>

---

## Cluster Analysis: Supporting Factors

**Key Factors:**  
- Freedom  
- Generosity  
- Trust in Government  

**Key Insights:**
- These factors may enhance well-being when paired with core factors.
- Their impact alone is not strong but may help improve scores in already-stable countries.

<a href="/images/happiness-cluster-weak.png" target="_blank">
  <img src="/images/happiness-cluster-weak.png" alt="Cluster: Supporting Factors" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Freedom.png" target="_blank">
  <img src="/images/World_Happiness_Freedom.png" alt="Happiness Score vs Freedom" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Generosity.png" target="_blank">
  <img src="/images/World_Happiness_Generosity.png" alt="Happiness Score vs Generosity" style="max-width:100%; height:auto;">
</a>

<a href="/images/World_Happiness_Corruption.png" target="_blank">
  <img src="/images/World_Happiness_Corruption.png" alt="Happiness Score vs Trust in Government" style="max-width:100%; height:auto;">
</a>

---

## Interactive Tableau Report

<a href="https://public.tableau.com/views/WorldHappinessReport2015-2019_17177049296500/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank">
  View Tableau Report
</a>

---

## Conclusions and Recommendations

**Summary:**
- Economy, Family, and Health are the top drivers of happiness.
- Freedom, Trust, and Generosity act as supporting contributors.
- Improving economic conditions, social services, and access to healthcare will raise national happiness.

**Recommendations:**
- Prioritize investments in healthcare and job growth.
- Improve community and family support systems.
- Use global leaders (e.g., Nordic countries) as models for policy-making.

---
