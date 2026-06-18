# oncology-data-analysis-nyc-
Healthcare Providers Data Analysis using Python, SQL (DuckDB), and Looker Studio.
# Healthcare Providers Analysis (NYC)

## Project Overview

This project explores healthcare provider data from New York City with the goal of understanding provider distribution, patient review patterns, and category diversity. The analysis combines Python for data exploration, SQL for querying and aggregation, and Looker Studio for dashboard development.

## Dataset Summary

* **Total Providers:** 640
* **Provider Categories:** 36
* **Cities Covered:** 16

## Tools & Technologies

* Python (Pandas)
* SQL (DuckDB)
* Matplotlib
* Looker Studio
* Google Colab

## Project Workflow

The analysis followed a typical data analytics process:

1. Loaded and explored the dataset.
2. Performed exploratory data analysis (EDA).
3. Checked for missing values and duplicate records.
4. Wrote SQL queries to summarize and analyze the data.
5. Used window functions such as `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, and `AVG() OVER()` to compare providers within their categories.
6. Created visualizations and an interactive dashboard in Looker Studio.
7. Documented key findings and recommendations.

## SQL Topics Covered

* SELECT
* WHERE
* GROUP BY
* ORDER BY
* HAVING
* CASE WHEN
* COALESCE
* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* Window Functions

## Dashboard

The final dashboard presents:

* Total providers
* Total provider categories
* Total cities
* Provider distribution by category
* Provider distribution by city
* Review distribution

The dashboard is available in **dashboard.pdf**.

## Key Findings

The dataset shows that provider representation is uneven across categories, with some specialties appearing much more frequently than others. Review activity is also highly variable, ranging from providers with only a few reviews to a small number with substantially higher visibility. Geographic analysis indicates that providers are concentrated in a limited number of cities, reflecting differences in healthcare availability within the dataset.

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* SQL Querying
* Window Functions
* Data Visualization
* Dashboard Design
* Business Insight Development

## Project Files

* `dashboard.pdf` — Looker Studio dashboard
* `README.md` — Project documentation
