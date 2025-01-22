# Sales Analysis

Data source: [Customer Shopping Latest Trends Dataset](https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset/data)

## Overview

This project involves the analysis of a sales dataset obtained from Kaggle. The primary goal is to explore the data and answer key business questions related to sales performance, customer behavior, and regional trends.

## Dataset

The dataset used in this analysis is from **[Kaggle](https://www.kaggle.com/)**. It includes sales transaction and customer information such as:

- **Age**
- **Gender**
- **Item Purchased**
- **Category**
- **Purchase Amount (USD)**
- **Location**
- **Size**
- **Color**
- **Season**
- **Review Rating**
- **Subscription Status**
- **Payment Method**
- **Shipping Type**
- **Discount Applied**
- **Promo Code Used**
- **Previous Purchases**
- **Preferred Payment Method**
- **Frequency of Purchases**

For more details, refer to the original Kaggle dataset.

## Research Questions

The analysis addresses the following key questions:

1. **What period recorded the highest revenue?**
2. **What products do subscribers purchase the most?**
3. **Which state had the highest and lowest sales?**
4. **Which state sold the most in each product category?**
5. **Which state recorded the highest sales in different seasons?**

## Methodology

The analysis follows these main steps:

1. **Data Cleaning**: Removing unnecessary formulas, adjusting formats in columns, checking for duplicate values and empty cells, and ensuring the data is ready for analysis.
2. **Exploratory Data Analysis (EDA)**: Investigating the data using statistical methods and visualizations.
3. **Answering Research Questions**: Using the data to answer the specific questions outlined above.
4. **Visualizations**: Creating pivots and charts to illustrate key insights and trends.

## Visualizations

Below are some of the key visualizations generated during the analysis:

### 1. Revenue by Period
![Revenue by Period](Sales_Analysys/images/revenue_by_period.png)
This chart shows the total revenue for each season, helping identify when the highest revenue was generated.

The highest revenue was generated in fall. If we take a closer look at shopping trends, 43.69% of revenue in the fall comes from clothing sales. In the fall, 34% of buyers were women (compared to the number of buyers for the whole year, where the share of women is 32%).

What distinguishes fall shoppers is that the largest portion of them are annually returning customers.

### 2. Most Purchased Products by Subscribers

This bar chart illustrates the most frequently purchased products by subscribers, highlighting customer preferences.

### 3. Sales by State

This pivot shows the total sales in each state, helping identify which states had the highest and lowest sales.

The state of Montana had the highest revenue, followed by Illinois and California. The state of Kansas was the weakest, providing 1.47% of the revenue amount.

### 4. State Sales by Category

By category, the following states recorded the highest revenue:

- **Clothing**: Montana
- **Outerwear**: North Dakota
- **Accessories**: Nebraska
- **Footwear**: Ohio

### 5. Seasonal Sales Trends by State

This chart tracks the sales by state across different seasons, showing which season had the highest sales in each region. For instance, Montana experienced peak sales in Fall, while Ohio saw higher sales during Summer.

## Key Insights

From the analysis, the following key insights were uncovered:

- **Period of Highest Revenue**: The highest revenue was recorded in Fall, where the biggest portion of customers were annually returning shoppers.
- **Subscriber Purchases**: Subscribers most frequently purchase clothing. 100% of subscribers are males. Due to the lack of sufficient source data, at this stage of the analysis, we cannot determine the reason for the lack of female subscribers.
- **Sales by State**: Montana had the highest sales, while Kansas had the lowest. This may be due to easier expansion in a less populated state, as the company does not have to compete with more famous brands in better-populated states.

## Conclusion

This analysis provided valuable insights into sales trends, customer preferences, and regional differences. By understanding customer behavior, including the most popular products and sales patterns, businesses can make more informed decisions regarding marketing strategies, inventory management, and customer engagement.
