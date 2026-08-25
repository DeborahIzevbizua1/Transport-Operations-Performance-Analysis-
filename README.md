# Transport Operations Performance Analysis

##  Overview
This project analyzes transport operations data from a Lagos based fleet covering Bikes, Buses, Taxis, and Trucks across seven routes. Using Microsoft Excel, raw operational data was cleaned, structured, and transformed into an interactive report to support fleet allocation, safety review, and maintenance planning decisions. Data covers February 2026 in full and the first three days of March 2026.

## Tools Used
- Microsoft Excel
- Pivot Tables
- Charts (Line, Bar, Column)

## Data Cleaning and Standardization
Data Source: Shared operational dataset, raw transport operations data provided by a stakeholder.

## Process
#### Data Cleaning
Removed duplicate records. Fixed inconsistent date formats. Standardized Vehicle Type and Route naming. Created calculated fields for Mechanical Fault Rate, Accident Rate, and Net Revenue.
#### Report Building
Built a dynamic Excel report tracking key KPIs. Added filters and slicers by Vehicle Type and Route for self serve analysis.
#### Analysis and Visualization
Cross analyzed accidents, faults, trips, and revenue by Vehicle Type and Route. Designed pivot tables and charts for an executive friendly presentation.

## Key Insights
#### Overall Performance
- Total trips: 5,426
- Total revenue: 31,917,663 Naira
- Total tax: 1,595,414 Naira
- Net revenue: 30,322,249 Naira
- Total accidents: 1,034
- Total mechanical faults: 1,479
- Mechanical fault rate: 27.3 percent
- Accident rate: 19.1 percent
#### Vehicle Type Breakdown
Buses recorded the highest trip volume at 1,410, ahead of Taxis at 1,396, Bikes at 1,387, and Trucks at 1,233. Buses also had the highest mechanical faults at 377 and the highest accidents at 295, meaning Buses are both the busiest and the riskiest vehicle type in the fleet.
#### Route Breakdown
Ikeja VI recorded the highest raw accident count of any single route at 186, and also generated the most revenue at 5,243,178 Naira. Yaba Ikeja, CMS Ikoyi, and Ikeja VI were flagged as high risk routes with a 21 percent accident rate, recommended for safety review and maintenance planning. Yaba Ikeja generated the least revenue of any route at 3,964,276 Naira, despite being one of the flagged high risk routes.
#### Trip Volume Note
Trip activity is tracked through the first three days of March. The lower trip count in early March reflects data coverage rather than an operational decline.
#### Business Impact
These insights support data driven decisions across three areas. Safety, by identifying high risk routes and vehicle types for prioritized review. Maintenance, by flagging vehicle types with elevated fault rates for proactive servicing. Fleet Planning, by allocating vehicles by route based on trip demand and revenue patterns.

## Files
transport operations dashboard.xlsx, full Excel report with PivotTables and charts

### Author
Deborah Etinosa Izevbizua
