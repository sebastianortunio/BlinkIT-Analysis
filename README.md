# BlinkIT Data Analysis Project

**Author:** Sebastián Ortuño Barrero  
**Tools Used:** Python (Pandas, Matplotlib, Seaborn)

## * Project Overview

This project provides an end-to-end data analysis of a grocery sales dataset from BlinkIT. The primary goal is to address business requirements through structured data processing, KPI calculation, and data visualization.

---

## * Business Requirements

1. Import and Load Data  
2. Explore the Dataset  
3. Clean the Data  
4. Calculate Key Performance Indicators (KPIs)  
5. Visualize the Data  
6. Derive Business Insights

---

## * Dataset Description

The dataset includes **8,523 rows** and **12 columns**, covering:

- Item identifiers and types  
- Fat content categories  
- Sales data  
- Outlet characteristics (type, size, location, establishment year)  
- Item ratings and visibility

---

## * Key Steps

### 1. Data Import and Inspection

- Loaded the CSV file with Pandas  
- Previewed the dataset and reviewed dimensions  
- Verified data types and column integrity  

### 2. Data Exploration

- Identified inconsistencies in categorical columns (e.g., 'Low Fat' vs 'low fat')  
- Analyzed distributions and summary statistics

### 3. Data Cleaning

- Standardized inconsistent text formats  
- Removed duplicate rows  
- Verified null and missing values  

### 4. KPI Calculation

![image](https://github.com/user-attachments/assets/f3e7c2cc-970a-40dd-98fc-09d5a851a17e)


### 5. Data Visualization

Generated visual insights using Matplotlib and Seaborn:

- Pie chart: Sales by Fat Content
   
![image](https://github.com/user-attachments/assets/27eab138-8c11-40de-bd1a-acd525f1d8c4)

- Bar chart: Sales by Item Type
  
![image](https://github.com/user-attachments/assets/bea118d4-8346-4b54-bc99-3ab0349e17ec)

- Grouped bar chart: Fat Content Sales by Outlet Tier
  
  ![image](https://github.com/user-attachments/assets/14580986-3ce4-4ce0-9134-3631812c17d3)

- Total Sales by Outlet Establishment
![image](https://github.com/user-attachments/assets/c84e69ee-10ba-49a1-b565-d875d05dfdef)

- Sales by Outlet Establishment
  ![image](https://github.com/user-attachments/assets/ee2357be-5bfb-44c1-a682-4d0a7af6a190)


---


##  Conclusion

The sales analysis reveals clear and impactful insights that challenge common assumptions and open opportunities for strategic growth:
- * Contrary to expectations, larger outlets are not the top performers, and Low Fat items show a clear customer preference.
- * Low Fat items dominate, contributing over 64% of total sales, confirming a strong consumer preference for healthier options.
- * Fruits & Vegetables lead item type sales, followed closely by Snack Foods. This is a sign to prioritize inventory and marketing for these categories.
- * Tier 3 outlets and medium-sized stores outperform all others in total sales, proving that size and tier do not guarantee success.

---


