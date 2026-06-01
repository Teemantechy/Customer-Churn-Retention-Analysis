# Global Customer Churn & Retention Analysis

### 📊 Live Interactive Dashboard: [View on Tableau Public](https://public.tableau.com/app/profile/taiwo.adigun/viz/GlobalCustomerChurnRetentionAnalysis/GlobalCustomerChurnRetentionAnalysis)

## Project Overview
This project is an end-to-end data analytics pipeline designed to identify business vulnerabilities and quantify wealth drain within a banking customer base of 10,000 individuals. 

The objective was to move beyond simple aggregate reporting and build a dynamic business intelligence tool that allows regional managers and executives to isolate churn drivers by geography, age, and financial standing.

## Technical Stack
* **Database Management:** MySQL (Data extraction, cleaning, and transformation)
* **Business Intelligence:** Tableau (Calculated fields, dual-axis charts, geospatial mapping, interactive filtering)

## Key Business Insights Discovered
1. **Geographic Risk:** Identified a severe, localized bleed in the European market, with Germany exhibiting a 32.46% churn rate—double the attrition rate of neighboring regions (France and Spain).
2. **Demographic Vulnerability:** Dual-axis analysis revealed a critical retention failure among the 50+ age demographic, with female customer churn spiking to over 60% in specific brackets.
3. **The Wealth Drain:** Scatter plot visualization exposed that the bank is not just losing low-tier accounts; there is a massive, proportional loss of high-value customers (Credit Scores 800+, Estimated Salaries $150k+), representing a highly concerning $185M+ total balance lost.

## Process & Methodology
* **Data Engineering:** Processed raw tabular data to standardize categorical variables and resolve data inconsistencies, ensuring bulletproof logic for front-end visualization.
* **Metric Calculation:** Bypassed standard sheet filters in Tableau to construct independent, executive-level KPI calculated fields (Total Customers, Overall Churn Rate, Total Balance Lost) to ensure accurate denominator scaling across the dashboard.
* **Dashboard Construction:** Engineered a fully interactive, four-panel executive dashboard utilizing a central Geographic Risk Matrix as a master action filter, allowing for instantaneous, granular cohort analysis.# Customer-Churn-Retention-Analysis
