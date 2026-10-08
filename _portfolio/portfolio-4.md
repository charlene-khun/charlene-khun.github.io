---
title: "NYPL Data Cleaning & Analysis Project"
excerpt: "Data cleaning and validation project preparing historical restaurant-menu data for reliable analysis."
collection: portfolio
header:
  teaser: pic4.png
---

## Project Description

Historical restaurant-menu data provides valuable insights into food pricing, dining trends, and consumer behavior over time. However, large historical datasets often contain missing values, inconsistent currencies, invalid dates, and unreliable pricing information, making accurate comparisons difficult. This project addresses these challenges by cleaning and preparing the **New York Public Library (NYPL) What's on the Menu dataset**, which contains historical restaurant-menu records from the mid-1800s through the modern era. The primary goal was to improve data quality and establish a reliable foundation for comparing restaurant-menu prices across comparable historical periods.

Using **OpenRefine, Python, Pandas, and SQL**, my team and I developed a multistage data cleaning and validation workflow across four related datasets: Menu, MenuPage, MenuItem, and Dish. My primary responsibility involved using OpenRefine to profile the datasets, identify missing values, inconsistent currencies, invalid dates, pricing anomalies, and unnecessary attributes, and apply initial cleaning and scope filtering. The team also developed Python-based transformations and SQL validation procedures to standardize values, preserve relational integrity, and verify data consistency. The project involved preparing over 1.3 million menu-item records and restricting the final analytical scope to records with usable dates and valid prices in U.S. dollars. These efforts established a cleaner, more consistent dataset for subsequent historical pricing analysis.

The primary stakeholders for this project include **historical researchers, economic analysts, data archivists, and cultural heritage organizations** interested in studying long-term restaurant pricing and dining patterns. The cleaned dataset supports future analytical decisions about which historical records are suitable for comparison, how restaurant-menu prices differ across time periods, and which data quality limitations must be considered before drawing conclusions. Although the broader project envisioned categorizing menus into relative price ranges, its primary deliverable focused on cleaning and validating the data needed for such analysis. By improving data accuracy, consistency, and traceability, the project demonstrates how effective data preparation supports reliable research, reduces the risk of misleading conclusions, and transforms complex historical records into a more usable analytical resource.

**Technologies:** OpenRefine, Python, Pandas, SQL, SQLite, Data Cleaning, Data Validation

**Dataset:** [NYPL What's on the Menu](https://menus.nypl.org/)

**Project Repository:** [View on GitHub](https://github.com/charlene-khun/cs513Project)

