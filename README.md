# CodeAlpha_Unemployment_Analysis
Advanced macro-economic time-series analytics and sector distribution profiles evaluating localized Covid-19 quarantine anomalies using Python pipelines.

# 📈 Dual-Dataset Unemployment Rate Analytics
**Economic Impact Mapping & Trend Analysis | CodeAlpha Data Science Internship — Task 2**

---

## 📋 Project Summary
This repository houses an advanced data analytics framework engineered to ingest, clean, and analyze macroeconomic indicators using two distinct regional datasets. The pipeline explicitly highlights spatial and temporal shifts across Indian states, isolating pre-pandemic baselines against severe economic anomalies triggered during the Covid-19 global lockdown phase.

---

## 📊 Core Analytical Insights
* **The Pandemic Shock Event:** Temporal analysis confirms a historic economic spike starting March 2020. The national average unemployment rate peaked drastically above **23%** during the core lockdown period (April–June 2020).
* **Vulnerability Vectors:** Geographically, **Haryana**, **Tripura**, and **Jharkhand** registered the highest structural mean unemployment ratios throughout the observation timeline.
* **Urban vs Rural Asymmetry:** Urban centers sustained a higher concentrated unemployment baseline (Mean: **13.17%**) compared to Rural sectors (Mean: **10.32%**). However, rural environments displayed a superior structural labor participation threshold of **44.46%**.

---

## 🛠️ Data Infrastructure Stack
* **Environment:** Python 3.12 within VS Code (Jupyter Suite)
* **Statistical Processing Suites:** `Pandas`, `NumPy`
* **Data Visualization Suites:** `Matplotlib`, `Seaborn`

---

## 📐 Data Processing Pipeline Architecture

### Phase 1: Ingestion & Dual-Dataset Cross Examination
* Safe data parsing of `Unemployment in India.csv` and `Unemployment_Rate_upto_11_2020.csv`.
* Shape verification mapping multidimensional data shapes ($768 \times 7$ and $267 \times 9$).

### Phase 2: String Sanitization & Date Formatting
* Extracted hidden leading and trailing white-spaces directly from raw column headers.
* Successfully eliminated spacer null fields.
* Transformed date series categories from default strings into machine-readable `datetime64[ns]` time stamps.

### Phase 3: Exploratory Visualization Engineering
* Built sorted state-wise horizontal bar plots isolating the absolute distribution of unemployment metrics.
* Developed time-series line plots overlaying explicit lockdown highlight window markers (`axvspan`).
* Deployed distribution boxplots detailing data variance and identifying outlier ranges.

---
**Developed with 💻 by Ayat Adnan | Data Science Intern at CodeAlpha (2026)**
