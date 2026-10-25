# Uber-Trip-Analysis

# 🚖 Uber Trip Analysis Dashboard | Power BI

## 📌 Project Overview

The **Uber Trip Analysis Dashboard** is an interactive data analytics project developed using Microsoft Power BI to analyze ride-booking trends, revenue, trip distances, travel time, vehicle performance, and pickup/drop-off locations.

The dashboard transforms trip data into meaningful business insights through interactive visualizations, KPI cards, time-based analysis, and location-based performance metrics.

## 🎯 Project Objectives

- Analyze total bookings and booking value.
- Understand daily and hourly ride-booking patterns.
- Evaluate trip distance and average trip duration.
- Compare booking performance across vehicle types.
- Identify popular pickup and drop-off locations.
- Analyze payment methods and day-trip versus night-trip bookings.
- Support data-driven operational and business decisions.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Dashboard development and visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Measures and KPI calculations
- **Data Modeling** – Relationships between trip, calendar, and location tables
- **Data Visualization** – KPI cards, donut charts, area charts, bar charts, and heatmaps

## 📊 Dashboard Pages

### 1. Overview Analysis

Provides a summary of ride-booking performance, including:

- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Distance
- Average Trip Time
- Payment Type Analysis
- Day Trip vs. Night Trip Analysis
- Vehicle Type Analysis
- Most Frequent Pickup and Drop-off Locations

### 2. Time Analysis

Explores how booking activity changes over time through:

- Hourly booking trends
- Daily booking trends
- Day-of-week comparisons
- Hour-by-day booking heatmap
- Peak and low-demand periods

### 3. Details

A dedicated page for exploring detailed trip records and supporting deeper analysis.

## 📈 Key Insights from the Dashboard

Based on the displayed dashboard:

- **103.7K total bookings** were recorded.
- **$1.6M total booking value** was generated.
- **$15.0 average booking value** was reported.
- **349K miles** were covered across trips.
- **3 miles average trip distance** was reported.
- **16 minutes average trip time** was recorded.
- UberX accounted for approximately **38.7K bookings**, making it the leading vehicle category by booking count.
- Saturday and Sunday showed the highest booking totals among the displayed weekdays, at approximately **18.7K and 19.2K bookings**, respectively.
- The hourly analysis indicates higher demand during the daytime and afternoon, with lower activity during early morning hours.

*Note: These figures reflect the values visible in the screenshots and may be rounded.*

## 📐 Key Performance Indicators (KPIs)

| KPI | Purpose |
|---|---|
| Total Bookings | Measures overall booking volume |
| Total Booking Value | Tracks total booking revenue/value |
| Average Booking Value | Measures average value per booking |
| Total Trip Distance | Measures total distance traveled |
| Average Trip Distance | Measures average distance per trip |
| Average Trip Time | Measures average trip duration |

## 🧮 Example DAX Measures

```dax
Total Bookings =
COUNTROWS('Trip Details')
```

```dax
Total Booking Value =
SUM('Trip Details'[Booking Value])
```

```dax
Average Booking Value =
DIVIDE(
    [Total Booking Value],
    [Total Bookings],
    0
)
```

```dax
Total Trip Distance =
SUM('Trip Details'[Trip Distance])
```

```dax
Average Trip Distance =
DIVIDE(
    [Total Trip Distance],
    [Total Bookings],
    0
)
```

*Update the table and column names to match your actual Power BI data model.*

## 📂 Project Structure

```text
Uber-Trip-Analysis/
│
├── README.md
├── Dashboard/
│   └── Uber_Trip_Analysis.pbix
├── Screenshots/
│   ├── Overview_Analysis.png
│   └── Time_Analysis.png
└── Dataset/
    └── trip_data.csv
```

*Replace the example filenames with your actual project files.*

## 🚀 How to Use This Project

1. Clone or download this repository.
2. Open `Uber_Trip_Analysis.pbix` using Power BI Desktop.
3. If required, update the dataset source path.
4. Refresh the data.
5. Explore the dashboard using the date and city filters.
6. Interact with the charts to investigate booking trends and trip performance.

## 💼 Skills Demonstrated

- Data cleaning and transformation
- Data modeling
- DAX calculations
- KPI development
- Time-series analysis
- Business intelligence reporting
- Interactive dashboard design
- Analytical thinking and insight generation

## 👨‍💻 Author

**Kishore Kumar**

Aspiring Data Analyst | Power BI | SQL | Python | Excel


<img width="1913" height="1093" alt="Screenshot 2026-10-25 140147" src="https://github.com/user-attachments/assets/1bc3e95a-c0ef-4cc0-a2e4-61479eec72c3" />

<img width="1918" height="1092" alt="Screenshot 2026-10-25 140213" src="https://github.com/user-attachments/assets/57651d59-dd01-466e-9c6c-2a44dbefa02a" />

<img width="1917" height="1097" alt="Screenshot 2026-10-25 140716" src="https://github.com/user-attachments/assets/bc3195a5-f5d6-4b7a-b75a-e0809383acce" />

This project demonstrates my ability to transform trip-level data into interactive dashboards and actionable business insights.

