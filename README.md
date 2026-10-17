# Retail Sales Performance Dashboard

## 1. Project Overview

The Retail Sales Performance Dashboard is a business intelligence project developed using Microsoft Power BI. The purpose of this project is to analyze retail sales data, monitor sales and profit performance, compare product categories and regions, and identify useful business insights.

## 2. Dataset

- **Dataset:** `retail_sales_dataset.csv`
- **Original row count:** 4,310
- **Current Sales table row count:** 4,112
- **Number of columns:** 21 in the original dataset
- **Tool used:** Microsoft Power BI Desktop

The dataset contains information about orders, customers, products, sales amounts, profit, discounts, shipping costs, customer satisfaction, returns, and order status.

## 3. Data Cleaning and Preparation

The dataset was imported into Power BI for preparation and analysis.

The following data-quality areas were considered:
- Missing and null values.
- Duplicate records and blank rows.
- Inconsistent date formats.
- Inconsistent category and text values.
- Appropriate data types for numeric and date columns.

**Note:** The original dataset contained 4,310 rows, while the current Sales table contains 4,112 rows. The exact reason for the difference should be confirmed from the Power Query Applied Steps before submission.

Only describe cleaning operations that were actually performed.

## 4. Data Modeling

The project uses three tables:

- **Sales:** Contains order-level sales, profit, quantity, product, and customer information.
- **Customers:** Contains customer information such as customer ID, name, age, city, region, and gender.
- **Products:** Contains product keys, product names, and product categories.

Relationships connect the Sales table to the Customers and Products tables. The relationship columns and cardinality were checked in Model view.

## 5. Measures and Calculated Column

The following DAX measures were created:

- **Total Sales:** Calculates the sum of sales amounts.
- **Total Profit:** Calculates the sum of profit.
- **Average Sales:** Calculates the average sales amount per row.
- **Total Records:** Counts the rows in the Sales table.
- **Maximum Sale:** Returns the highest sales amount.
- **Minimum Sale:** Returns the lowest sales amount.
- **Profit Margin:** Calculates total profit divided by total sales.

A calculated column named **Sales Band** was also created to classify sales into three categories.

## 6. Dashboard Visualizations

The dashboard contains:

- KPI cards for Total Sales, Total Profit, Total Records, Average Sales, and Profit Margin.
- A bar chart showing Profit by Region.
- A column chart showing Sales by Product Category.
- A line chart showing the Monthly Sales Trend.
- A donut chart showing Sales Share by Category.
- An Order Date slicer.
- A Product Category slicer.

These visuals help users compare performance and explore the data interactively.

## 7. Business Insights

Based on the unfiltered dashboard screenshot:

- Total Sales are approximately 240.84 million.
- Total Profit is approximately 46.12 million.
- The overall Profit Margin is approximately 19.15%.
- Electronics is the largest sales category, contributing approximately 134 million, or 55.64% of total sales.
- Furniture contributes approximately 55.89 million, or 23.21% of total sales.
- Sports contributes approximately 31.01 million, or 12.88% of total sales.
- The regional profit chart indicates differences in profit performance across regions.

These findings are based on the displayed dashboard values and should be rechecked against the final unfiltered report before submission.

## 8. Recommendations

1. Investigate Electronics sales to understand which products contribute most to its strong performance.
2. Review Furniture and Sports performance to identify opportunities for profitable growth.
3. Compare regional profitability to identify successful practices that may be applied to other regions.
4. Monitor profit margin alongside sales revenue to avoid focusing on revenue alone.
5. Continue monitoring sales trends and customer satisfaction to support business decisions.

## 9. Project Files

- Power BI report: `Week5 Assignment.pbix`
- Dataset: `retail_sales_dataset.csv`
- README: `README.md`
- Screenshots: `Screenshots/`

## 10. Conclusion

This project demonstrates the use of Power BI for data preparation, data modeling, DAX calculations, data visualization, and interactive business reporting. The dashboard provides a consolidated view of retail sales and profitability to support data-driven decisions.