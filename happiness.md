---
title: "World Happiness Report Analysis"
layout: default
---

# World Happiness Report Analysis

Analyzed data from 2015–2019 to uncover what drives happiness across the globe. The project explored six key contributing factors using Python, Tableau, and machine learning techniques.

---

##Geospatial Analysis

**Key Insights:**
- Nordic countries (Finland, Denmark, Norway) rank highest in happiness.
- Sub-Saharan Africa, parts of South Asia, and the Middle East rank lowest.
- The U.S. and Eastern Europe show moderate scores, reflecting mixed results.

![Geospatial Map](/images/happiness-map.png)

---

##Correlation Heatmap

**Key Insights:**
- Happiness Score and Rank show a near-perfect negative correlation (-0.99).
- Economy (GDP), Family (support), and Health (life expectancy) show the strongest positive correlations with happiness.
- Freedom, Trust, and Generosity have weaker correlations, suggesting supporting rather than primary effects.

![Correlation Heatmap](/images/happiness-heatmap.png)

---

##Cluster Analysis: Core Factors

**Key Factors:**  
- **Economy (GDP per Capita)**: Financial stability links closely to happiness.  
- **Health (Life Expectancy)**: Longer life expectancy is tied to higher happiness.  
- **Family (Social Support)**: Strong interpersonal relationships boost well-being.

**Key Insights:**
- These factors had the highest correlation with happiness.
- Financial, physical, and emotional security are key to life satisfaction.

![Cluster 1 - GDP, Health, Family](/images/happiness-cluster-core.png)

---

##Cluster Analysis: Supporting Factors

**Key Factors:**  
- **Freedom**: Mild positive correlation with happiness.  
- **Generosity**: Very weak correlation.  
- **Trust in Government**: Weak but positive trend.

**Key Insights:**
- These factors may enhance well-being when paired with core factors.
- Their impact alone is not strong but may help improve scores in already-stable countries.

![Cluster 2 - Freedom, Generosity, Trust](/images/happiness-cluster-support.png)

---

##Conclusions & Recommendations

**Summary:**
- Economy, Family, and Health are the top drivers of happiness.
- Freedom, Trust, and Generosity act as supporting contributors.
- Improving economic conditions, social services, and access to healthcare will raise national happiness.

**Recommendations:**
- Invest in job growth, healthcare, and community services.
- Target support in regions with low GDP and life expectancy.

[View Tableau Dashboard](https://public.tableau.com/)  
*Replace with your live dashboard link.*

---

