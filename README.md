# Uber Ride Analysis Dashboard using Power BI

## Project Overview
This project provides a comprehensive analysis of Uber ride data for the NCR region using **Power BI**. The analysis covers key business metrics, trends, and insights including bookings, cancellations, performance, revenue, and customer/driver ratings. The goal is to help Uber or ride-hailing stakeholders make **data-driven decisions** by identifying trends, peak times, common cancellation reasons, revenue patterns, and service performance.

**Dataset:**  
- Source: [Kaggle – Uber Ride Analytics Dashboard](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard?select=ncr_ride_bookings.csv)  
- Size: ~1.5 lakh rows  
- Key Columns: Date, Time, Booking ID, Booking Status, Customer ID, Vehicle Type, Pickup & Drop Location, Avg VTAT, Avg CTAT, Cancelled Rides, Booking Value, Ride Distance, Driver/Customer Ratings, Payment Method, etc.

---

## Pages & Features

### 1. Overview Page  
**Link:** [Overview Screenshot](https://github.com/divyamehulmakwana-bit/Uber-Analysis-using-PowerBi/blob/main/Screenshots/Overview%20Page.png)  
**Key Features:**  
- **KPIs:**  
  - Total Sales: 51.85M  
  - Total Rides: 93k  
  - Avg Ride Distance: 24.64 km  
  - Total Customers: 149k  
  - Avg Trip Duration: 29.15 mins  
- **Visualizations:**  
  - Line chart: Rides over months (peak in May, July, Oct ~8k rides)  
  - Map: Most common pickup locations  
  - Donut chart: Rides by vehicle type (Auto: 23k, Go Mini: 19k)  
  - Bar chart: Most commonly used payment method (UPI: 42k, Cash: 23k)

---

### 2. Bookings & Trends Page  
**Link:** [Bookings & Trends Screenshot](https://github.com/divyamehulmakwana-bit/Uber-Analysis-using-PowerBi/blob/main/Screenshots/Bookings%20%26%20Trends%20Page.png)  
**Key Features:**  
- **KPIs:** Completed Rides: 93k, Pending Rides: ~9k  
- **Visualizations:**  
  - Column chart: Bookings by month, weekdays vs weekends (avg 9k weekday rides, 3.5k weekend)  
  - Bar chart: Booking status (Completed: 93k, Cancelled by Driver: 27k, Cancelled by Customer: 11k)  
  - Histogram: Bookings by ride distance (highest between 10-20 km)  
  - Donut chart: Booking by vehicle type

---

### 3. Cancellations Page  
**Link:** [Cancellations Screenshot](https://github.com/divyamehulmakwana-bit/Uber-Analysis-using-PowerBi/blob/main/Screenshots/Cancellations%20Page.png)  
**Key Features:**  
- **KPIs:**  
  - Total Cancelled Rides: 37.5k  
  - Cancelled by Customers: 10k  
  - Cancelled by Drivers: 27k  
  - Total Incomplete Rides: ~9k  
- **Visualizations:**  
  - Table: Booking status, cancellation reasons, and count  
  - Column chart: Rides cancelled by day (avg 3.8k driver cancellations, 1.5k customer cancellations)  
  - Line chart: Cancellations over months by driver and customer  
  - Donut chart: Cancellations by vehicle type (Auto & Mini dominate)

---

### 4. Performance Page  
**Link:** [Performance Screenshot](https://github.com/divyamehulmakwana-bit/Uber-Analysis-using-PowerBi/blob/main/Screenshots/Performance%20Page.png)  
**Key Features:**  
- **KPIs:**  
  - Avg Driver Arrival Time: 8.4 mins  
  - Avg Trip Duration: 29 mins  
  - Avg Ride Distance: 24 km  
  - On-time Pickups: 41k  
- **Visualizations:**  
  - Line chart: Avg arrival time by month (Oct & Dec highest)  
  - Donut chart: Rides cancelled by vehicle type  
  - Map: Locations with high arrival times  
  - Column chart: Avg trip duration by vehicle type

---

### 5. Revenue & Payment Page  
**Link:** [Revenue & Payment Screenshot](https://github.com/divyamehulmakwana-bit/Uber-Analysis-using-PowerBi/blob/main/Screenshots/Revenue%20%26%20Payment%20Page.png)  
**Key Features:**  
- **KPIs:**  
  - Total Revenue: 51M  
  - Most used Payment Method: UPI  
  - Day generating most revenue: Sunday  
- **Visualizations:**  
  - Line chart: Revenue over months (March: 4.5M, October: 4.4M)  
  - Donut chart: Revenue by payment method  
  - Funnel chart: Revenue by hour (6 PM highest)  
  - Bar chart: Revenue by vehicle type

---

### 6. Customer & Driver Ratings Page  
**Link:** [Customer & Driver Ratings Screenshot](https://github.com/divyamehulmakwana-bit/Uber-Analysis-using-PowerBi/blob/main/Screenshots/Customer%20%26%20Driver%20Ratings%20Page.png)  
**Key Features:**  
- **KPIs:**  
  - Total Customers: 149k  
  - Avg Customer Rating: 4.4  
  - Avg Driver Rating: 4.2  
  - Total Rides with 5-star: ~6k (~27%)  
- **Visualizations:**  
  - Histogram: Customer ratings distribution (majority 4-5)  
  - Line chart: Ratings over months  
  - Tree map: Ratings by vehicle type

---

## Insights & Observations
- **Bookings:** May, July, and October see peak ride volumes. Weekdays dominate over weekends.  
- **Cancellations:** Majority of cancellations are driver-based, often auto & mini rides.  
- **Performance:** October and December had longer driver arrival times, indicating potential operational bottlenecks.  
- **Revenue:** March and October generate highest revenue; evening hours (5-6 PM) are peak.  
- **Ratings:** Most customers give 4-5 ratings; 5-star ratings are concentrated in certain vehicle types.  

---

## Tools & Technologies
- **Power BI Desktop:** For data modeling, transformations, and visualization.  
- **DAX (Data Analysis Expressions):** For calculated columns, measures, and KPIs.  
- **Kaggle Dataset:** Raw Uber ride data (~1.5 lakh rows).  
- **GitHub:** Hosting screenshots and project documentation.

---

## Conclusion
This dashboard provides actionable insights for Uber operations, helping identify **peak hours, most profitable days, common cancellation reasons, customer/driver satisfaction trends**, and areas for operational improvement. It serves as a **decision-support tool** for ride-hailing business analytics.

