Balaji Fast Food Sales — Interactive Power BI Dashboard

1. Business Question

How can sales data help Balaji Fast Food understand its revenue performance, identify top-performing products, analyse customer payment patterns, and compare sales across different shifts?

This project uses Power BI to analyse sales transactions and provide actionable business insights through an interactive dashboard.

2. Project Overview

This is an end-to-end Business Intelligence project developed using Microsoft Power BI.

The project analyses 1,000 sales transactions recorded between April 2022 and March 2023. It includes data cleaning, data transformation, data modelling, DAX calculations, and interactive dashboard development.

Important: The financial figures represent gross revenue, not profit, because product cost data is not available in the dataset.

3. Dataset

- Dataset: Balaji Fast Food Sales
- Source: Project-provided CSV dataset
- Total Records: 1,000
- Total Attributes: 10
- Period: April 2022 – March 2023
- Format: CSV

4. Tools Used

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- Microsoft Excel
- GitHub

5. Steps Followed

A. Data Loading and Inspection

- Imported the original CSV dataset into Power BI.
- Examined the dataset structure and column data types.
- Checked missing values and duplicate records.

B. Data Cleaning and Transformation

Performed data cleaning using Power Query:

- Standardised inconsistent date formats.
- Converted date values into a consistent date format.
- Identified and handled 107 missing transaction type/payment mode records (10.7%).
- Replaced missing values with "Not Recorded".
- Checked for duplicate transaction IDs.
- Verified data types and prepared the dataset for analysis.

Data quality findings:

- 1,000 records and 10 columns.
- Zero duplicate transaction IDs.
- 107 missing transaction type/payment mode records before cleaning.

C. Data Modelling

- Created a star schema data model.
- Used "Balaji_Sales" as the central fact table.
- Created dimension tables for Date, Product, and Shift.
- Established one-to-many relationships with single-direction filtering.

D. DAX Measures

Created 10 custom DAX measures:

1. Total Revenue
2. Total Orders
3. Total Quantity Sold
4. Average Order Value (AOV)
5. Average Item Price
6. Cash Orders
7. Online Orders
8. Recorded Digital Share
9. Monthly Revenue
10. Month-over-Month Revenue Growth

E. Dashboard Development

Developed a two-page interactive Power BI report with KPIs, charts, tables, and filters.

6. Key Insights

- Total Gross Revenue: ₹2,75,230
- Total Orders: 1,000
- Total Quantity Sold: 8,162
- Average Order Value: ₹275.23
- Average Item Price: ₹33.72

Product Performance

- Sandwich generated the highest revenue at ₹65,820.
- Frankie generated ₹57,500 in revenue.
- Cold Coffee recorded the highest quantity sold at 1,361 units.
- Sugarcane Juice followed with 1,278 units sold.

Shift Performance

- Night shift generated ₹62,075 in revenue.
- Afternoon shift generated ₹56,345 in revenue.

Payment Analysis

- Cash orders: 476.
- Online orders: 417.
- Recorded digital payment share: 46.7%.
- 107 transactions had unrecorded payment information, representing ₹31,240 in revenue.

Business Recommendation

Improve the recording of payment information to reduce missing transaction data. Focus on high-revenue products such as Sandwich and Frankie, and evaluate product availability and staffing across shifts to support sales performance.

7. Dashboard Pages and Screenshots

Page 1 – Sales Overview

Provides an overview of revenue, order volume, quantity sold, average order value, monthly revenue trends, category performance, and shift-wise revenue.

"Sales Overview" (page1_sales_overview.png)

Page 2 – Product and Transaction Analysis

Analyses payment methods, transaction patterns, staff and shift performance, product revenue, and quantity sold.

"Product and Transaction Analysis" (page2_product_analysis.png)

Data Model – Star Schema

Shows the relationships between the sales fact table and the Date, Product, and Shift dimension tables.

"Star Schema Data Model" (star_schema_model.png)

8. How to Run or Open

1. Download or clone this GitHub repository.
2. Open "Balaji_Fast_Food_Sales_Dashboard.pbix" using Microsoft Power BI Desktop.
3. If Power BI requests the source dataset, select the included "Balaji Fast Food Sales.csv" file and update the data source path.
4. Refresh the data if required.
5. Navigate between the two report pages and interact with the filters and visuals.

9. Project Files

- "Balaji Fast Food Sales.csv" – Original dataset.
- "Balaji_Fast_Food_Sales_Dashboard.pbix" – Power BI project file.
- "Balaji_Fast_Food_Sales_Dashboard.pdf" – Exported dashboard report.
- "page1_sales_overview.png" – Page 1 screenshot.
- "page2_product_analysis.png" – Page 2 screenshot.
- "star_schema_model.png" – Data model screenshot.

10. Author

Name: Vibin R
Project: Balaji Fast Food Sales – Power BI Dashboard
Field: Data Analytics
