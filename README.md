# COVID-19 Data Analysis Using SQL

## Project Overview
This project explores global COVID-19 case, death, and vaccination data using SQL to identify trends, calculate key metrics, and prepare datasets for reporting and visualisation. The analysis focuses on understanding infection rates, death percentages, and vaccination progress across countries and continents.

The goal of this project was to demonstrate data analysis, data transformation, and querying skills using real-world datasets.

---

## Data Sources
- COVID-19 Deaths dataset  
- COVID-19 Vaccinations dataset  

Both tables were queried from a structured SQL database and analysed using T-SQL.

---

## Tools & Technologies
- SQL (T-SQL)
- SQL Server
- Aggregate functions
- Joins
- Window functions
- Common Table Expressions (CTEs)
- Temporary tables
- Views

---

## Key Analysis Performed

### 1. Exploratory Data Analysis
- Retrieved and reviewed COVID-19 case and vaccination data by location and date.
- Selected relevant columns such as total cases, new cases, total deaths, population, and vaccination counts.

### 2. Case Fatality & Infection Rates
- Calculated **death percentage** by comparing total deaths to total cases.
- Calculated the **percentage of population infected** with COVID-19.
- Analysed specific countries (e.g. United Kingdom) to track trends over time.

### 3. Country & Global Comparisons
- Identified countries with the **highest infection rates relative to population**.
- Identified countries with the **highest total death counts**.
- Aggregated data to compare **global case and death trends over time**.
- Segmented analysis by continent where applicable.

### 4. Vaccination Analysis
- Joined COVID-19 deaths and vaccination datasets to analyse vaccination rollout.
- Used **window functions** to calculate a rolling total of vaccinations by country.
- Calculated the **percentage of population vaccinated** over time.

### 5. Data Modelling for Reporting
- Created a **CTE** to simplify population vs vaccination analysis.
- Built a **temporary table** for reusable vaccination percentage calculations.
- Created a **SQL view** to support downstream visualisation and dashboarding.

---

## Key Outputs
- Country-level and global COVID-19 metrics
- Infection and death rate calculations
- Rolling vaccination totals by location
- Clean, structured SQL view designed for reporting tools such as Excel, Power BI, or Tableau

---

## Example Skills Demonstrated
- Data cleaning and validation
- Analytical thinking with real-world datasets
- Writing complex SQL queries
- Using window functions for time-series analysis
- Preparing datasets for visualisation and reporting

---

## Next Steps / Possible Improvements
- Visualise insights using Power BI or Tableau
- Automate refreshable reporting using the created SQL view
- Extend analysis to compare vaccination rollout speed between regions

---

## Author
Physics graduate with a strong interest in data analytics, reporting, and business insights.
