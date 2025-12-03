# Alameda County Chronic Disease Analysis (2018-2022)

**Healthcare Data Analyst | 2.2M CDC Records | Live Dashboard**

## Overview
This project analyzes chronic disease patterns in Alameda County from 2018 to 2022 using CDC PLACES and SDOH datasets. The goal is to identify shift in metabolic health, quantify changes over time, and provide practical recommendations for publis health planning.

## LIVE DASHBOARD 
https://chliop.github.io/alameda-chronic-disease-dashboard/

## Key Findings
**Chi-square p<0.001**: Metabolic shift → cholesterol (32.5%) + hypertension (26.6%) dominate  
**Paired t-test p=0.706**: Overall burden stable  
**Key insight**: Prioritize metabolic screening clinics

## Interpretation
Metabolic risks increased in the county. Cholesterol and hypertension became dominant. Screening and prevention programs for metabolic health should be a priority. Obesity decreased but related risks increased. 

## Key Results Table
| Disease | 2018 | 2022 | Change |
|---------|------|------|--------|
| **High cholesterol** | - | **32.5%** | NEW |
| **Hypertension** | - | **26.6%** | NEW |
| **Obesity** | 24.6% | 20.1% | ↓4.5pp |

## Repository Structure
notebooks/

* 01_data_cleaning.ipynb (CDC PLACES → cleaned)

* 02_merge_data.ipynb (merged cleaned dataset + SDOH)

* 03_eda_chart.ipynb (exploratory data analysis)

*04_prevalence_analysis.ipynb (t-test, chi-sq, logistic regression)

docs/ 
* Chronic-Diseases-Report.pdf
  
## Recommendations
1. **Expand metabolic screening clinics.** 
2. **Add tract level SDOH modeling.**
3. **Add 2023 and 2024 trend updates**
4. **Buid quarterly reports for local health agencies.**

---
## Contact
**Healthcare analytics, dashboards, and reporting.**  
Emails: chliopham@gmail.com
