📊 Global Electronics Retailer: Executive Performance Dashboard

🎯 Business Overview
This project involves a comprehensive analysis of over $55M in sales data for a global electronics retailer. The goal was to transform raw, fragmented data across multiple regions , interactive decision-making tool. This dashboard allows stakeholders to monitor real-time performance, track growth trends, and identify high-value product segments.

🛠️ Tech Stack & Skills
Power BI Desktop: End-to-end report development and visualization.
Power Query (M): Advanced data cleaning, handling null values, and merging disparate datasets (Sales, Exchange Rates, and Products).
Data Modeling: Implementation of a Star Schema to optimize query performance and filter context.
DAX: Developed complex measures for Time Intelligence and dynamic currency conversions.

🏗️ Data Architecture
The model follows a Star Schema approach to ensure scalability and accuracy.
Fact Table: Sales (Transactional data)
Dimension Tables: Products, Stores, Customers, Calendar, and Exchange_Rates.
Relationship: One-to-many (1:*) relationships with single-direction filtering to maintain data integrity.

📈 Key DAX Measures
Here are some of the core calculations used to drive the dashboard's insights:

1. Year-Over-Year (YoY) Growth %
Calculates the performance compared to the same period in the previous year.

2. Total Profitability
💡 Business Insights
Market Leadership: The United States accounts for over 53% of total global revenue, followed by the UK and Germany.
Product Performance: Computers is the dominant category, generating $19.3M, with Desktops being the highest-selling sub-category.
Growth Trends: Despite high volume, the current YoY Growth is at 1.90%, suggesting a need for targeted marketing in underperforming categories like "Audio" or "TV and Video."

📁 Repository Structure
Global_Electronics_Retailer.pbix: The primary Power BI report file.

/files_global_electromics: Contains the raw CSV files used for the analysis (Sales, Products, Stores, etc.).

global_elect_sales.png: High-resolution screenshot of the final dashboard.

LICENSE: MIT License.

🚀 How to View
Download the .pbix file from this repository.

Open it using Power BI Desktop.

If data links are broken, redirect the Source step in Power Query to the local files in the /Data folder.
