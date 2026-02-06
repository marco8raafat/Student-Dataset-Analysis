# 🎓 Student Performance Analysis Dashboard

**Project Title:** Student Dataset Analysis  
**Author:** Marco  
**Date:** February 2026  
**Tools:** Power BI Desktop  
**Dataset:** [UCI Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance) (395 records)

---

## 🎯 Project Goal
The objective of this project is to explore and visualize key factors influencing secondary school students' academic performance. Using an interactive Power BI dashboard, this analysis identifies patterns among demographic, family, social, and behavioral variables to help educators and administrators support student success.

---

## 📊 Dashboard Overview

### 1. Main Overview & KPIs
The landing page provides high-level metrics including average grades and basic student demographics.
- **Avg. Assignment (G1):** 10.91
- **Avg. Midterm (G2):** 10.71
- **Avg. Final Grade (G3):** 10.42

![Overview Dashboard](Overview%20Dashboard.png)

### 2. Demographic & Family Background
This section explores the impact of parental education and job categories on student outcomes.
![Grade Analysis 1](Grade%20Analysis%201%20.png)

### 3. Socio-Economic Influences
Analyzing the correlation between address (Urban vs. Rural), internet access, and extra educational support.
![Grade Analysis 2](Grade%20Analysis%202.png)

### 4. Health & Lifestyle Factors
Visualizing the impact of health status and alcohol consumption (workday vs. weekend) on academic focus.
![Grade Analysis 3](Grade%20Analysis%203.png)

### 5. Behavioral Insights: Absences & Social Life
A deep dive into how "going out with friends" and school absences directly correlate to failure rates.
![Grade Analysis 4](Grade%20Analysis%204.png)

### 6. Performance Decomposition
An interactive decomposition tree used to drill down into total grades by gender, age, and health status.
![Grade Analysis 5](Grade%20Analysis%205.png)

---

## 🔍 Key Findings

* **Attendance is King:** There is a strong negative relationship between absences and final grades. High absences are the #1 predictor of lower performance.
* **Early Indicators:** G1 and G2 grades are extremely strong predictors of the final G3 result.
* **Social Balance:** A "U-shaped" pattern exists for social life; students with moderate social interaction (level 3) perform better than those who rarely go out or go out too much.
* **Family Environment:** Higher family relationship quality (`famrel`) correlates with slightly higher final grades.
* **Urban Advantage:** Students living in urban areas and those with home internet access consistently outperform their peers.

---

## 🛠️ How the Dashboard Was Built
1.  **Data Source:** `student-mat.csv` (Mathematics course).
2.  **Data Cleaning:** Used Power Query to create readable labels for categories (e.g., `Dalc_Label`, `famrel_label`).
3.  **Visualizations:** * **KPI Cards** for quick metric tracking.
    * **Scatter Plots** to identify trends in absences.
    * **Decomposition Tree** for interactive root-cause analysis.
    * **Pie & Bar Charts** for demographic distributions.
4.  **Interactivity:** Integrated slicers for `Sex`, `Age`, `Health`, and `Internet Access`.

---

## 🚀 Recommendations
* **Monitor Absences Early:** School administrators should flag students with rising absences before they reach the final exam phase.
* **Digital Equity:** Providing internet access or school-based study hours for students without home access could bridge the performance gap.
* **Social Support:** Encourage extracurricular activities that provide "moderate" social interaction rather than extreme social isolation or excessive "going out."

---

## 📂 Files in this Repository
* `Student_Performance_Analysis.pbix` - Power BI Dashboard
* `cleaned-dataset.csv` - The processed dataset
* `README.md` - Project documentation

---
