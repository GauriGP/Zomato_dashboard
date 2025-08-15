Restaurant Orders Dashboard – Power BI Project

Overview: 
Designed and developed an interactive Power BI dashboard to analyze restaurant sales, 
customer demographics, and ordering patterns, enabling data-driven decision-making for 
business growth.  

1. Data Collection & Import 
 Gathered multiple datasets: restaurant details, menu items, orders, order types, and 
customer profiles. 
 Imported Excel datasets into Power BI.

2. Data Cleaning & Transformation (Power Query) 
 Removed duplicates, handled missing values, and standardized formats. 
 Split/merged columns (e.g., extracted date & time, standardized category names). 
 Created calculated columns such as Total = Quantity × Price. 
 Applied correct data types and prepared data for modeling.

3. Data Modeling 
 Built a star schema with fact tables (Orders) and dimension tables (Restaurants, Menu, 
Users, Order Types, Date). 
 Created and marked a Date Table for time-based analysis. 
 Applied one-to-many relationships, avoiding circular/many-to-many joins.
 
4. DAX Measures 
 Developed KPIs: 
o Total Sales 
o Order Count 
o Average Order Value 
o % Repeat Customers 
 Created demographic and cuisine segmentation measures.

5. Dashboard Design & Visualization 
 Designed an interactive layout with KPI cards, bar charts, treemaps, line charts, maps, 
and demographic visuals. 
 Key visuals: 
o Top 10 Restaurants by Revenue 
o Revenue by Month 
o Top 5 Cuisines by Revenue 
o Orders & Restaurants by City 
o Gender Split & Occupation-wise Revenue 
o Veg vs Non-Veg Sales Share 
 Added slicers for city, restaurant, cuisine, and order type.

6. Insights 
 Domino’s Pizza emerged as the top-performing brand. 
 Bikaner had the highest orders and number of restaurants. 
 Students were the largest revenue-generating group. 
 Veg and Non-Veg demand were nearly equal. 
 Identified seasonal trends and sales dips.

7. Final Output 
 Delivered a clean, interactive Power BI dashboard ready for stakeholder presentation. 
 Summarized insights into an actionable business narrative.
