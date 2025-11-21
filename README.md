# Global Economy Analysis Dashboard

A professional, beginner-friendly Power BI dashboard that analyzes key global economic indicators — including Cost of Living Index, Rent Affordability, Local Purchasing Power, Restaurant Price Index, Groceries Index, and an aggregated Value Score by country. This repository contains the Power BI file, an exploratory analysis notebook, and a screenshot of the dashboard.

Repository: https://github.com/Nexux69/Economy-analysis/tree/main

![Dashboard Screenshot](./Dashboard eco.png)

---

## Overview
This project brings together multiple datasets to build an interactive Power BI dashboard for comparing countries on cost, affordability, and purchasing power measures. It is designed for analysts, students, and decision-makers who want a fast, visual way to explore country-level economic indicators and derive actionable insights.

Key goals:
- Present intuitive visual comparisons between countries and regions.
- Highlight affordability and relative value across global markets.
- Provide a reproducible analysis pipeline for future data updates.

---

## Features
- Interactive Power BI dashboard (.pbix) with filters and cross-highlighting
- Multiple coordinated visualizations for comparative analysis
- Exploratory Jupyter notebook for data preprocessing and experimentation (analysis.ipynb)
- Clean, exportable visuals suitable for reporting and presentations

---

## Dataset Description
The analysis uses multiple country-level indicators such as:
- Cost of Living Index
- Rent Affordability
- Local Purchasing Power Index
- Restaurant Price Index
- Groceries Index
- Value Score (derived/aggregated metric combining the above)

Notes:
- Each dataset should contain a country identifier to enable joins/merges.
- The repository contains the processed data embedded in the Power BI file or used by the supplied notebook (see analysis.ipynb for preprocessing steps).

---

## Visualizations Included
- KPI tiles showing aggregated sums/averages (e.g., total Cost of Living Index)
- Bar charts comparing metrics by country and region
- Donut (ring) charts showing breakdowns by region
- Line / scatter visuals showing relationships (e.g., Restaurant Price Index vs Groceries Index)
- Horizontal bar chart for Value Score by country

Short note on Power BI visuals used:
- Bar charts (vertical and horizontal) — for ranking and comparison
- Donut charts — for regional distribution and share
- Line / scatter charts — for trend/relationship visualization
These are standard Power BI visuals (built-in) that support interactivity and filtering.

---

## Insights Derived
- Certain countries consistently appear at the top for Cost of Living Index, indicating higher consumer prices relative to other countries.
- Value Score highlights countries that offer higher relative value when comparing local purchasing power against cost indices.
- Regional donut charts show how cost and affordability vary by region (e.g., Europe vs Asia vs Others).
- The relationship between Groceries and Restaurant Price Index can reveal consumption cost patterns and potential outliers.

Use these insights as starting points for deeper investigations — e.g., drilling into policy impacts, wage comparisons, or longitudinal changes if time-series data is available.

---

## How to Use
Step-by-step instructions for running / viewing the dashboard:

1. Clone the repository:
   - git clone https://github.com/Nexux69/Economy-analysis.git
2. Open the Power BI file:
   - Launch Power BI Desktop (recommended latest release).
   - Open `Dashboard.pbix` from the repository root.
3. Inspect visuals and filters:
   - Use slicers/filters to focus on specific countries, regions, or metrics.
   - Click bars or donut segments to cross-filter other visuals.
4. Refresh data (if you update source files):
   - If you add new data sources, use Transform Data to load and apply your changes.
   - Refresh the report to recalculate visuals.
5. (Optional) Publish:
   - Sign in to Power BI Service and publish the report to share with others (Power BI Pro may be required depending on sharing settings).
6. Review the exploratory notebook:
   - Open `analysis.ipynb` in JupyterLab/Notebook to see preprocessing and any derived metric calculations that feed the dashboard.

Troubleshooting tips:
- If Power BI cannot find data sources, open Transform Data to relink files or re-run the notebook to regenerate processed data.
- For large datasets, consider optimizing data model columns and reducing unnecessary visuals to improve performance.

---

## Requirements / Tools Used
- Power BI Desktop (required to open and edit .pbix)
- Python 3.x (optional, if re-running preprocessing)
  - pandas, numpy, jupyter (used in analysis.ipynb)
- Git (for cloning repository)
- (Optional) Power BI Service for publishing and sharing

---

## Folder Structure
- Dashboard.pbix — Power BI report file (main dashboard)
- Dashboard.png — Dashboard screenshot used in README
- analysis.ipynb — Jupyter notebook with exploratory analysis and preprocessing
- README.md — Project documentation (this file)

---

## Future Improvements
- Add raw dataset files and a data ingestion script to make the pipeline fully reproducible
- Implement a small ETL script (Python) to automatically refresh and standardize new data
- Add time-series analysis and trends if historical data is available
- Enhance accessibility and tooltips for clearer context on each visual
- Include additional metrics (e.g., median income, inflation-adjusted measures) for deeper analysis
- Add automated tests or validations for the data merging steps

---

## License
This project is provided under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, subject to the conditions of the MIT License.

(If you prefer a different license, replace this section with your chosen license text.)

---

If you want, I can:
- Expand the README with examples of common filter workflows,
- Add a CONTRIBUTING.md template or a LICENSE file to the repo,
- Or generate a short changelog and versioning recommendations.
