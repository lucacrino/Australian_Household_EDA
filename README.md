# 🏠 Australian Household Exploratory Data Analysis
![Python](https://img.shields.io/badge/Python-3.13.9-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.2.3-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.1.3-013243?style=flat-square&logo=numpy&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.2-4C72B0?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10.0-11557C?style=flat-square)
---




## 📌 Business Problem
Between May 2022 and late 2023, the Reserve Bank of Australia raised interest rates 13 consecutive times — the sharpest tightening cycle in decades — while cost-of-living pressures accelerated across utilities, insurance, and everyday expenses.
> **Which Australian households were under the most financial stress, what drove it, and where is it heading by 2029?**
This project builds a composite Financial Stress Score (0–100) across 5,000 synthetic Australian households observed quarterly from Q1 2022 to Q4 2026, then projects the trajectory forward to 2029 using NumPy polynomial fitting — entirely in Pandas and NumPy, no machine learning libraries.
---



## 📂 Repository Structure
```
├── au_financial_stress_analysis.ipynb   # Main analysis notebook
├── data
│   └── au_household_financial_stress.csv
├── outputs
│   └── (exported charts, .png)
├── requirements.txt
└── README.md
```



---
## 📊 Dataset Overview
Attribute	Detail
Households	5,000 unique households
Observations	Quarterly — Q1 2022 to Q4 2026
Total rows	100,000
Geography	All 6 states + 2 territories
Variables	21 columns

