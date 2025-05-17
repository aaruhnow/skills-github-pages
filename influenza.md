---
title: Influenza Season Staffing Plan
---

<!-- Meta tag for SEO -->
<meta name="description" content="Data-driven staffing strategy for U.S. hospitals during flu season, using CDC and Census data to forecast influenza trends and guide medical resource allocation.">

# Influenza Season Staffing Plan

## Introduction

**Project Overview:**  
The United States has an influenza season where more people than usual suffer from the flu. Some people, particularly those in vulnerable populations, develop serious complications and end up in the hospital. Hospitals and clinics need additional staff to adequately treat these extra patients. The medical staffing agency provides this temporary staff. The agency covers all hospitals in each of the 50 states, and the project will plan for the upcoming influenza season.

**Goal:**  
Determine when to send staff, and how many, to each state.

**Role:** Data Analyst  
**Stakeholders:** Hospitals and medical clinics

---

## Data & Skills

**Data:**  
- 452 rows × 36 columns  
- Time period: 2009–2017  
- Region: United States  
- Sources: CDC & U.S. Census Bureau  
- Datasets: Influenza deaths by geography, population data by geography, time, age, and gender

**Skills:**  
- Excel  
- Interpreted Business Requirements  
- Data Sourcing, Profiling, and Cleaning  
- Hypothesis Testing  
- Visual Analysis and Forecasting  
- Tableau Storyboarding  
- Stakeholder Communication

---

## Project Planning

**Data Sources:**  
- CDC Wonder (Influenza and Pneumonia Death Rates)  
- U.S. Census Bureau (Population Demographics)

**Tools Used:** Excel (data merging and pivoting), Tableau (visualization)

**Steps Taken:**  
- Downloaded and merged flu mortality data with population estimates  
- Cleaned and reformatted data for consistency across years and categories  
- Created calculated fields for death rates per 100,000 people  
- Used pivot tables to analyze geographic, age, and gender-based trends  
- Built dashboards in Tableau to highlight high-risk areas

---

## Influenza Analysis – Trends Over Time

This visualization shows influenza death trends by U.S. state from 2009–2017.  
Deaths have remained consistent by state, and forecasts indicate this trend will continue into 2018–2019.

<a href="/images/influenza-deaths-by-year.png" target="_blank"><img src="/images/influenza-deaths-by-year.png" alt="Deaths by year" width="600"></a>  
<a href="/images/influenza-deaths-state-year.png" target="_blank"><img src="/images/influenza-deaths-state-year.png" alt="Deaths by state and year" width="600"></a>

---

## Influenza Analysis – Elderly Population

People over age 65 are considered high-risk and have higher mortality rates from influenza.  
States with larger elderly populations show more flu-related deaths and should be prioritized.

<a href="/images/influenza-avg-deaths-state.png" target="_blank"><img src="/images/influenza-avg-deaths-state.png" alt="Average deaths by state and age group" width="600"></a>  
<a href="/images/influenza-65+-population.png" target="_blank"><img src="/images/influenza-65+-population.png" alt="Elderly population map" width="600"></a>

---

## Challenges and Solutions

**Mismatched Data Granularity:**  
Mortality and population datasets used different region/age groupings  
**Solution:** Standardized groupings and aligned categories

**Data Formatting Issues:**  
Date inconsistencies and missing values  
**Solution:** Cleaned/standardized formats prior to merging

**Calculating Accurate Death Rates:**  
Raw death counts lacked context  
**Solution:** Used normalized rates per 100,000 population

---

## Recommendations

The 15 states with High and Medium need should be prioritized for staffing in December–March.

<a href="/images/influenza-level-of-need-by-state.png" target="_blank"><img src="/images/influenza-level-of-need-by-state.png" alt="Level of Need by State" width="600"></a>

- **High Need States:** California, Texas, Illinois, Florida, Pennsylvania, New York  
- **Medium Need States:** Missouri, Georgia, Tennessee, North Carolina, Virginia, Ohio, Michigan, New Jersey, Massachusetts

Flu vaccination and staffing policies should target these regions.

---

## View Final Tableau Dashboard

<a href="https://public.tableau.com/views/Exercise2_9StorytellingwithDataPresentationsAR/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link" target="_blank" rel="noopener noreferrer">View Final Tableau Dashboard</a>
