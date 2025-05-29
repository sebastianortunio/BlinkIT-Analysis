Data Analysis Python Projects - BlinkIT Analysis

Author: Sebastián Ortuño Barrero

Overview

This project showcases a data analysis conducted on a grocery sales dataset for BlinkIT. The analysis aims to address various business requirements through data exploration, cleaning, KPI calculations, and visualizations using Python.

Business Requirements

Import and Load Data
Explore the Dataset
Data Cleaning
KPI Calculation
Total Sales
Average Sales
Number of Items Sold
Average Ratings
Data Visualization
Sales by Fat Content
Sales by Item Type
Fat Content Sales by Outlet Tier
Sales by Establishment Year
Sales by Outlet Type
Sales by Outlet Location
Conclusion
Dataset

The dataset includes 8,523 entries and 12 features such as:

Item Identifier
Item Fat Content
Item Type
Outlet Identifier
Outlet Establishment Year
Outlet Size, Type, and Location
Item Visibility and Weight
Sales and Ratings
Key Steps in the Project

1. Import and Load Data
Loaded dataset using pandas and previewed first 20 entries. Verified data dimensions and data types.

2. Data Exploration
Identified inconsistencies in categorical fields such as 'Item Fat Content'. Reviewed data types, column names, and missing values.

3. Data Cleaning
Standardized inconsistent text values in 'Item Fat Content'.
Removed duplicates from the dataset.
4. KPI Calculations
Total Sales: $1,201,681.49
Average Sales: $140.99
Items Sold: 8,523
Average Rating: 3.97
5. Visualizations
Pie Chart for Sales by Fat Content
Bar Graph for Sales by Item Type
Grouped Bar Chart for Fat Content Sales by Outlet Tier
Additional charts for establishment year, outlet type, and outlet location were generated for deeper insights.
Conclusion

The analysis revealed key insights such as the dominance of Low Fat items in total sales and the leading performance of certain item categories like Fruits and Vegetables. Outlet characteristics such as tier, size, and location significantly influence sales patterns, helping BlinkIT make informed business decisions.
