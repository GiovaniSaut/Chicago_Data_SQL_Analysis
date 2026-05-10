# Chicago City Data — SQL Analysis

**IBM SQL for Data Science with Python | Coursera Plus | 2026**

---

## Overview

A SQL analysis of three real-world Chicago datasets — crime records, census socioeconomic data, and public school performance — answering 10 questions about crime patterns, community hardship, and school safety.

This project was completed as the final assignment for the IBM Databases and SQL for Data Science with Python course, demonstrating practical SQL skills against real messy data.

---

## Datasets

| Dataset | Rows | Source |
|---|---|---|
| Chicago Crime Data | 533 incidents | Chicago Data Portal |
| Chicago Census Data | 78 community areas | Chicago Data Portal |
| Chicago Public Schools | 566 schools | Chicago Data Portal |

---

## Key Findings

- **Austin** (community area 25) is the most crime-prone neighbourhood with 43 recorded incidents
- **Riverdale** has both the highest hardship index (98/100) and one of the lowest per capita incomes in the city (<$11,000)
- **4 community areas** have a per capita income below $11,000 — all on the south and west sides
- **Middle schools** average a safety score of only 48 out of 99
- **6 distinct crime types** occur in school settings; battery is the most common
- Only **1 child kidnapping** incident is recorded in the dataset

---

## SQL Techniques Demonstrated

`COUNT()` `AVG()` `MAX()` `WHERE` `LIKE` `SELECT DISTINCT` `GROUP BY` `ORDER BY` `LIMIT` `JOIN` `Subqueries`

---

## Files

- [`chicago_analysis.ipynb`](./chicago_analysis.ipynb) — full notebook with all queries and results
- [`ChicagoCrimeData.csv`](./ChicagoCrimeData.csv) — crime dataset
- [`ChicagoCensusData.csv`](./ChicagoCensusData.csv) — census dataset
- [`ChicagoPublicSchools.csv`](./ChicagoPublicSchools.csv) — schools dataset
