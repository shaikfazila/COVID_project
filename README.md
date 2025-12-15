# COVID_project
Here is a **clean, professional, GitHub-ready README.md** for your **COVID-19 Data Exploration (SQL)** project.
It matches **data analyst portfolio standards** and clearly reflects the SQL work you shared.

---

# 🦠 COVID-19 Data Exploration (SQL)

## 📌 Project Overview

This project focuses on **exploratory data analysis (EDA) of global COVID-19 data** using SQL.
The goal is to analyze **infection rates, death rates, and vaccination progress** across countries and continents to uncover meaningful trends and insights.

The analysis is performed using **structured SQL queries** and is suitable for **data analyst portfolio demonstration**.

---

## 🛠️ Tools & Skills Used

* **SQL (Microsoft SQL Server)**
* Joins
* Common Table Expressions (CTEs)
* Temporary Tables
* Window Functions
* Aggregate Functions
* Data Type Conversions
* Creating Views
* Exploratory Data Analysis (EDA)

---

## 📊 Datasets Used

* **CovidDeaths**
* **CovidVaccinations**

Both datasets include global COVID-19 statistics such as:

* Total cases
* New cases
* Total deaths
* Population
* Vaccination data
* Dates and locations

---

## 🔍 Analysis Performed

### 1️⃣ Initial Data Exploration

* Filtered out aggregated rows where continent data was missing
* Selected relevant fields for analysis such as:

  * Location
  * Date
  * Total cases
  * Total deaths
  * Population

---

### 2️⃣ Total Cases vs Total Deaths

* Calculated **death percentage** to determine:

  > Likelihood of dying after contracting COVID-19 in a given country

---

### 3️⃣ Total Cases vs Population

* Measured the **percentage of population infected**
* Helped compare infection spread across countries

---

### 4️⃣ Countries with Highest Infection Rate

* Identified countries with the **highest infection rate relative to population**
* Used aggregate functions and grouping

---

### 5️⃣ Countries & Continents with Highest Death Count

* Ranked countries by **total death count**
* Analyzed death counts at the **continent level**

---

### 6️⃣ Global COVID-19 Numbers

* Calculated global totals for:

  * New cases
  * New deaths
  * Overall death percentage

---

### 7️⃣ Population vs Vaccination Analysis

* Joined **CovidDeaths** and **CovidVaccinations** datasets
* Calculated a **rolling count of vaccinated people** using window functions
* Analyzed vaccination progress over time

---

## 🧠 Advanced SQL Techniques Used

### ✅ Common Table Expression (CTE)

Used to calculate the **percentage of population vaccinated** in a readable and reusable way.

### ✅ Temporary Table

Created a temp table to store intermediate vaccination calculations for further analysis.

### ✅ SQL View

Created a view (`PercentPopulationVaccinated`) to store cleaned and processed vaccination data for:

* Reusability
* Future visualizations
* BI tool integration

---

## 📂 Project Structure

```
📁 Covid-19-Data-Exploration-SQL
│
├── 📄 Covid19_Data_Exploration.sql
├── 📄 README.md
└── 📁 Screenshots (optional)
```

---

## 🎯 Key Insights

* Infection and death rates vary significantly by country
* Some countries experienced high infection rates despite smaller populations
* Vaccination progress shows clear trends over time when analyzed using rolling totals
* SQL window functions are powerful for time-based analysis

---

## 🚀 Use Cases

* Data analyst portfolio project
* SQL skill demonstration
* Public health data analysis
* Input dataset for Power BI / Tableau dashboards

---

## 📌 Future Enhancements

* Integrate with **Power BI** for interactive dashboards
* Add time-series trend analysis
* Compare pre- and post-vaccination impacts
* Automate data refresh pipelines

---

## 👤 Author

**Shaik Fazila**
Aspiring Data Analyst
Skills: SQL, Excel, Power BI, Python

---

## 📜 License

This project is intended for **educational and portfolio purposes**.

---

If you want, I can also:

* Shorten this README
* Make it **ATS-optimized**
* Write a **GitHub About description**
* Convert this into a **Power BI project README**

Just tell me 👍
