

# Supermarket Sales Analysis

## About This Dataset
This dataset contains transactional information from a supermarket across three different branches. It includes details about individual sales, such as product line, unit price, quantity, payment method, customer demographics (customer type, gender), and ratings. The data spans a period, allowing for the analysis of sales trends and customer behavior.


## Problem Statement
The objective of this analysis is to explore and visualize various aspects of the supermarket sales data. By identifying key trends, customer preferences, and product performance, this analysis aims to offer actionable insights that could help improve sales strategies, optimize inventory, and enhance customer experience in the supermarket industry.

## Solution Approach

### Data Gathering
The dataset was obtained from Kaggle's [Supermarket Sales Dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales). The dataset includes the following key columns:
- **Product name**, **Product line**, and **Category**
- **Customer information** (e.g., gender, type)
- **Transaction details** (e.g., time, date)
- **Sales data** (e.g., quantity, total)

### Data Cleaning
- Converted the **Date** column to `datetime` format for easier analysis.
- Extracted additional date-time features such as **Day**, **Month**, **Year**, **Hour**, and **Minutes**.
- Checked for missing or null values and addressed them.
- Converted categorical data into a more suitable format for analysis.

### Exploratory Data Analysis (EDA)
- **Branch Performance**: Analyzed the total sales by branch, providing insight into the supermarket's geographical performance.
- **City-wise Sales**: Compared sales across different cities to understand regional performance.
- **Product Sales**: Explored sales distribution by product category, identifying which products are most popular.
- **Customer Demographics**: Analyzed customer types (e.g., member vs. non-member) and gender across sales.
- **Payment Methods**: Examined the preferred payment methods and their correlation with sales.
- **Time-based Trends**: Investigated how sales vary over different days of the week and times of day.



### Insights and Trends
- **Branch Performance**: Certain branches perform significantly better in terms of total sales, and this information can help optimize resource allocation.
- **Product Insights**: Certain product categories generate higher sales, indicating customer preferences.
- **Payment Preferences**: Different payment methods are used by different customer types, which can influence payment processing strategies.
- **Time-based Patterns**: Sales fluctuate depending on the day of the week, which can help forecast demand and optimize staffing and stock levels.

## Conclusion
The analysis of this dataset provides valuable insights into the supermarket's operations, customer behavior, and product performance, which can inform strategic decision-making.
