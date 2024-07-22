# Overview
This project demonstrates advanced data processing and visualization using Power BI, focusing on transforming raw data into actionable insights.

### Key Steps:
#### Data Preparation:

- Imported and transformed data from Excel.
- Renamed tables for clarity (Dim_account, Dim_product).
- Checked headers, removed duplicates, and cleaned column names.
- Fixed date columns for consistency.

#### Table Creation:

- Created Dim_date table using DAX: Dim_date = CALENDAR(DATE(2022,1,1), DATE(2024,12,31))
- Added Inpast column for past date identification.
- Created summary table (Slc Values) with Sales, Gross Profit, and Quantity.
- Added measures table for calculated metrics.

#### Measure Development:

- Calculated measures: Sales, Quantity, COGs, Gross Profit.
- Developed YTD and PYTD measures using TOTALYTD and SAMEPERIODLASTYEAR.
- Created dynamic slicer measures for comparative analysis.
- Calculated YTD vs. PYTD performance: YTD vs PYTD = [S_YTD] - [S_PYTD]

#### Model Organization:

Grouped measures into display folders: Base Measures, PYTD, YTD, Switch.

#### Dashboard Creation:

Designed interactive elements: slicers, cards, and visualizations.
Created visualizations: tree map, waterfall chart, stacked bar chart, scatter plot.

# Conclusion
This Power BI project showcases the ability to transform raw data into meaningful visualizations and insights, demonstrating proficiency in data analysis and business intelligence.
