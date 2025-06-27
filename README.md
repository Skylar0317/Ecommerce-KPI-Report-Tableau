# Ecommerce KPI Report (Tableau + Python)

This project is a comprehensive analytics workflow developed for the FP20 Analytics Challenge 19. It includes Python-based data preparation and a Tableau dashboard analyzing key performance indicators (KPIs) in the global skincare and beauty e-commerce market from 2020 to 2023.

## Project Overview

The analysis explores:

- Profit and sales trends by region, category, subcategory, and product
- Discount effectiveness and impact on profit margins
- Top products and customers by country and year
- Yearly KPI performance compared with business targets

## Data Preparation (Python)

A Jupyter notebook (`Data Preperation.ipynb`) was used to clean and format the dataset prior to visualization.

Steps included:

- Converting order dates and extracting year
- Ensuring numeric columns (`Sales`, `Profit`, `Discount`, `Quantity`) are valid
- Removing rows with critical missing values
- Exporting a clean CSV file for use in Tableau

## Dashboard (Tableau)

The Tableau report includes:

- Interactive charts showing profit and sales performance by market and segment
- Drill-downs by category, subcategory, and product
- Discounted vs non-discounted order analysis
- Top 10 customers by region and year
- Global profit distribution map

## Tools Used

- Python (Pandas, Jupyter Notebook)
- Tableau
- Data source: Global skincare and beauty e-commerce dataset

## Acknowledgments

This project was built as part of the FP20 Analytics Challenge 19. ZoomCharts visuals were recommended for advanced interactivity.

