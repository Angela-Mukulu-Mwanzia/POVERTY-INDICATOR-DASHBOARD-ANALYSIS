# POVERTY-INDICATOR-DASHBOARD-ANALYSIS
Interactive Power BI dashboard analyzing 30+ years of global poverty trends, demographic shifts, and economic growth contributions. Features dynamic cross-filtering, drill-down capabilities, and actionable insights into a critical -59.82% economic indicator decline.

# 📊 Poverty Indicator Dashboard

## 📌 Overview
This repository contains an interactive data visualization dashboard built to analyze a key **Poverty Indicator** across multiple decades (1960–1990). The dashboard dissects the metric by **Sex**, **Age Group**, and **Country** to uncover underlying demographic and economic vulnerabilities. It highlights a severe -59.82% change over the 10-year period, providing policymakers and analysts with a granular view of the crisis.

## 🎯 Objective
- Track the drastic decline from **132.13T** (First 10 Years) down to **137bn** (Sum of Index).
- Identify which demographics (gender/age) are bearing the heaviest burden.
- Analyze contribution to growth (Increases vs. Decreases) by country and sex.
- Provide a user-friendly interface for deep-dive analysis via interactive features.

## ✨ Key Interactive Features
The dashboard is built for exploration, featuring:
1.  **Slicers (Filters)**: Filter the entire report dynamically using:
    - **Country** (from the `COUNTRY AND CODE` field).
    - **Sex** (Total, Male, Female).
    - **Age Group** (e.g., Y15T64, Y01T14, Y65+).
2.  **Drill-Down Functionality**: Click on the "Population by Sex (1960-1980)" visual to drill down from **Year** to **Sex** for granular historical analysis.
3.  **Cross-Filtering**: Click on any data point (e.g., the "Male" segment in the 2020 Sex Breakdown) to instantly filter all other visuals on the page—showcasing the correlation between gender, age, and total index value.

## 🖥️ Dashboard Components (Visuals)

| Visual | Description | Key Takeaway |
| :--- | :--- | :--- |
| **Top KPIs** | High-level cards showing the Sum of Index, Historical total, and % change. | Current Index is **137bn** vs. **132.13T** historically. |
| **Population by Sex (1960-1980)** | Trend analysis showing the percentage distribution of the indicator by Sex over three decades. | Female share jumped from **~26.94%** (1960) to **~40.09%** (1970). |
| **Sex Breakdown (2020)** | Current snapshot of the indicator split by Total, Male, and Female. | Total value stands at **263.42bn**. |
| **Top 5 Age Groups (1st 10 Yrs)** | Bar chart highlighting the age cohorts with the highest cumulative indicator values. | **Y15T64 (Working Age)** dominates at **25T**, followed by **Y01T14 (Children)** at **17T**. |
| **Top 5 Country Contributions** | Treemap or bar chart showing countries with the highest Increases and Decreases in the indicator. | Both sexes contributed **400T** to growth increases, but Males contributed **171T** vs. Females **79T**. |
| **1990 Data Comparison** | Supplementary view of age groups specific to the year 1990. | 15-64 age group held the highest share at **0.03T**. |

<img width="888" height="497" alt="Screenshot 2026-06-27 231445" src="https://github.com/user-attachments/assets/8e1a2caa-ce52-4350-a830-19401bf1ace3" />


## 🔍 Key Business & Policy Insights
1.  **Severe Economic Contraction**: The -59.82% change coupled with the drop to 137bn indicates a structural breakdown in the measured economy/welfare, requiring urgent macroeconomic stabilization.
2.  **Gender Disparity in Growth**: Male contributions to Increases (171T) vastly outpace Female contributions (79T). However, Males also account for a larger share of Decreases (79T vs 32T), suggesting males are more exposed to economic volatility.
3.  **Working-Age Crisis**: The "Top 5 Age Groups" clearly shows that the 15-64 demographic (25T) is the primary driver of the poverty metric, implying that labor market conditions and employment stability are the root causes of the overall decline.

## 🛠️ Technology Stack
- **Visualization Tool**: Microsoft Power BI Desktop (or Tableau if applicable)
- **Data Processing**: Excel / CSV (Data connection required)
- **Languages**: DAX (Measures), M (Power Query)

## 📁 Repository Structure
