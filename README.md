# Cognifyz_DA_Task2_CityAnalysis
Task 2 of Cognifyz Technologies Data Analysis Internship — City-wise restaurant analysis using Python (pandas, matplotlib)

# 📊 Task 2 – City Analysis | Cognifyz Technologies Internship

### 🎓 Internship Overview
This repository contains my work for **Task 2 (City Analysis)** under the **Data Analysis Internship** offered by **Cognifyz Technologies**.  
The objective of this task is to analyze restaurant data to identify:

1. The **city with the highest number of restaurants**  
2. The **average restaurant rating for each city**  
3. The **city with the highest average rating**


## 🧠 Objective
To explore city-level restaurant trends and identify areas with high restaurant density and quality using real-world data.


## 🧩 Dataset Details
- **Total Records:** 9,551  
- **Columns:** 21  
- **Important Columns Used:**
  - `Restaurant ID`
  - `City`
  - `Aggregate rating`


## ⚙️ Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Python** | Programming Language |
| **pandas** | Data cleaning, aggregation, analysis |
| **matplotlib** | Data visualization |
| **Jupyter Notebook / Google Colab** | Coding environment |


## 🧹 Data Cleaning Steps
- Removed extra spaces from the `City` column    
- Ensured ratings are valid numeric values  
- Grouped data using `groupby()` to calculate:
  - Count of restaurants per city  
  - Average rating per city  


## 📈 Analysis Performed

### 🔹 City with Most Restaurants
```python
df.groupby('City')['Restaurant ID'].nunique()
```

---
*Created by Komal for the Data Analyst Internship Program.*
