# Alameda County Chronic Disease Analysis (2018-2022)

**Healthcare Data Analyst | 2.2M CDC Records | Live Dashboard**

## Executive Summary
**Chi-square p<0.001**: Metabolic shift → cholesterol (32.5%) + hypertension (26.6%) dominate  
**Paired t-test p=0.706**: Overall burden stable  
**Key insight**: Prioritize metabolic screening clinics

## LIVE DASHBOARD 
(https://chliop.github.io/alameda-chronic-disease-dashboard/)

## Full Analysis Pipeline
notebooks/

├── 01_data_cleaning.ipynb (CDC PLACES → cleaned)

├── 02_merge_data.ipynb (merged cleaned dataset + SDOH)

├── 03_eda_chart.ipynb (exploratory data analysis)

└── 04_prevalence_analysis.ipynb (t-test, chi-sq, logistic regression)

docs/ Chronic-Diseases-Report.pdf

## Key Results Table
| Disease | 2018 | 2022 | Change |
|---------|------|------|--------|
| **High cholesterol** | - | **32.5%** | NEW |
| **Hypertension** | - | **26.6%** | NEW |
| **Obesity** | 24.6% | 20.1% | ↓4.5pp |

## Recommendations
1. **Metabolic health clinics** (cholesterol + hypertension)
2. **Tract-level SDOH analysis**
3. **Longitudinal 2023-2024 tracking**

---
**Freelance: Healthcare data analysis + interactive dashboards**  
 Upwork | Fiverr | chliopham@gmail.com
