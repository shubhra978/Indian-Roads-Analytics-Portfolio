Indian Roads Analytics Project Report

1. Introduction

This project demonstrates an end-to-end data analytics pipeline using Databricks, PySpark, SQL, Power BI, and Tableau. The dataset used is the Indian Roads dataset, which contains raw information about road lengths, conditions, traffic volumes, and accident counts across states and districts. The goal is to showcase data engineering, cleaning, KPI creation, and dashboarding skills in a professional portfolio.

2. Objectives

Ingest raw Indian Roads dataset into Databricks (Bronze layer).

Clean and transform data using PySpark (Silver layer).

Create curated KPI tables with SQL (Gold layer).

Build dashboards in Databricks SQL, Power BI, and Tableau.

Document the entire workflow in GitHub for reproducibility.

3. Methodology

Bronze Layer

Raw ingestion of CSV dataset into Databricks.

Schema inspection and storage.

Silver Layer

Flatten nested columns.

Handle missing values (imputation/drop).

Standardize units (km, traffic counts).

Normalize categorical values (road condition, state names).

Gold Layer

Curated KPI tables:

Road length by state/district.

Traffic vs accidents.

Road condition distribution.

Accident rate per 100 km.

Accident severity index.

Traffic per km ratio.

4. Dashboards

Databricks SQL Dashboard

KPI cards: accident rate per 100 km.

Bar chart: road length by state.

Line chart: traffic vs accidents.

Pie chart: road condition distribution.

Power BI Dashboard

Interactive slicers for state/district.

Drill-down into traffic vs accident trends.

KPI cards for road length and accident rates.

Tableau Dashboard

Heatmaps of accident density.

Trend lines for traffic vs accidents.

Storytelling dashboard combining multiple visuals.

5. Key Insights

States with highest accident rates per 100 km.

Distribution of road conditions across India.

Correlation between traffic volume and accident counts.

Districts with longest road networks.

6. Repository Structure

📂 Indian-Roads-Analytics-Portfolio
 ┣ 📂 datasets
 ┃ ┗ indian_roads_raw.csv
 ┣ 📂 notebooks
 ┃ ┣ bronze_ingestion.ipynb
 ┃ ┣ silver_cleaning_pyspark.ipynb
 ┃ ┗ gold_kpi_queries.sql
 ┣ 📂 dashboards
 ┃ ┣ databricks_dashboard_screenshots/
 ┃ ┣ powerbi_dashboard.pbix
 ┃ ┗ tableau_dashboard.twbx
 ┣ 📂 sql
 ┃ ┗ gold_queries.sql
 ┣ 📂 docs
 ┃ ┗ project_report.md
 ┣ README.md

7. Conclusion

This project highlights the ability to design and implement a complete data analytics pipeline. By combining Databricks, PySpark, SQL, Power BI, and Tableau, the portfolio demonstrates proficiency in data engineering, analytics, and visualization. The GitHub repository ensures transparency, reproducibility, and professional presentation for career advancement.