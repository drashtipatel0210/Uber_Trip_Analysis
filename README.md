# Ube Trip Analysis

## Objective
To leverage historical Uber trip data to answer critical business questions:
What are the booking and revenue trends over time?
How efficient are the trips in terms of time and distance?
Which payment types, trip types, vehicle types, and locations drive the most business?
How does ride demand vary by time of day and day of week?

## Dashboard Breakdown
Dashboard 1 : Overview Analysis

Key KPIs:
Total Bookings
Total Booking Value
Average Booking Value
Total Trip Distance
Average Trip Distance
Average Trip Time

Features:
Dynamic Measure Selector (Total Bookings, Revenue, Distance)
Breakdowns by Payment Type & Trip Type (Day/Night)
Vehicle Type Analysis with conditional formatting
Daily Booking Trends

Location-Based Insights:
Top Pickup & Drop-off Points
Farthest Trip
Top 5 Locations by Booking
Preferred Vehicle Type by Location

Interactive Elements:
Dynamic chart titles based on selected metric
Slicers for Date, City, Trip Type, etc.
Tooltips for deeper context (Avg Booking Value, etc.)
Export Button (CSV/Excel)
Clear Filter Button
Bookmarks for data detail views

Dashboard 2: Time Analysis

Focuses on ride demand across time intervals to assist with operational optimization.
Visuals:

Area Chart: Bookings by Pickup Time (10-minute intervals)

Line Chart: Bookings by Day of the Week

Heatmap: Hour vs Day of Week with dynamic measure (Total Bookings/Revenue/Distance)

Dashboard 3: Details Tab

Offers a drill-through experience for granular trip-level data.
Features:
Grid Table displaying trip-level details (Trip ID, Locations, Time, Fare, Distance)
Drill-through from other dashboards
Bookmark to toggle between filtered and full data view

## Data & Tools
Tools Used: Power BI, DAX, Power Query
Data Source: Synthetic Uber Trip Dataset
Data Model: Multiple related tables with active and inactive relationships used for deep insights


