# Analysis of Average Wages in European Union Countries

This project is a semestral project for **Practical Statistics** (BI-PRS) on **linear regression modeling**.

A statistical analysis and linear regression modeling project exploring the economic and demographic determinants of average monthly wages across European Union member states in 2015.

---

## 📌 Overview

The goal of this project is to analyze the distribution of average wages across EU countries, examine which economic and educational indicators influence wage levels, and construct an interpretable yet accurate linear regression model.

### Key Research Questions
1. How are average monthly wages distributed across EU member states, and which countries exhibit extreme values?
2. Which macroeconomic and demographic factors (GDP per capita, currency, tertiary education, and EU membership duration) correlate most strongly with wages?
3. What is the optimal regression model to approximate wage levels while satisfying classical regression assumptions?

---

## 📊 Datasets & Variables

Data was retrieved primarily from Eurostat (reference year 2015, covering 26 EU member states):
- **Average Monthly Wage** (`salary` [EUR]): Derived from Eurostat dataset `nama_10_fte` (converted from annual full-time equivalent wages).
- **GDP per Capita** (`gdp` [EUR/capita]): Eurostat dataset `tipsna40`.
- **Eurozone Membership** (`euro` [0/1]): Categorical indicator of whether the country uses the Euro or a national currency.
- **Tertiary Education** (`edu` [%]): Eurostat dataset `edat_lfse_03` (percentage of population aged 15–64 with ISCED 2011 levels 5–8 attainment).
- **EU Membership Length** (`in_eu` [years]): Number of years elapsed since the country joined the European Union (up to 2015).

---

## 🔬 Methodology & Modeling

1. Exploratory Data Analysis (EDA)
2. Correlation & Multicollinearity Diagnostics
3. Linear Regression Models
