# 🦠 COVID-19 Global Trends – SQL-Based Exploratory Data Analysis

This project presents an SQL-based exploration of COVID-19 data using **Microsoft SQL Server 2019**. The goal was to generate actionable insights into global and continental infection trends, mortality rates, and recovery metrics. This work was part of our broader data analytics initiative to apply SQL for real-world health crisis analysis.

📄 [**View SQL Code on GitHub**](https://github.com/AbassFatah/Portfolio_Projects/blob/main/Covid%2019%20Data%20exploration%20SQL.sql)

---

## 🎯 Project Objectives

- Conduct exploratory data analysis (EDA) on COVID-19 using **SQL queries**.
- Evaluate **global and regional case trends**, including **infection and death rates**.
- Demonstrate the use of SQL for deriving insights from **time-series health data**.
- Develop robust, reproducible queries to power future dashboards and reporting.

---

## 🧠 Key Insights Derived

- Infection and death trends across **continents and countries**.
- Comparative analysis of **new cases, deaths, and recovery rates** over time.
- Identification of **hotspot regions** with the highest case surges.
- Growth rates and **daily rolling averages** for better temporal visibility.

---

## 🧮 Dataset Structure

The dataset was loaded into SQL Server and contained fields such as:

| Column Name | Description |
|-------------|-------------|
| `continent` | Continent of the location |
| `location` | Country/region name |
| `date` | Date of report |
| `total_cases` | Cumulative confirmed cases |
| `new_cases` | New daily confirmed cases |
| `total_deaths` | Cumulative deaths |
| `new_deaths` | Daily new deaths |
| `population` | Population of the location |
| `life_expectancy` | Estimated life expectancy |
| `gdp_per_capita` | Economic context indicator |

---

## 🔧 Tools Used

- **SQL Server 2019** – Core querying and data analysis
- **SSMS (SQL Server Management Studio)** – IDE for SQL development
- **GitHub** – Versioning and collaboration

---

## 📁 Query Types & Examples

- `CASE WHEN` statements to group and clean data
- `GROUP BY` and aggregate functions for trend analysis
- Rolling metrics using `OVER(PARTITION BY ...)`
- `JOIN` operations to enrich datasets with population context
- `CTE` (Common Table Expressions) for layered analysis

---

## 🔍 Use Cases

- **Health agencies** assessing infection trends and comparing regions.
- **Policy analysts** reviewing death rates to inform containment efforts.
- **Business continuity teams** planning for supply chain impact.
- **Data teams** developing COVID dashboards powered by SQL.

---

## 🚀 Future Extensions

- Integration with **Power BI** or **Tableau** for visual dashboards.
- Scheduled data ingestion pipelines using **SQL Agent Jobs**.
- Extension into **predictive modeling** with time-series features.

---
