<div align="center">

# 📊 Data Science Job Salaries — EDA Capstone Project
**Samsung Innovation Campus (SIC8) · AI801 Graduation Project**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](#)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)](#)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](#)

*An exploratory data analysis answering one core question:*<br>
**What actually determines a data scientist's salary — experience, company size, or location?**

</div>

---

## 📌 Overview
This project explores the [Data Science Job Salaries dataset](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries) from Kaggle. Through data cleaning, descriptive statistics, and grouped analysis, we aim to uncover the primary drivers behind compensation in the data science field.

> **🔑 Key Finding:** **Experience level is the strongest driver of salary** — overshadowing both company size and location. Salaries observe a **3.2× jump** from Entry-level (~$61.6K) to Executive-level (~$199.4K).

---

## 🗂️ Project Structure
```text
├── data/               # Raw and cleaned datasets
├── notebooks/          # EDA notebook (cleaning, stats, correlation, grouped analysis)
├── dashboard/          # Interactive Power BI dashboard
├── presentation/       # Final slide deck
```

## 📊 Dataset Snapshot
- **Source**: [Kaggle — Data Science Job Salaries](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)
- **Size**: `607` rows × `12` columns ➔ Cleaned to `565` rows × `11` columns
- **Time Span**: 2020–2022
- **Key Variables**: `experience_level`, `employment_type`, `job_title`, `salary_in_usd`, `company_location`, `company_size`, `remote_ratio`

## ⚙️ Methodology
1. **Data Cleaning:** Removed duplicates, handled missing values, and corrected data types.
2. **Outlier Detection:** Implemented the IQR (Interquartile Range) method.
3. **Descriptive Statistics:** Calculated mean, median, and standard deviation.
4. **Grouped Analysis:** Evaluated metrics across experience, company size, year, job title, location, employment type, and remote ratio.
5. **Correlation Analysis:** Assessed Pearson correlation (e.g., `work_year` vs. `salary_in_usd`).

## 📈 Findings Summary

| Factor | Key Finding |
| :--- | :--- |
| **🎓 Experience Level** | **Strongest driver** — Entry ($61.6K) ➔ Executive ($199.4K) |
| **🏢 Company Size** | Weaker effect than expected — Medium ($114.8K) vs Large ($118.2K) |
| **📅 Work Year** | Steady growth — Salaries rose from $95.8K (2020) to $123.1K (2022) |
| **🏠 Remote Work** | Fully remote highest ($120.8K) — *Indicates association, not causation* |
| **🌍 Top Location** | US leads the market, but represents 56% of the sample *(caution advised)* |

## ⚠️ Limitations
- **Geographic Skew:** The US dominates the sample (318 out of 565 records).
- **Sample Size:** Contract/Freelance employment types have very small sample sizes.
- **Timeframe:** Data is limited to a 3-year span (2020–2022).
- **Correlation:** Tested strictly on numeric variables.

## 🛠️ Tools & Technologies
- **Programming:** Python (`pandas`, `seaborn`, `matplotlib`)
- **BI & Visualization:** Power BI

---

<div align="center">
<i>Educational project — Samsung Innovation Campus 2026 </i>
</div>
