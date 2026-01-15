# BlinkIT Data Analysis Project

**Author:** Sebastian Ortuno Barrero  
**Tools Used:** Python (Pandas, Matplotlib, Seaborn, NumPy)

## * Project Overview

BlinkIT is a fast-growing online grocery delivery platform in India, known for providing essential household items and groceries with rapid delivery. Operating through a network of local outlets, BlinkIT connects consumers with nearby stores, offering convenience and speed as its core value proposition.

This project delivers a comprehensive sales analysis through a structured data science workflow designed to uncover business insights. Utilizing a dataset of over 8,500 records, the analysis progresses through data import, exploration, cleaning, KPI calculation, and visualization. The objective is to support strategic decision-making by identifying key trends in product performance, outlet efficiency, and customer preferences. The insights gained provide valuable guidance for inventory management, marketing strategies, and outlet optimization.

---

## * Business Requirements

1. Import and Load Data  
2. Explore the Dataset  
3. Clean the Data  
4. Calculate Key Performance Indicators (KPIs)  
5. Visualize the Data
   - 5.1 Total Sales by fat content
   - 5.2 Total sales by Item Type
   - 5.3 Fat Content by Outlet for Total Sales
   - 5.4 Total Sales by Outlet Establishment
   - 5.5 Sales by Outlet Establishment
   - 5.6 Sales by Outlet Location
6. Business Insights

---

## * Dataset Description

The dataset includes 8,523 rows and 12 columns, covering:

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

- **5.1 Pie chart: Sales by Fat Content**
   
![image](https://github.com/user-attachments/assets/27eab138-8c11-40de-bd1a-acd525f1d8c4)

- **5.2 Bar chart: Sales by Item Type**
  
![image](https://github.com/user-attachments/assets/bea118d4-8346-4b54-bc99-3ab0349e17ec)

- **5.3 Grouped bar chart: Fat Content Sales by Outlet Tier**
  
  ![image](https://github.com/user-attachments/assets/14580986-3ce4-4ce0-9134-3631812c17d3)

- **5.4 Total Sales by Outlet Establishment**
![image](https://github.com/user-attachments/assets/c84e69ee-10ba-49a1-b565-d875d05dfdef)

- **5.5 Sales by Outlet Establishment**
  ![image](https://github.com/user-attachments/assets/ee2357be-5bfb-44c1-a682-4d0a7af6a190)
- **5.6 Sales by Outlet Location**
  ![image](https://github.com/user-attachments/assets/09108f12-6e59-46b8-b46b-031ab6972d68)


## **6. Business Insights**

The sales analysis reveals clear and impactful insights that challenge common assumptions and open opportunities for strategic growth:
- * Contrary to expectations, larger outlets are not the top performers, and Low Fat items show a clear customer preference.
- * Low Fat items dominate, contributing over 64% of total sales, confirming a strong consumer preference for healthier options.
- * Fruits & Vegetables lead item type sales, followed closely by Snack Foods. This is a sign to prioritize inventory and marketing for these categories.
- * Tier 3 outlets and medium-sized stores outperform all others in total sales, proving that size and tier do not guarantee success.

---


