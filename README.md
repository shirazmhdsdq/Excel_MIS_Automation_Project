📌 Project Overview

This project demonstrates an automated Management Information System (MIS) reporting pipeline built entirely within Microsoft Excel. The goal was to eliminate manual data entry by engineering a one-click refresh system that ingests monthly raw sales data and updates a dynamic performance dashboard.

🛠️ Tech Stack & Tools

Microsoft Excel: Dashboard design and KPI visualization.

Power Query: Automated ETL (Extract, Transform, Load) pipeline connecting directly to a local folder directory to append new monthly CSV files.

Advanced Formulas: Utilized INDEX-MATCH for robust data mapping and relational lookups against a static dimension table.

Pivot Tables: Aggregated ~10,000 rows of transactional data to calculate dynamic Month-over-Month (MoM) revenue variance.

📂 Project Structure

Automated_MIS_Report.xlsx: The master dashboard and reporting file containing the Power Query connections and Pivot Tables.

Raw_Data/: The target folder where new monthly CSV datasets are dropped for automatic ingestion.

MIS_Dashboard_Screenshot.png: A static preview of the final KPI dashboard and slicers.

📈 Key Features

Zero-Touch Updates: By pointing Power Query to a master folder, new monthly sales data is instantly appended to the data model simply by clicking "Refresh All."

Variance Analysis: Programmed Pivot Table calculations to automatically evaluate and display Month-over-Month percentage growth across regions.

Interactive Filtering: Implemented interconnected slicers allowing management to drill down into specific product categories and regional manager performance instantly.
