🛒 Blinkit Sales Analytics Dashboard using Power BI

📌 Project Overview
This project analyzes Blinkit grocery sales data to understand how sales vary across item types, fat content, outlet sizes, location tiers and outlet types. Using Power BI, the interactive dashboard helps businesses see which products, outlets and locations drive the most revenue.

🎯 Objectives
Track key KPIs: Total Sales, Average Sales, Average Rating and number of items
Compare sales across outlet size, location tier and outlet type
Identify top-selling item categories and the effect of fat content
Let users filter the whole dashboard with slicers
Provide actionable insights for business decision-making

🛠️ Technologies Used
Power BI Desktop – data modeling, DAX measures and visuals
DAX – KPI measures
Python (Pandas) – data cleaning
Excel – source and cleaned datasets

🗂️ Dataset
8,523 records and 12 columns
8,523 records after cleaning (no duplicates found)
Columns: Item Fat Content, Item Identifier, Item Type, Outlet Establishment Year, Outlet Identifier, Outlet Location Type, Outlet Size, Outlet Type, Item 
Visibility, Item Weight, Sales, Rating

📊 Key Analysis Performed
Data cleaning and preprocessing:
  - Standardized Item Fat Content labels (`LF`, `low fat` → Low Fat; `reg` → Regular)
  - Filled 1,463 missing Item Weight values using the same Item Identifier from other rows (4 items had no recorded weight and were left empty)
  - Added an Outlet Age column
DAX measures for Total Sales, Avg Sales, Avg Rating and No. of Items
Sales by item fat content, outlet size, location tier and outlet type
Item type ranking and sales by outlet establishment year
Interactive slicers for Outlet Size, Outlet Location Type and Item Type

📌 Key Metrics
Metric - Value 
Total Sales - $1.20M 
Average Sales - $141 
Average Rating - 3.97 
No. of Items - 8,523

📈 Sample Insights
Low Fat items bring about 65% of sales ($776K vs $425K for Regular)
Medium outlets lead by size ($508K), followed by Small ($445K) and High ($249K)
Tier 3 locations lead ($472K), followed by Tier 2 ($393K) and Tier 1 ($336K)
Supermarket Type 1 brings the most sales ($788K); Grocery Stores bring $152K
Fruits and Vegetables ($178K), Snack Foods ($175K) and Household ($136K) are the top item types
Sales by establishment year are about $130K each, except 2018 ($205K), because two of the 10 outlets opened that year

✅ Recommendations
Focus promotions and stock on Tier 3 locations and Supermarket Type 1 outlets
Give Fruits and Vegetables and Snack Foods priority shelf space and early stocking
Review why Grocery Stores sell much less than supermarkets before expanding them

⚠️ Limitations
The dataset has only 10 outlets, so each group is small
Three outlets appear under more than one Outlet Size, so size comparisons should be read with care

## ▶️ How to Open
Install Power BI Desktop (Windows), download `Blinkit_Dashboard.pbix` and open it. If asked, point the data source to `BlinkIT_Grocery_Data_Cleaned.xlsx`.
