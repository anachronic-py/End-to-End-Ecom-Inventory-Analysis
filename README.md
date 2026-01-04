# End-to-End-Ecom-Inventory-Analysis
This project demonstrates a full-cycle data analysis workflow, from sourcing raw data on Kaggle to delivering a high-clarity operational dashboard. The analysis focuses on inventory valuation, delivery efficiency, and pricing strategy for an Indian e-commerce dataset.

📝 The "Steps I Took" Section
The Data Workflow
Step 1: Raw Data Sourcing & Inspection
Sourced the Meesho Product Dataset from Kaggle to work with real-world Indian e-commerce data.

Identified critical data quality issues during the initial inspection, including null values (13%) and inconsistent naming conventions.

Step 2: Data Auditing (Excel)
Performed a manual audit in Excel to verify the relationships between Price, Discount Price, and Ratings.

Validated that the "Availability" column contained consistent "In-Stock" labels before importing to Power BI.

Step 3: Advanced Cleaning (Power Query)
Used Power Query Editor to standardize data types (Decimals for Price, Integers for Reviews).

Applied "Transformation Steps" to ensure the data was clean and refreshed-ready for the visualization layer.

Step 4: Feature Engineering
Realized the raw dataset lacked insight into promotional depth, so I created two custom columns:

Total Discount Given: To track the total loss in value from MRP.

Discount-to-Price Ratio: To analyze which categories were being most aggressively discounted.

Step 5: Interactive Dashboard Development
Designed a modern UI with high-contrast KPI cards for Inventory Value, Delivery Time, and Review Averages.

Implemented dynamic cross-filtering, allowing users to drill down from high-level "Categories" (like Men-Fashion) into specific "Sub-Categories" (like Jeans or Shirts).
