# 🌧 Hasselt Rainfall Data Analysis

## 📌 Project Overview
This project analyzes monthly rainfall data for **Hasselt** to explore long-term rainfall patterns, seasonal variations, and anomalies.  
The dataset includes **monthly rainfall (mm)** values over multiple years.  

Main goals of the analysis:
- Understand rainfall **trends over time**  
- Detect **seasonal patterns** (which months are wettest/driest)  
- Identify **outliers** (unusually high/low rainfall months)  
- Provide insights into rainfall **variability and distribution**  

---

## 📂 Dataset
- **File Name:** `hasselt rainfall data monthly.csv`  
- **Columns:**
  - `Year` → Year of observation  
  - `Month` → Month of observation  
  - `Rainfall_mm` → Recorded rainfall in millimeters  

---

## 📊 Performed Analyses
1. **Data Cleaning**
   - Removed metadata rows  
   - Ensured numerical columns are properly formatted  

2. **Descriptive Statistics**
   - Mean, Median, Min, Max rainfall  
   - Standard Deviation & Variance  
   - Quartile statistics (Q1, Q3, IQR)  

3. **Outlier Detection**
   - Applied **IQR method** to find extreme rainfall values  

4. **Hypothesis Testing**
   - Explored possibility of applying **Z-test** for rainfall comparison  

---

## 📈 Visualizations
- **Line Chart (Total rainfall per year)** → Shows long-term rainfall trends  
- **Bar Chart (Average rainfall per month)** → Highlights seasonal rainfall patterns  
- **Boxplot per month** → Displays variability and detects outliers  

---

## 🚀 How to Run
1. Clone this repository or download the notebook (`rainfall.ipynb`).  
2. Install required libraries:  
   ```bash
   pip install pandas matplotlib seaborn
