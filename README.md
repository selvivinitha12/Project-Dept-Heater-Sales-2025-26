Excel Data Cleaning + Power BI Dashboard Project

This project demonstrates a complete end-to-end data analysis workflow using Microsoft Excel for data cleaning and transformation, and Power BI for interactive dashboard creation, modelling, and business insights generation. The analysis is based on Project Dept – Heater Sales (2024–2025).

📁 1. Project Overview

This project focuses on:

Cleaning, transforming, and validating raw sales data using Excel
Creating structured fact and dimension tables
Handling missing values, duplicates, and formatting issues
Building a fully interactive Power BI Dashboard
Deriving insights on yearly sales, branch performance, material sales, customer behaviour and profitability

Objective:
To analyze heater sales performance across branches, understand revenue trends, customer segments, product categories, and profit insights for the years 2024–2025.

📚 2. Data Sources
Source	Description
Sales Dataset	Heater Sales Yearly Wise (2024–2025)
Data Type	Real-time sales data
Domain	Sales & Revenue Analytics
🎯 3. Problem Statement

The organization requires:

A clear understanding of yearly heater sales
Comparison between 2024 vs 2025
Branch-wise and model-wise sales behaviour
Identification of high-value customer groups
Insights for inventory planning, production, and future forecasting
🗂️ 4. Attribute (Column) Details

The dataset includes:

Sales Office
Branch Name
Customer Details
Material & Product Descriptions
Quantity
Billing Date & Year
Invoice Numbers
Net Value, Unit Price, GST Amount
Total Amount (With GST)
Product Category
Profit Status
Material Codes

(Refer to PDF for full column list.)

🧹 5. Data Exploration (Excel)
Key Metrics
KPI	Value
Total Sales Transactions	966
Total Sales Amount (Including GST)	₹22.90 Cr
Total Net Sales (Excl. GST)	₹19.40 Cr
Average Sales Amount (Including GST)	₹2,37,069
Average Sales Amount (Net)	₹2,00,884
Average Quantity per Order	43 Units
Most Sold Product Code	501300
Most Popular Category	STORAGE
Year-Wise Sales (2025)	₹12.66 Cr
Year-Wise Sales (2024)	₹10.24 Cr
Branch-wise Sales Contribution
Delhi Branch – ₹8.01 Cr
Chennai Branch – ₹3.33 Cr
Mumbai Branch – ₹3.96 Cr
Model-wise Sales
25GH-L → ₹4.06 Cr
25GH-R → ₹4.38 Cr
🛠️ 6. Excel Data Pre-Processing

Tasks performed:

✔ Removed duplicates
✔ Standardized date formats
✔ Applied proper case to text fields
✔ Created dimensional tables: Material Price Table
✔ Performed VLOOKUP to merge branch information
✔ Built pivot tables and charts
✔ Created fact table for Power BI modelling

📈 7. Power BI Modelling
Transformations & DAX Used
Converted Branch Name to UPPERCASE
Created Location column (Sales Office + Branch)
Built relationships between:
Cleaned Data Sheet
Material Code Price Table
Created Profit Status (Profit/Loss) column
Grouped data by branch for aggregate revenue
Created calculated columns for:
Total Amount Spend
Revenue After Expense
Profit Status Highlight
📊 8. Power BI Visualizations
Dashboard includes:
Year-wise Sales Trend Line Chart
Branch-wise Sales Stacked Column
Material Code-wise KPI Chart
Pie Chart (GST vs Spend Distribution)
Map Visualization (Branch Revenue Locations)
Model-wise Revenue Chart
Customer Segmentation
Profit Status Slicer
🧾 9. Summary of Insights
Sales increased by ₹2.4 Cr from 2024 to 2025.
Delhi, Chennai, and Mumbai are top revenue contributors.
Storage category dominates, showing 97% customer preference.
High-value models 25GH-L and 25GH-R generate maximum revenue.
Branch-wise customer count highest in Chennai.
Geographic analysis shows strong metro coverage.
🏁 10. Conclusion

The analysis confirms:

Strong and growing sales performance
High dependency on a few models and key branches
Healthy profit margins and consistent customer buying patterns
Opportunities exist for:
Expanding low-performing branches
Rebalancing inventory
Promoting high-demand materials
Strengthening customer segmentation strategy
