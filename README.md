# World-Life-Expectancy-
This exploratory analysis reveals global health patterns across 15 years using the World Life Expectancy dataset. By examining trends in life expectancy, GDP, BMI, development status, and adult mortality, several clear insights emerge.
Got you, Alex — here is the **full, clean, copy‑paste‑ready README.md** exactly as it should appear in your GitHub repository, **with all screenshot placeholders already embedded**.  
Just paste this into your repo’s main `README.md` and upload your screenshots into the folders you created — everything will render perfectly.

---

# 🌍 **World Life Expectancy – SQL Data Cleaning & Exploratory Analysis**  
*A complete SQL portfolio project demonstrating data cleaning, validation, and exploratory analysis using global health data.*

---

## 📘 **Project Overview**

This repository contains two SQL projects built using the **World Life Expectancy** dataset:

### **1. Data Cleaning**
You identify and fix:
- Duplicate records  
- Missing values  
- Inconsistent categorical fields  
- Missing life expectancy values using interpolation  
- Status standardization (Developed vs Developing)

### **2. Exploratory Data Analysis (EDA)**
You uncover global health insights by analyzing:
- Life expectancy trends  
- GDP relationships  
- Development status  
- BMI patterns  
- Adult mortality trends  
- Country‑level improvements over time  

This project demonstrates strong SQL skills including:
- Window functions  
- Aggregations  
- Conditional logic  
- Joins  
- Data validation  
- Analytical storytelling  

---

# 📁 **Repository Structure**

```
sql-world-life-expectancy/
│
├── project-1-data-cleaning/
│   ├── world_life_expectancy_cleaning.sql
│   └── screenshots/
│       ├── duplicates-check.png
│       ├── row-number-duplicates.png
│       ├── status-cleaning.png
│       ├── life-expectancy-interpolation.png
│       └── final-cleaned-table.png
│
└── project-2-exploratory-analysis/
    ├── world_life_expectancy_eda.sql
    └── screenshots/
        ├── life-increase-by-country.png
        ├── avg-life-expectancy-by-year.png
        ├── gdp-vs-life-exp.png
        ├── high-vs-low-gdp.png
        ├── developed-vs-developing.png
        ├── bmi-vs-life-exp.png
        └── adult-mortality-window-function.png
```

---

# 🧼 **Project 1: Data Cleaning**

### **Duplicate Detection & Removal**
You identify duplicate Country‑Year combinations using `ROW_NUMBER()` and safely delete them.

📸 *duplicates-check.png*  
📸 *row-number-duplicates.png*

---

### **Status Standardization (Developed vs Developing)**  
You fix missing or inconsistent `Status` values using self‑joins.

📸 *status-cleaning.png*

---

### **Life Expectancy Interpolation**  
Missing life expectancy values are filled using the average of the previous and next year.

📸 *life-expectancy-interpolation.png*

---

### **Final Cleaned Dataset**

📸 *final-cleaned-table.png*

---

# 📊 **Project 2: Exploratory Data Analysis (EDA)**

Below are the combined insights from all SQL analysis, with screenshot placeholders included.

---

## ⭐ **1. Life Expectancy Over the Years**

Global life expectancy increased from **66.7 years (2007)** to **71.6 years (2022)** — a steady upward trend.

📸 *avg-life-expectancy-by-year.png*

---

## ⭐ **2. Countries With the Best & Worst Life Expectancy Growth**

You calculate each country’s 15‑year improvement using:

```sql
MAX(Life Expectancy) - MIN(Life Expectancy)
```

Countries like **Guyana, Seychelles, Kuwait** show strong improvement, while others show slower growth.

📸 *life-increase-by-country.png*

---

## ⭐ **3. GDP vs Life Expectancy**

High‑GDP countries consistently show higher life expectancy:

Examples:
- Switzerland — 82.3 years  
- Luxembourg — 80.8 years  
- Qatar — 80.7 years  

📸 *gdp-vs-life-exp.png*

---

## ⭐ **4. High‑GDP vs Low‑GDP Groups**

| Group | Avg Life Expectancy |
|-------|----------------------|
| **High GDP (≥1500)** | **~74.2 years** |
| **Low GDP (≤1500)** | **~64.7 years** |

📸 *high-vs-low-gdp.png*

---

## ⭐ **5. Developed vs Developing Countries**

| Status | Avg Life Expectancy |
|--------|----------------------|
| **Developed** | **79.2 years** |
| **Developing** | **66.8 years** |

📸 *developed-vs-developing.png*

---

## ⭐ **6. BMI vs Life Expectancy**

Sorting by BMI reveals a non‑linear relationship:

- **Very low BMI** → lower life expectancy  
- **Moderate BMI** → higher life expectancy  
- **Very high BMI** → slight decline  

📸 *bmi-vs-life-exp.png*

---

## ⭐ **7. Adult Mortality Trends (Window Function)**

Using a cumulative window function, you track adult mortality over time for countries like the **United Arab Emirates**.

📸 *adult-mortality-window-function.png*

---

# 🧠 **Combined Insight Summary**

Across all analyses, the dataset consistently shows:

- **Economic strength (GDP)**  
- **Development status**  
- **Nutrition (BMI)**  
- **Healthcare access**  
- **Mortality trends**

…are the strongest predictors of life expectancy.

Countries with higher GDP, developed infrastructure, and moderate BMI values live **significantly longer** than those facing economic or health‑system challenges.

---

# 🚀 **How to Use This Repository**

1. Upload your screenshots into the folders shown above.  
2. Paste this README into your main `README.md`.  
3. Commit your SQL files and push the repo.  

Your portfolio will look polished, professional, and recruiter‑ready.

---

If you want, I can also write:
- A LinkedIn project description  
- A portfolio summary  
- A recruiter‑optimized bullet list  

Just tell me what you want next.
