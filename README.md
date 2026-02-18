# BMW-Sales-Data-2010-to-2014
BMW Global Sales & EV Transition Analysis (2010 - 2024)
📌 Project Overview
This project provides a comprehensive analysis of BMW's global sales performance over a 14-year period. The primary objective was to visualize the brand's shift from traditional internal combustion engines (ICE) to Electric (EV) and Hybrid powertrains, while identifying high-value regional markets and model performance.

<img width="1323" height="743" alt="Screenshot 2026-02-18 190159" src="https://github.com/user-attachments/assets/9bec7ea0-b510-4b7d-a2e5-32bf598378ca" />


🛠️ Tech Stack & Skills
Tool: Power BI Desktop

Data Modeling: Star Schema (Fact and Dimension tables)

ETL: Power Query (Data cleaning, type conversion, and custom columns)

DAX: Advanced measures for Time Intelligence (YoY Growth), Dynamic Ranking, and Aggregations.

Data Visualization: Custom Stream Graphs, Decomposition Trees, and branded UI/UX design.

📂 Data Architecture
The project utilizes a Star Schema to ensure optimal performance and scalability:

Fact_Sales: Contains core transactional data (Sales Volume, Price, Mileage).

Dim_Model: Unique list of BMW models.

Dim_Region: Geographic categories (Asia, Europe, North America, etc.).

Dim_Date: A dedicated DAX-generated calendar table for time-series analysis.

📊 Key Insights & Features
1. The EV Transition (Stream Graph)
Identified the specific "inflection point" where Electric and Hybrid sales volumes began to outpace Diesel models in the European and North American markets.

2. Revenue Drivers (Decomposition Tree)
Using AI-driven root-cause analysis, I identified that the 7 Series remains the primary revenue driver globally, despite higher unit volumes in the 3 Series and i3 segments.


3. Executive KPIs
Total Revenue: Tracked across 14 years.

YoY Growth %: Interactive cards that highlight performance swings using conditional formatting.


📖 How to Use
Filters: Use the slicers on the left to filter by Region, Fuel Type, or Year.

Drill-Down: Right-click on the "Model" bar charts to drill through into specific regional performance.

Interact: Hover over any data point in the Stream Graph to see detailed monthly performance tooltips.
