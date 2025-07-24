# 🚖 Driving-Data-Uber-Analysis
## 📌 Project Description / Purpose

The **Uber Trip Insights Dashboard** is a visually rich and interactive Power BI solution designed to analyze Uber trip data across multiple dimensions—time, location, vehicle type, and revenue. It provides actionable insights to support decision-making for operational teams, business analysts, and strategic planners in the ride-hailing industry.

This dashboard addresses key business questions such as:

- **When are Uber rides most frequently booked?**  
  By analyzing pickup timestamps, the dashboard reveals hourly and daily ride patterns using 10-minute intervals and weekday segmentation. This enables identification of peak and off-peak periods for better resource planning, driver allocation, and dynamic pricing.

- **What are the most in-demand days and hours?**  
  Visuals like line charts and heatmaps show booking behavior across hours of the day and days of the week. These patterns help forecast demand and support staffing and promotional strategies.

- **Which vehicle types generate the highest revenue?**  
  The dashboard compares performance across vehicle categories (e.g., Sedan, SUV, Mini) using KPIs like total bookings, total revenue, and average booking value. This helps identify the most profitable vehicle types and supports fleet optimization.

- **How efficient are Uber trips?**  
  It measures average trip distance and duration to evaluate operational efficiency and customer behavior, helping identify potential inefficiencies or long-distance ride trends.

- **Where is ride demand concentrated?**  
  Location analysis highlights the most common pickup and drop-off points, the farthest trips, and preferred vehicles by location. This insight is crucial for optimizing driver placement and improving service availability.

In summary, this Power BI dashboard enables Uber teams to uncover deep insights from trip data and make informed decisions regarding pricing, fleet management, marketing, and customer experience.


---

## 🛠 Tech Stack

The dashboard was developed using the following technologies:

- **Power BI Desktop** – Main platform for building data models and reports.
- **Power Query** – For data cleaning, shaping, and transformation.
- **DAX (Data Analysis Expressions)** – Used for calculated measures, conditional logic, and dynamic KPIs.
- **Data Modeling** – Established relationships across dimensions like trip details, location, and time for cross-filtering and aggregation.
- **File Formats** – `.pbit` for the dashboard file and `.csv` for data source files.

---

## 📊 Data Source

**Source**: Uber trip data (public/simulated).

The dataset includes:

- Pickup and drop-off timestamps
- Booking value and payment types
- Trip distance and duration
- Vehicle types and trip categories
- Pickup and drop-off locations

---

## 🔍 Features and Highlights

### ✅ Business Problem

Ride-hailing platforms generate vast amounts of trip-level data, which can be difficult to interpret without structured dashboards. This project addresses key business questions, including:

- When and where does ride demand peak?
- Which vehicle types are preferred in specific areas?
- What are the trends in trip distances and revenue over time?

### 🎯 Goal of the Dashboard

To provide an interactive and comprehensive dashboard that:

- Identifies patterns in bookings, revenue, and trip performance
- Offers visual analysis by location, time, and vehicle category
- Supports decision-making for pricing, driver allocation, and marketing

---

## 📈 Dashboard Overview

### 🧩 Dashboard 1: Overview Analysis

- **KPIs**:
  - Total Bookings
  - Total Booking Value
  - Average Booking Value
  - Total Trip Distance
  - Average Trip Distance
  - Average Trip Time

- **Visualizations**:
  - Dynamic measure selector and title
  - Segment analysis by payment type and trip type (Day/Night)
  - Vehicle performance grid (table or matrix view)
  - Total bookings by day
  - Top 5 pickup and drop-off locations
  - Farthest trip identification
  - Most preferred vehicle by pickup location

### 🕒 Dashboard 2: Time Analysis

- **Visualizations**:
  - Pickup Time (10-minute intervals): Area Chart
  - Day Name Trends: Line Chart (Monday to Sunday)
  - Hour vs. Day Heatmap: Matrix with dynamic KPI selection

### 📋 Dashboard 3: Details Tab

- Show Detail Analysis

---

## 📌 Key Outcomes

- Identify temporal and geographic ride demand patterns
- Detect high-revenue locations and vehicle types
- Optimize operational strategies and customer experience
- Enable data-informed pricing and driver dispatch policies

---

## 🔧 Additional Enhancements

- Disconnected table for global dynamic measure selection
- Dynamic chart titles linked to selected KPI
- Bookmark for metric definitions and metadata
- "Clear Filters" button for resetting slicers
- "Download Raw Data" button using Power BI or Power Automate
- Conditional formatting for high/low performance indicators

---

## 📂 Files Included

- `Uber Analysis.pbit` – Power BI dashboard file
- `uber_trip_details.xls` – Data source file
- `README.md` – Project documentation
- `Overview-Uber-Analysis.png` – Screenshot of the dashboard
- `TimeAnalysis-Uber.png` – Screenshot of the dashboard

---

