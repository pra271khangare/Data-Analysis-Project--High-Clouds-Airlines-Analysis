✈️ High Clouds Airlines – Business Intelligence Dashboards
This repository contains interactive dashboards built using Tableau, Power BI, and Excel for analyzing airline performance data as part of the High Clouds Airlines case study. Also MySQL was used to do all the KPI's and verify the data

📊 Objective
To evaluate and visualize key performance metrics for High Clouds Airlines, aiding stakeholders in identifying areas of improvement and making data-driven strategic decisions.

🛠️ Tools Used
Tableau
Power BI
Excel
SQL (for query-based data verification)

📁 KPIs Required
Calcuate the following fields from the Year Month (#) Day fields ( First Create a Date Field from Year , Month , Day fields)"
A.Year
B.Month no
C.Month full name
D.Quarter(Q1,Q2,Q3,Q4)
E.Year-Month (YYYY-MMM)
F.Weekday No
G.Weekday Name
H.Financial Month
I.Financial Quarter
Find the load Factor percentage on a yearly , Quarterly , Monthly basis (Transported passengers / Available seats)
Find the load Factor percentage on a Carrier Name basis (Transported passengers / Available seats)
Identify Top 10 Carrier Names based passengers preference
Display top Routes (From-to City) based on Number of Flights
Identify the how much load factor is occupied on Weekend vs Weekdays.
Identify number of flights based on Distance group
Build a Dashboard to support your Analysis

📊 Dashboards Overview
1. Tableau Dashboard
Features:

Yearly, Monthly and Quarterly-wise Load-Factor % created by using (Pie Chart , Bar Chart , Line Chart)
Load Factor % based on Carrier Name ( Bar Chart) and Weekend/Weekday (Donut Chart).
Top 10 routes (From-to-City) and Carriers based on passenger preference (Bar Chart)
Total flights based on distance group with the help of joins (TreeMap)
Interactive filters for selecting Carrier name,Month name,Year of date
Added Dashboard actions that make the dashboard more interactive where clicking on any graph applies filters

2. Power BI Dashboard
Features:

KPI visuals for passenger count, total countries, total no of flights and Load factor .
Yearly, Monthly and Quarterly-wise Load-Factor % Line chart which can be changed with the use of bookmark.
Top 10 routes (From-to-City) and Carriers based on passenger preference (Bar and Area-Line Chart)
Load Factor % based on Weekend/Weekday (Donut Chart).
Total flights based on distance group with the help of Merging in Power Query editor (Clustered Bar Chart)
Slicers for dynamic filtering by Month,Year,Career name and Origin (State,City),Destination (State,City).
Added a Clear all slicers button for easy usage
Added a link for Booking tickets

3. Excel Dashboard
Features:

KPI visuals for Total country, total no of flights and 
Top 10 routes (From-to-City) and Carriers based on passenger preference (Bar Chart)
Load Factor % based on Weekend/Weekday (Pie Chart),carrier name(Bar Chart) and also Year-Wise Load Factor % (Bar chart).
Total flights based on distance group with the help of Power Query editor (Line Chart)
Slicers for dynamic filtering by Year,Quarter and Weekend/Weekday.

💻 MySQL Usage
All KPIs and calculated columns used in this project were derived, verified, and tested using MySQL prior to visualizing the data in Tableau, Power BI, and Excel. SQL was used to:

Generate custom date fields (date, month_name, quarter, etc.)
Compute Load Factor % across time and dimensions
Extract top 10 carriers and routes
Segment data by distance group
Compare weekday vs weekend trends

