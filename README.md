# Airline Sales Dashboard — Power BI Candidate Task

Power BI dashboard built as part of a candidate assessment task, analyzing airline ticket sales data across two periods (H1 2024 vs H1 2025) by country, revenue, and booking behavior.

## Task
Given raw airline sales data (two half-year sales sheets + a POS–Country mapping sheet), the goal was to:
- Model and combine the data in Power BI
- Build DAX measures for revenue, ticket volume, and booking lead time
- Design a dashboard with country/year/class-level breakdowns
- Summarize key insights from the data

## Data
- **Sales data**: Sales Date, Scheduled Flight Date, Departure, Arrival, Ticket Class, Ticket Quantity, Revenue (AZN), Point of Sale — covering 01.01.2024–30.06.2024 and 01.01.2025–30.06.2025
- **POS–Country mapping**: maps each Point of Sale code (e.g. BSP_SA, BSP_FR, BSP_AE) to its country

## Data Modeling
- Combined the 2024 and 2025 sales tables into a single fact table
- Joined the POS–Country mapping to resolve country from Point of Sale
- Built a proper Date table linked to both Sales Date and Scheduled Flight Date
- Converted date columns to proper date types

## DAX Measures
- Total Revenue (AZN) by Country
- Total Ticket Quantity by Country
- Average Advance Purchase Days (Scheduled Flight Date − Sales Date)
- Year-over-Year Revenue and Ticket Quantity growth (%) by Country

## Dashboard
- **Revenue by Country** — by Sales Date (2024 vs 2025)
- **Revenue by Country** — by Scheduled Flight Date (2024 vs 2025)
- **Average Advance Purchase Days** by Country
- **Ticket Quantity** comparison by Country and Year
- Slicers: Year, Country, Ticket Class
- Card visual: Total Revenue across all countries

## Key Insights
*(2–3 sentences to add — e.g. which country grew fastest, how Sales Date vs Flight Date views differ, notable booking lead-time patterns)*


