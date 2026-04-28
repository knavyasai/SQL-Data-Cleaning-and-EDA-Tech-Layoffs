# Tech Layoffs: Data Cleaning & Exploratory Analysis

## Project Overview
This project involves a deep dive into a raw dataset of tech layoffs from 2020 to 2023. The goal was to transform a "dirty" dataset into an analysis-ready format and extract meaningful business insights using advanced SQL techniques.

## Key Features
* **Data Engineering:** Removed duplicates, standardized inconsistent naming conventions, and reformatted date types for time-series analysis.
* **Advanced SQL:** Utilized CTEs (Common Table Expressions), Window Functions (`DENSE_RANK`, `SUM OVER`), and Self-Joins.
* **Visualization:** Developed cumulative rolling total charts and categorical breakdowns to visualize the "layoff wave."

## The Workflow
1. **Data Cleaning:**
    - Deduplication via `ROW_NUMBER()`
    - Text standardization (Trim, Like patterns)
    - Handling null values through relational joins
2. **EDA (Exploratory Data Analysis):**
    - Identifying peak layoff periods
    - Ranking top-impacted companies by year
    - Industry-wide impact assessment

## Key Insights
- **The Peak:** Layoffs peaked in early 2023, surpassing the combined totals of previous years.
- **Top Sectors:** The Retail and Consumer industries were hit hardest by volume.
- **Company Leaders:** Large-cap tech firms like Amazon and Google showed the highest total layoff counts.

## Tech Stack
- **SQL** (SQLite/BigQuery flavor)
- **Python** (for environment orchestration)
- **Google Colab**
- **Matplotlib/Seaborn** (Visuals)
