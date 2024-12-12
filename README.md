# BikeStores-Dashboard

### Dashboard Link: https://public.tableau.com/app/profile/sanjana.parsa1878/viz/BikeStoresDashboard_17294358343070/Dashboard1

Data Analytics Project – BikeStores [SQL | Excel | Tableau]

## Project Overview

In this project, I walk you through the complete data analytics process using SQL, Excel, and Tableau, leveraging the BikeStores dataset. This involves generating a dataset using SQL, performing data analysis, and then visualizing insights with both an Excel dashboard and an interactive Tableau dashboard.

The BikeStores dataset is a simulated database used to represent a bike retail store with various tables containing information about customers, products, sales, staff, and more. The goal is to provide a comprehensive approach to data analysis by employing different tools for reporting, visualization, and decision-making support.

## Dataset & Tools

Dataset: The dataset used in this project is BikeStores, which consists of several interconnected tables including products, orders, customers, stores, staff, and more.
Tools Used:
- SQL: For data extraction, transformation, and querying.
- Excel: For creating pivot tables and charts, as well as an interactive dashboard.
Tableau: For building an executive-level interactive dashboard.

## Project Walkthrough

1. SQL  (Data Extraction & Transformation)
In this section, I performed the following tasks:

- Writing SQL Queries
Used SQL to extract relevant data, such as sales transactions, product details, and customer information.
- Querying the database to find sales performance by category, product, and region.
- SQL Query Results
The SQL queries yield results in the form of datasets that provide insights into sales, customer demographics, and stock availability.

2. Excel (Data Analysis & Visualization)
- After extracting the necessary data from SQL, I used Excel to create pivot tables and charts for initial data exploration and analysis.

- Connecting SQL Dataset to Excel Workbook 
Connected to the SQL database from Excel using the "Get & Transform Data" feature. This allowed to query the database directly and pull in live data for analysis.

- Creating Pivot Tables and Pivot Charts 
Pivot Table: Organized the data based on key metrics such as sales by product category, total revenue, or customer location.

Pivot Chart: Created visual charts such as bar graphs and line charts to depict the sales trends, revenue comparisons, etc.

Stopping PivotTable Grouping from affecting another PivotTable: A common Excel challenge is to ensure that grouping in one PivotTable doesn’t affect others. This is solved by ensuring each PivotTable is independent.

- Creating Map Charts 
Used Excel’s Map Chart feature to visualize sales by region, highlighting geographic trends in product sales.
- Setting Up Excel Dashboard
Combined all PivotTables and charts into a single Excel dashboard for a consolidated view of the business performance.
Added slicers to enable interactive filtering by time, product category, or region.

- Adding Slicers for Interactivity
Slicers are added to make the dashboard interactive, allowing users to filter data dynamically and drill down into specific details, such as sales per store or per product.


3. Tableau (Data Visualization)
- Tableau is used to build an interactive, visually appealing dashboard that provides deeper insights into sales performance.

- Connect Excel Dataset to Tableau Workbook 
Imported the Excel dataset into Tableau and prepare the data for visualization.

- Setting Default Properties
Set the default properties for fields, such as date formatting and numeric precision, to ensure accurate visualizations.

- Creating Visualizations
Charts: Build bar charts, line graphs, and pie charts to visualize key metrics like total sales by product, sales trends, and revenue by region.

Top N Chart: Used Tableau’s parameters and sets to create a Top N chart, displaying the best-performing products or regions.

- Adding Action Filters & Banner 

Action Filters: Created interactivity by setting up action filters that allow users to click on a region or product category to drill deeper into the data.

Banner: Added a banner to the dashboard to provide context or summarize key insights.

- Executive Dashboard 
Designed a comprehensive executive dashboard that summarizes all key metrics, enabling senior management to make data-driven decisions at a glance.


Interactivity: Allow users to interact with the dashboard, selecting different periods, products, and regions to explore performance.

- Contextual Calculated Field
Used a calculated field in Tableau to display dynamic text that changes based on user selection, providing a more contextual experience for users.
- Publishing to Tableau Public
Saved and published the Tableau dashboard to Tableau Public to share it with stakeholders and make it publicly accessible for viewing and interaction.


## Key Insights and Outcomes
- Sales Performance: The analysis shows that certain bike categories (e.g., Mountain Bikes) consistently outperform others, with sales peaking in the summer months.
- Customer Demographics: Insights into customer age groups and locations allow the company to tailor marketing efforts to specific audiences and regions.
- Inventory Management: By analyzing stock levels and product demand, businesses can optimize inventory and reduce stockouts.


## Conclusion
This project demonstrates the entire data analysis process, from SQL data extraction to the creation of detailed and interactive dashboards using both Excel and Tableau. The combination of these tools enables a robust data analysis approach, providing the business with valuable insights that can drive decision-making and improve overall performance.

## Tools and Technologies Used
SQL: For querying and transforming the dataset.
Excel: For creating pivot tables, pivot charts, and interactive dashboards.
Tableau: For designing an executive-level interactive dashboard and advanced visualizations.
