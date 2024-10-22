# eCommerce Sales Dashboard

## Overview
This dashboard provides a detailed analysis of eCommerce performance, allowing users to explore sales, order distribution, customer demographics, and geographical performance across various platforms.

## Dashboard Breakdown
1. **Orders vs Sales**  
   This bar chart compares the total orders against the sales amount for each month. Users can filter the data based on months, providing insight into sales trends.

2. **Sales by Gender (Men vs Women)**  
   A pie chart that illustrates the percentage of sales contributed by male and female customers. This can help assess gender-based performance in sales campaigns.

3. **Order Status**  
   This pie chart showcases the breakdown of orders by status, such as completed, pending, or canceled orders. It helps monitor the completion rate of orders.

4. **Top 5 States by Sales**  
   This horizontal bar chart displays the top 5 states contributing the highest sales. It allows for geographic analysis of sales performance.

5. **Orders by Age Group and Gender**  
   This clustered bar chart visualizes the order distribution across different age groups (Adult, Senior, Teenager) and further splits it by gender, showing sales patterns based on demographic.

6. **Orders by Channels**  
   The pie chart breaks down sales by eCommerce channels, such as Flipkart, Myntra, and Meesho, allowing for a comparison of performance across platforms.

## Features
- **Interactive Filters**:  
   Filters for Month, Sales Channels, and Category allow users to slice and dice the data, enabling them to see how sales differ by specific time periods, platforms, and product categories.

## Data Structure
The dashboard is built on a dataset containing the following key fields:
- **Month**: The month of the transaction.
- **Channel**: The sales platform (e.g., Flipkart, Myntra, Meesho).
- **Category**: The product category (e.g., Western Dress, Bottom, Ethnic Dress).
- **State**: The state where the order originated.
- **Sales Amount**: The total sales amount for each transaction.
- **Order Status**: The status of the order (e.g., Completed, Pending, Failed).
- **Gender**: The gender of the customer (Men/Women).
- **Age Group**: Age group of the customer (Adult, Senior, Teenager).

## How to Use
1. **Open the Excel File**:  
   Download and open the Excel workbook where the dashboard is saved.

2. **Interact with Filters**:  
   Use the filters on the left to change the Month, Sales Channel, and Category. The charts will dynamically update based on your selections.

3. **Analyze the Charts**:  
   Explore the various charts to understand the performance in terms of orders, sales, top-performing states, and customer demographics.

## Setup (Code/Steps)
To recreate this dashboard in Excel:
1. **Data Preparation**:  
   Ensure that your data includes columns for Month, Channel, State, Category, Sales Amount, Gender, Age Group, and Order Status.

2. **Create Pivot Tables**:  
   - Insert PivotTables for each metric (Orders vs Sales, Sales by Gender, Top 5 States, etc.) based on your data.
   
3. **Create Charts**:  
   - Insert bar charts, pie charts, and clustered bar charts using the PivotTables created in Step 2. Make sure to assign relevant fields to each chart (e.g., Month and Sales Amount for Orders vs Sales).

4. **Add Slicers/Filters**:  
   - Add slicers for Month, Channel, and Category to enable interactive filtering across all charts. Link them to the PivotTables to ensure dynamic updates.

5. **Format and Design**:  
   - Customize the design of the charts and dashboard to make it visually appealing, using colors, labels, and gridlines.

## Conclusion
This dashboard provides a comprehensive view of sales performance, customer demographics, and regional success, enabling business owners and analysts to make data-driven decisions to optimize their eCommerce strategy.
