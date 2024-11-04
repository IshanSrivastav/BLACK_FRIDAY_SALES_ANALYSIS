# Black Friday Sales Data Analysis

## Overview
Black Friday is one of the busiest shopping days of the year, marked by significant discounts and promotions. This project analyzes Black Friday sales data to gain insights that could guide marketing strategies, identify key customer segments, and optimize product offerings. The dataset contains **537,578 rows and 12 columns**.

## Project Goals
The goal of this project is to analyze various data columns to provide insights into customer demographics, purchasing behaviors, and product performance. The analysis is divided into several key sections for a structured approach.

## Prerequisites
- **Libraries**: `Pandas`, `NumPy`, `Seaborn`

---

## Project Structure

### 1. Dataset Walkthrough
Examines the dataset to understand its structure, including column names, data types, and the presence of null values. Null values in `Product_Category_2` and `Product_Category_3` were removed to avoid data loss in other columns.

### 2. Analyzing Columns
Uses `unique()` and `nunique()` functions to explore unique values in each column, helping us identify the distinct customers (`User_ID`), products (`Product_ID`), and demographic factors (`Gender`, `Age`).

### 3. Analyzing Gender
Focuses on the `Gender` column, revealing that male customers are more prevalent. We use `groupby` functions to compare purchasing trends by gender and visualize findings with pie and bar charts.

### 4. Analyzing Age & Marital Status
Analyzes the `Age` and `Marital_Status` columns to identify which age groups are the most active buyers and have the highest purchase amounts. This section also highlights that 60% of the dataset consists of unmarried individuals, shown via pie charts.

### 5. Multi-Column Analysis
Moves beyond single-column analysis by combining multiple columns for deeper insights. Using Seaborn, we create visualizations to explore patterns across demographics, with legends and `hue` parameters for enhanced clarity.

### 6. Occupation and Products Analysis
Examines `Occupation`, `Product_ID`, and `Product_Category_1` to identify popular occupations and top-selling products. We use `countplot` and bar plots to highlight trends and determine which products generate the highest sales.

### 7. Combining Gender & Marital Status
The final analysis section combines `Gender` and `Marital_Status` to discover patterns that appear when both demographics are considered together. This section uses Seaborn's `countplot` for comprehensive visualizations.

---

## Key Insights
1. **Customer Demographics**: Majority of the buyers are male, unmarried, and fall into specific age groups.
2. **Popular Products**: Identifying top-selling products and categories can help target promotions more effectively.
3. **Occupational Trends**: Certain occupations display higher purchasing patterns, providing insights for tailored marketing.

## Visualizations
Visualizations are created using Seaborn and Matplotlib to effectively present key findings, including gender distribution, age group behavior, and occupation-based trends.

