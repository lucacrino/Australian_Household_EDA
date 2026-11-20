# 🏠 Australian Household Exploratory Data Analysis
![Python](https://img.shields.io/badge/Python-3.13.9-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.1.3-013243?style=flat-square&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-4C72B0?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.0-11557C?style=flat-square)



## Table of Contents
- [Business Problem](#business-prolem)
- [Repository Structure](#repository-structure)
- [Notebook Overview](#notebook-overview)
- [Tools & Libraries](#tools)


---

<a id="business-prolem"></a>

## 📌 Business Problem
Between May 2022 and late 2023, the Reserve Bank of Australia raised interest rates 13 consecutive times — the sharpest tightening cycle in decades — while cost-of-living pressures accelerated across utilities, insurance and everyday expenses.
> **Which Australian households were under the most financial stress, what drove it and where is it heading by 2029?**
This project builds a composite Financial Stress Score (0–100) across 5,000 synthetic Australian households observed quarterly from Q1 2022 to Q4 2026, then projects the trajectory forward to 2029 using NumPy polynomial fitting — entirely in Pandas and NumPy, no Machine Learning libraries.
---


<a id="repository-structure"></a>

## 📂 Repository Structure
```
├── aus_financial_stress_analysis.ipynb   # Main analysis notebook
├── analysis_report.html                  # Data overview
├── data
│   └── au_household_financial_stress.csv
├── requirements.txt
└── README.md
```



---

<a id="notebook-overview"></a>

## 📊 Notebook Overview

The analysis follows a single linear notebook (`aus_financial_stress_analysis.ipynb`), structured as follows:

| Section | Focus |
|-------|------|
| 0. Setup & Imports | Library imports, display settings |
| 1. Data Loading & Quality Checks | Shape validation, missing values, dtype checks | 
| 2. Financial Stress Score — Distribution | National distribution, stress bands | 
| 3. Stress Trends Over Time (2022–2026) | Quarterly trend, RBA rate hike annotations | 
| 4. State-Level Heatmap | Stress by state & quarter | 
| 5. Segment Analysis |	Breakdown by household type, age, employment | 
| 6. Stress Components Deep Dive | Housing ratio, savings rate, correlation matrix, debt load | 
| 7. Predictive Projection (2027–2029) | NumPy polyfit national and state-level forecasts | 
| 8. Business Insights & Recommendations | Narrative synthesis, segment prioritisation | 

Each section opens with a short Markdown cell stating the business question being answered, followed by the supporting analysis.




---

<a id="tools"></a>

## 🛠️ Tools & Libraries
* Python 3.13.9 — core language.
* Pandas — data manipulation, groupby, rolling windows, pivot tables.
* NumPy — weighted composite scoring, polynomial trend fitting (`polyfit`), correlation matrices.
* Seaborn — heatmaps, distribution plots, segmented comparisons.
* Matplotlib — time-series charts, annotated trend lines, projection overlays.

  
Install dependencies with:
```
pip install -r requirements.txt
```





---

*Data is synthetic and generated for analytical purposes*
