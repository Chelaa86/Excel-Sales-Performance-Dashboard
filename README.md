# Sales Performance Dashboard

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Findings](#findings)
- [Recommendations](#recommendations)

## Project Overview
This project was developed as part of the projects we get to do in the mentorship program at the **School of Statisticians - Kenya**. The goal was to build an interactive Excel dashboard that provides actionable insights from sales data. 

The dashboard includes time-based sales performance, product-level insights, regional sales breakdown, and key order metrics; designed to support data-driven decision-making. Users can interact with the dashboard using slicers to filter by region, product category, and date range.

![excel_dashboard_screenshot](https://github.com/user-attachments/assets/2a76408a-9b9f-4fa7-b482-e2c294d610c3)

## Data Sources
The dataset used in this project was provided by the **School of Statisticians - Kenya** as one of the weekly projects. It contains fictional sales data including:

- Order ID
- Order Date
- Product Category & Sub-category
- Customer Region
- Units Sold
- Unit Price
- Sales Revenue

## Tools Used
**Microsoft Excel**: The entire analysis and dashboard were created using Excel.

## Data Cleaning
Before starting the analysis and building the dashboard, the dataset went through the following cleaning steps:

1. **Created a Table**: 
   - The raw data was converted into an Excel Table format (`Ctrl + T`) to enable better organization and easy referencing.

2. **Data Formatting**: 
   - Ensured consistent formatting for dates, currencies, and numerical values to avoid errors during analysis. 
   - Date columns were formatted as `Date`, sales-related columns as `Currency`, and numerical columns for units sold were set to `Number`.

3. **Checked for Duplicates**:
   - Used Excel's `Remove Duplicates` feature to eliminate any repeated rows that could skew analysis.
   - There were no duplicates found.

4. **Checked for Missing Values**: 
   - Utilized the `Filters` by column to check for blanks.
   - There were no missing values found.

## Exploratory Data Analysis
To gain insights from the dataset, the following questions were explored:
- What is the total sales revenue over time?
- Which month had the highest sales?
- Which product category generate the most sales?
- What are the top 5 sub-categories by sales revenue?
- Which product have the highest units sold vs highest revenue?
- Which customer region contributes the most to total sales?
- How does each region perform across different product categories?
- What is the average order value (AOV)?
- What is the average unit price by category and region?
- Can users filter by region, category, or date range?

## Data Analysis and Visualization
Data analysis and visualization were performed entirely in **Microsoft Excel** using a combination of built-in tools to uncover patterns and trends in the sales data. The key Excel tools used include:

- **Pivot Tables**: 
  - Used to summarize and analyze large datasets efficiently.
  - Enabled quick grouping by date, product, and region.

- **Pivot Charts**:
  - Created visual representations such as line charts, bar charts, pie charts, and stacked columns.
  - Automatically updated based on changes in pivot table filters.

- **Slicers**:
  - Enabled interactive filtering by dimensions such as region, product category, and date range.
  - Enhanced user experience for dashboard exploration.

- **Data Sorting and Filtering**:
  - Used throughout to organize sub-category rankings, identify top-performing products, and clean the dataset.

These tools were integrated into a structured and interactive dashboard that allows users to slice the data and gain insights quickly.

## Findings

Based on the interactive Excel dashboard, the following insights were drawn from the sales data:

### Sales Performance
- **Total Sales Revenue Over Time**: Sales revenue showed a slightly downward trend across the days.
- **Highest Sales Period**: The month of **March** recorded the highest total sales.

### Product Insights
- **Top Performing Category**: The **Electronics** category generated the highest overall sales.
- **Top 5 Sub-Categories by Sales**:
  1. Shoes
  2. Shirt
  3. Phone
  4. Cookware
  5. Laptop

### Regional Analysis
- **Top Sales Region**: The **North region** contributed the most to overall sales.
- **Regional vs. Product Category Performance**: **Clothing** performed best in the **South region**.

### Order Metrics
- **Average Order Value (AOV)**: The average order value across all transactions was approximately **2466.51**.
- **Average Unit Price**: Highest in the **Electronics** category in the **West region**.

### Interactivity
- **Filters Available**: Users can explore the dashboard by applying slicers for:
  - **Region**
  - **Product Category**
  - **Date Range**
 
## Recommendations

Based on the findings from the Excel dashboard, here are several recommendations to enhance sales performance and drive data-driven decision-making:

1. **Focus on High-Performing Product Categories**:
   - The **Electronics** and **Clothing** categories have the highest sales, so focusing on these categories during promotional campaigns could yield significant revenue.
   - Consider expanding inventory or launching targeted marketing campaigns around these categories.

2. **Targeting Sub-Categories for Growth**:
   - The top-selling sub-categories, such as **Shoes** and **Shirt**, should be prioritized for future investments in product lines, as they generate the most revenue.
   - Evaluate customer preferences and explore bundling options to increase sales of these high-margin products.

3. **Regional Expansion and Targeted Marketing**:
   - The **North region** contributed the most to total sales, suggesting that regional marketing efforts and tailored offers in that area could maximize growth.
   - Conversely, the **South region** underperformed, which presents an opportunity to understand customer behavior and tailor products and promotions to improve sales in that region.

4. **Leverage Interactive Dashboards for Business Strategy**:
   - Use the interactive dashboard to continuously monitor sales performance and adjust marketing or inventory strategies based on real-time data.
   - Encouraging team members or stakeholders to use the dashboard with filters for region, product category, and date range can help create targeted reports for specific needs.

5. **Seasonal Promotions and Strategic Timing**:
   - The highest sales during **March** suggests that this could be an ideal time to run special promotions or launch new products. Planning campaigns well in advance of peak months will help optimize sales during these times.

6. **Improve Data Quality and Maintenance**:
   - Regularly clean and update the data to avoid issues like duplicates or missing values. This will ensure the accuracy and reliability of future analyses and dashboard updates.








