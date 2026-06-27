# California County Spending Efficiency Dashboard

**Author:** Karen Wu
**Date:** June 2026


## Overview
Analysis of FY2024 revenue and expenditure data across all 57 California counties using the State Controller's public financial dataset, to identify spending efficiency patterns by county size.

## Key Finding
Excluding Alpine County's extreme population skew, small counties (under 50K population) 
average the highest per-capita budget surplus at $347, followed by large counties 
(250K+) at $153, with medium counties (50K-250K) running the thinnest margins at 
just $47 per capita — challenging the assumption that larger counties operate 
less efficiently.

## Methodology
1. Pulled revenue and expenditure per-capita data from the CA State Controller's open data portal
2. Merged datasets by county and fiscal year in Python (pandas)
3. Segmented counties into population tiers (Small/Medium/Large) for fair comparison
4. Identified and excluded Alpine County as a statistical outlier (population ~1,200) 
   before calculating tier averages
5. Built an interactive dashboard in Tableau Public

## Tools Used
- Python (pandas) — data cleaning and analysis
- Tableau Public — visualization and dashboarding

## Data Source
[California State Controller's Office — Local Government Financial Data](https://lab.data.ca.gov)

## View the Dashboard
[Live interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/karen.wu6142/viz/CA_County_Spending_Efficiency_FY2024_KWu/Dashboard1)

## Files
- `notebooks/county_spending_analysis.ipynb` — full data cleaning and analysis process
- `data/county_spending_efficiency_2024.csv` — cleaned dataset used for visualization
- `dashboard_screenshot.png` — static preview of the final dashboard
