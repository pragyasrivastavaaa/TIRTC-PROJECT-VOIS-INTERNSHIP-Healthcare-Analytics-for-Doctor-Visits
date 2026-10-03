# Healthcare Analytics for Doctor Visits

## VOIS TIRTC Data Analytics Project

**Domain:** Healthcare & Medical Analytics  
**Project Theme:** Healthcare Utilization and Doctor Visits Performance Analysis[cite: 3]  
**Author:** Pragya Srivastava (STU68639e54e89091751359060)  

---

## Project Overview
This repository contains a comprehensive data analytics project focused on analyzing healthcare utilization patterns based on individual doctor visits, health status, illness indicators, and socioeconomic variables[cite: 3]. The objective is to uncover underlying trends, examine patient demographics, and evaluate how factors like illness scores, age, income, and insurance coverage impact healthcare access and doctor visit frequencies.

---

## Dataset Details
* **Source:** Healthcare Analytics for Doctor Visits Dataset[cite: 3]
* **Description:** Contains records of individual health status, number of illnesses, restricted activity days, doctor visit frequencies, and socioeconomic factors[cite: 3].
* **Size:** 5,190 records with 13 variables[cite: 3].
* **Key Features:** `visits`, `gender`, `age`, `income`, `illness`, `reduced`, `health`, `private`, `freepoor`, `freerepat`, `nchronic`, and `lchronic`[cite: 3].

---

## Core Environment & Libraries
* **Programming Language:** Python
* **Environment:** Google Colab
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Statistical & Machine Learning:** SciPy, Scikit-learn

---

## Exploratory Data Analysis & Visualizations
* **Univariate Analysis:** Count plots and histograms visualizing distributions for doctor visits, gender, age, and income[cite: 4, 5].
* **Bivariate & Categorical Analysis:** Bar plots showing average doctor visits grouped by gender and non-chronic conditions[cite: 6]; line plots analyzing illness scores versus average doctor visits[cite: 7].
* **Advanced Visualizations:** Box plots and strip plots examining income distributions relative to private health insurance and illness scores[cite: 8]; violin plots showing age distribution across doctor visits[cite: 7]; joint density plots and correlation heatmaps[cite: 7].

---

## Conclusion
* **Utilization Patterns:** Doctor visit distributions are heavily right-skewed, with most patients reporting few or no visits[cite: 5], though utilization rises sharply with increasing illness scores[cite: 7].
* **Demographic Insights:** Female patients show a higher average number of doctor visits than male patients[cite: 6]. 
* **Socioeconomic Impact:** Income levels, private health insurance status[cite: 8], and chronic conditions significantly shape healthcare utilization trends.

---

## How to Run
1. Open the project notebook in **Google Colab**.
2. Ensure the dataset (`P2-Healthcare Analytics for Doctor Visits (1).csv`) is uploaded or accessible in your working environment[cite: 3].
3. Run the cells sequentially to reproduce the exploratory data analysis, visualizations, and statistical findings.
