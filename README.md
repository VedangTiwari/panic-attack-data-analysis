# 🧠 Panic Attacks Data Analysis Dashboard

This project explores **factors and triggers associated with panic attacks**, analyzing their distribution across **different age groups**.  
It demonstrates an **end-to-end data analytics workflow** — from connecting to a **Snowflake data warehouse**, cleaning and modeling the data, to visualizing key insights using **Power BI**.

---

## 🚀 Project Overview

The goal of this project was to identify patterns, correlations, and insights about panic attacks across demographic groups.  
By leveraging **Snowflake, SQL, Power Query, and DAX**, I built a powerful and interactive Power BI dashboard that highlights trends in symptoms, triggers, and patient demographics.

### 🔄 Workflow Summary

1. **Data Extraction:** Connected to **Snowflake** to pull raw patient and symptom data.  
2. **Data Preparation:** Used **SQL queries** for exploration, cleaning, and initial transformation.  
3. **Data Modeling:** Created relationships, hierarchies, and custom columns in **Power BI**.  
4. **Visualization:** Designed dynamic dashboards to uncover key insights and trends.

---

## 🛠️ Tech Stack & Tools

| Category | Tools / Techniques |
|-----------|--------------------|
| **Data Source** | Snowflake Cloud Data Warehouse |
| **Data Extraction** | SQL Queries |
| **Data Transformation** | Power Query (M Language) |
| **Data Analysis** | DAX (Data Analysis Expressions) |
| **Data Visualization** | Microsoft Power BI |

---

## ⚙️ Key Features & Implementation

### 🧩 Data Preparation
- Extracted and cleaned data directly from **Snowflake** using **SQL** queries.  
- Handled missing values, standardized fields, and created lookup relationships.  
- Imported datasets into Power BI for transformation and visualization.

### 🧮 Data Modeling
- Built a **dimensional model** linking patient demographics with symptom data.  
- Used **nested IF** and **SWITCH** functions to categorize patients by **Age Group**.  
- Created **Conditional Columns** in Power Query to segment data based on triggers and severity.

### 📊 DAX Measures
Developed **custom DAX measures** for interactive metrics, such as:

| Metric | Description | DAX Functions Used |
|--------|--------------|--------------------|
| **% of Patients with Dizziness** | Calculates the proportion of patients with dizziness. | `DIVIDE`, `COUNTROWS`, `FILTER` |
| **Average Panic Duration** | Computes mean panic duration across groups. | `AVERAGEX` |
| **Patient Count by Age Group** | Counts patients within age segments. | `CALCULATE`, `COUNTROWS` |
| **Symptom Frequency Index** | Measures relative symptom intensity. | `SUMX`, `CALCULATE` |

---

## 📈 Dashboard Insights

The dashboard provides a **clear view of panic attack trends** by age, gender, and symptom category.  
Some of the major insights include:

- **Age Factor:** Certain age groups are more prone to frequent panic episodes.  
- **Symptom Trends:** Dizziness, rapid heartbeat, and chest tightness are the most common symptoms.  
- **Demographic Insights:** Gender-based variation in reported symptoms.  
- **Trigger Patterns:** Identifies lifestyle or stress-related triggers linked to panic frequency.

---

## 🖼️ Dashboard Preview

Below are some visual highlights from the Power BI dashboard 👇  
### 📊 1.Introduction
![Overall Insights](https://github.com/grandline-coder/panic-attacks-data-analysis/blob/main/Capture.PNG)

### 👥 1. Age Group Distribution
![Age Group Distribution](https://github.com/grandline-coder/panic-attacks-data-analysis/blob/main/age%20group%20analysis.PNG)

### 💫 2. Symptom & Trigger Breakdown
![Symptom Breakdown](https://github.com/grandline-coder/panic-attacks-data-analysis/blob/main/panic%20attack%20analysis.PNG)

### ⚙️ 3. Patient Overview Dashboard
![Patient Overview](https://github.com/grandline-coder/panic-attacks-data-analysis/blob/main/Other.PNG)



---

## 🔗 Live Power BI Dashboard

Explore the interactive dashboard here:  
👉 [**View Power BI Dashboard**](https://app.powerbi.com/links/zpCEYa9JH7?ctid=fbe9137e-2f40-4d34-88cd-cc8cb4c515ee&pbi_source=linkShare&bookmarkGuid=712864b0-c475-4a79-b7bd-00a7c953b264)





