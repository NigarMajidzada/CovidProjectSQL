# COVID-19 Data Exploration with SQL

A data exploration project that analyzes global COVID-19 statistics using SQL queries. The project examines infection rates, death counts, and vaccination progress across countries and continents to uncover meaningful trends from the pandemic data.

## Tech Stack

| Category | Technology |
|---|---|
| **Language** | SQL (T-SQL) |
| **Database** | Microsoft SQL Server |
| **Techniques** | Joins, CTEs, Temp Tables, Window Functions, Aggregate Functions, Views |

## Project Structure

```
CovidProjectSQL/
└── CovidPortfolioProject.sql   # All exploration queries
```

### Data Sources

The queries operate on two tables:

- **CovidDeaths** — cases, deaths, and population data by location and date
- **CovidVaccinations** — vaccination records by location and date

### Analyses Performed

| # | Analysis | Description |
|---|---|---|
| 1 | Death Percentage | Likelihood of dying after contracting COVID per country |
| 2 | Infection Rate | Percentage of population infected per country |
| 3 | Highest Infection Rate | Countries ranked by infection rate relative to population |
| 4 | Highest Death Count | Countries and continents ranked by total deaths |
| 5 | Global Summary | Worldwide aggregated case and death totals |
| 6 | Vaccination Progress | Rolling vaccination count per country using window functions |
