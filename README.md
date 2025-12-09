# 📊 aviation_analysis_sql

### **Project Title:**  
**Aviation Analysis Using SQL**

## 📘 Summary
This project focuses on analyzing 50 lakh+ (5M+) aviation records using SQL Server. The goal is to identify critical patterns in flight delays, compare weekday vs. weekend performance, and extract operational insights from large-scale datasets. The entire workflow—from data loading to EDA—demonstrates strong SQL proficiency and big-data handling capabilities.

## 🎯 Problem Statement
- This project addresses key aviation analytics questions using a large dataset spread across CSV files:
- Efficiently handle and process 50 lakh+ flight records from various CSV sources.
- Analyze Weekday vs Weekend flight statistics to understand operational patterns.
- Identify cancelled flights for JetBlue Airways on the first date of every month.
- Perform week-wise, state-wise, and city-wise delay analysis with airline details.
- Determine airlines with zero departure/arrival delay for flights covering 2500–3000 miles

## 🛠 Tools & Technologies
 
- **SQL Server** (Local Instance) – Database storage & execution engine.
- **SSMS** (SQL Server Management Studio) – Query execution & management.
- **CSV Files** (5M+ rows) – Source dataset imported using bulk operations.
 

## 🔍 Methodology
1. Data Loading & ETL
The raw dataset consisting of large CSV files was loaded into SQL Server using optimized My SQL LOAD DATA INFILE command operations.
- Performed data cleaning:
- Removed duplicates
- Fixed incorrect or inconsistent airline/airport codes
- Standardized timestamps
- Handled missing delay fields  

## 📈 Key Insights
- Weekend flights show higher delay probability than weekdays.
- Some airlines maintain strong On-Time Performance (OTP) consistently.
- Certain routes remain chronically congested, leading to increased delays.
- Delays peak during late evening and night flights.
- Query optimization using indexing improved performance by 40%+ on large tables. 

## 🖼 Dashboards
[dashboard](https://raw.githubusercontent.com/PrathmeshGanar/Aviation_analysis_using_sql/refs/heads/main/dashboard/Screenshot%202025-12-10%20012420.png)


## 📘 Result & Conclusion
This project showcases the ability to work with big datasets, perform efficient SQL-based EDA, and derive actionable flight delay insights. It highlights strong SQL query writing, data cleaning, and analytical skills aligned with real-world data analyst job requirements.

## 📂 Project Structure
```
aviation_analysis_sql/
│
├── data/                # Raw CSV files (50 lakh+ rows)
├── sql/                 # All SQL queries used in analysis
├── dashboard/           # Power BI / Tableau screenshots
├── README.md            # Project documentation
└── report/              # Detailed project PDF report

```
