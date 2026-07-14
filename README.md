# COVID-19 Data Analysis using SQL & Tableau

## 📌 Project Overview

This project analyzes global COVID-19 data using SQL for data exploration and Tableau for data visualization. The goal is to understand the spread of the pandemic by examining infection rates, death statistics, vaccination progress, and regional trends. SQL was used to clean, transform, and analyze the data before creating an interactive Tableau dashboard.

---

## 🎯 Objectives

The project aims to answer the following questions:

- What percentage of the population has been vaccinated?
- Which countries have the highest infection rates?
- Which countries reported the highest number of COVID-19 deaths?
- How do death counts compare across continents?
- What is the global COVID-19 death percentage?
- How did vaccination progress change over time?

---

## 📂 Dataset

The project uses publicly available COVID-19 datasets containing worldwide statistics.

### CovidDeaths Table

Includes information such as:

- Country
- Continent
- Date
- Population
- Total Cases
- New Cases
- Total Deaths
- New Deaths

### CovidVaccinations Table

Includes vaccination-related information such as:

- Country
- Date
- New Vaccinations
- Total Vaccinations

---

## 🛠 SQL Skills Demonstrated

During this project, the following SQL concepts were used:

- SELECT statements
- WHERE filtering
- ORDER BY
- Aggregate Functions (SUM, MAX)
- GROUP BY
- INNER JOIN
- Common Table Expressions (CTEs)
- Window Functions
- Data Type Conversion using CAST and CONVERT
- Calculated Columns
- Percentage Calculations

---

## 📊 Key Insights

Some of the analysis performed includes:

- Comparing total COVID-19 cases with total deaths
- Calculating death percentage by country
- Measuring infection rates relative to population
- Identifying countries with the highest infection rates
- Identifying countries and continents with the highest death counts
- Calculating global COVID-19 statistics
- Tracking cumulative vaccination progress over time
- Measuring vaccination percentage across different countries

---

## 📈 Tableau Dashboard

The SQL analysis was visualized in Tableau through an interactive dashboard displaying:

- Global COVID-19 Summary
- Total Cases
- Total Deaths
- Death Percentage
- Cases by Country
- Deaths by Continent
- Vaccination Progress
- Infection Rate by Country

The dashboard provides an overview of worldwide COVID-19 trends and supports interactive data exploration.

---

## 📁 Repository Structure

```
Covid-19-SQL-Analysis/
│
├── Dataset/
│   ├── CovidDeaths.csv
│   └── CovidVaccinations.csv
│
├── SQL/
│   └── Covid_Analysis.sql
│
├── Tableau/
│   └── Covid Dashboard.twbx
│
├── Images/
│   └── Dashboard.png
│
└── README.md
```

---

## ▶️ How to Run

1. Download the COVID-19 datasets.
2. Import the datasets into your SQL database.
3. Execute the SQL queries provided in the SQL script.
4. Review the generated results.
5. Connect Tableau to the processed data.
6. Open the Tableau workbook to explore the dashboard.

---

## 🚀 Future Improvements

Possible enhancements include:

- Automating data updates
- Creating stored procedures for repeated analysis
- Building interactive SQL reports
- Developing Power BI dashboards for comparison
- Performing time-series forecasting
- Adding predictive analytics using Python

---

## 📚 Tools Used

- SQL Server
- SQL
- Tableau
- Microsoft Excel
- Public COVID-19 Dataset

---

## 📌 Key Learning Outcomes

Through this project, I gained hands-on experience with:

- Writing analytical SQL queries
- Working with relational datasets
- Performing data aggregation and calculations
- Using joins and window functions
- Building interactive dashboards in Tableau
- Converting raw data into business insights
