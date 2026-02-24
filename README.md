# Demographic & Structural Analysis of Aadhaar Enrollment Data

## 📌 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** and **data preprocessing** on Aadhaar enrollment data at the district level.

The analysis focuses on:
- Enrollment distribution
- Age-group segmentation
- Dependency ratios
- Structural demographic patterns

---

## 🎯 Objectives
- Clean and preprocess raw enrollment datasets
- Remove duplicates and fix data types
- Engineer analytical features
- Analyze demographic structure
- Derive district-level insights

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook
- SQL (MySQL)

---

## 🧹 Data Preprocessing Steps
✔ Loaded datasets from multiple folders:
- Enrollments
- Demography
- Biometrics

✔ Focused analysis on **enrollment data**

✔ Cleaning operations:
- Duplicate removal
- Data type correction
- Missing value handling

✔ Feature Engineering:
- Total enrollments
- Child ratio
- Youth ratio
- Adult ratio
- Dependency ratio
- Enrollment Structural Index (ESI)

---

## 🧮 Key Derived Metrics

### Dependency Ratio
Calculated to measure demographic pressure:

Special handling for:
- Infinite ratios (Adult = 0)
- NaN / Blank values

---

## 📊 Analysis Performed
- District-wise enrollment comparison
- Dependency ratio evaluation
- Identification of high dependency districts
- Detection of anomalous demographic structures

---

## 💾 Data Export
- Created derived district-level table
- Exported cleaned dataset
- Loaded into MySQL database

---

## 📈 Insights Derived
- Structural demographic imbalance detection
- District-level enrollment patterns
- Dependency burden analysis

---

## 📂 Repository Contents
- `analysis.ipynb` → Jupyter Notebook
- `dataset.csv` → Cleaned dataset
- `README.md`

---

## 📬 Author
**Nishant Karn**  
Instrumentation Engineering Student  
Data Analytics | Python | Power BI

---

## ⭐ If you like this project
Give it a ⭐ on GitHub!
