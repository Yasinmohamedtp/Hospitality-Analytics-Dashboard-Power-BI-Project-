# 🏨 Hospitality Analytics Dashboard (Power BI Project)

## 📌 Project Overview
This project focuses on building an **end-to-end Hospitality Analytics Dashboard** using **Power BI**. The dashboard provides a **comprehensive view of hotel performance metrics** such as Revenue, Occupancy, ADR, RevPAR, Cancellations, and Realisation %.  

The purpose of this project is to help stakeholders in the **hospitality domain** make data-driven decisions by analyzing booking patterns, revenue contributions, customer segments, and property-level performance.

---

## 🎯 Purpose
This project is designed as a **portfolio project for Data Analytics & Business Intelligence** showcasing:  
- Data modeling with fact & dimension tables  
- Advanced DAX calculations for KPIs  
- End-to-end BI dashboard design  
- Actionable insights for business users in the hospitality industry  

---

## 🚀 Tech Stack
- **Power BI** → Data visualization and dashboarding  
- **SQL / DAX** → Data modeling, calculated measures & KPIs  
- **Excel/CSV** → Raw dataset storage  
- **ETL in Power Query** → Data cleaning & transformation  

---

## 📂 Dataset
The project uses structured **fact & dimension tables**:  

- [dim_date.csv](./dim_date.csv) → Date dimension table  
- [dim_hotels.csv](./dim_hotels.csv) → Hotel metadata (city, property details)  
- [dim_rooms.csv](./dim_rooms.csv) → Room categories & attributes  
- [fact_aggregated_bookings.csv](./fact_aggregated_bookings.csv) → Aggregated booking metrics  
- [fact_bookings.csv](./fact_bookings.csv) → Transactional booking data  

---

## ✨ Features & Highlights
- ✅ **Interactive Filters**: by City, Room Type, Date, and Week  
- ✅ **Revenue Segmentation**: Luxury vs Business category share  
- ✅ **Performance Trends**: Week-over-week KPIs for RevPAR, ADR, and Occupancy %  
- ✅ **Property-Level Analysis**: Deep dive into each property’s performance (Revenue, Occupancy, ADR, Cancellations, Ratings)  
- ✅ **Booking Platform Insights**: Realisation % and ADR across platforms like TripXer, Direct Online, Logtrip etc.  
- ✅ **Weekend vs Weekday Comparison**: Occupancy and ADR split by day type  

---

## 📊 Key Insights from the Dashboard
- **Total Revenue**: ₹1.69 Bn across properties  
- **RevPAR**: ₹7,336 overall average  
- **Daily Sellable Room Nights (DSRN)**: 2,530+  
- **ADR (Average Daily Rate)**: ₹12,696  
- **Occupancy %**: 57.79% (higher on weekends ~62.64%)  
- **Realisation %**: 70.14%  

### 🔎 Revenue Breakdown
- Luxury category → **61.62%** of total revenue  
- Business category → **38.38%** of total revenue  

### 🔎 Platform Insights
- Realisation % is highest in **Direct Offline (70.92%)**  
- ADR is highest in **Direct Online (~₹12,800)**  

### 🔎 Property-Level Observations
- **Highest Revenue Property**: Atiq Grands (Hyderabad) – ₹88M  
- **Lowest Revenue Property**: Atiq City (Bangalore) – ₹8M  
- **Occupancy Leader**: Atiq Bay (Hyderabad) – 65.61%  
- **Highest Cancellation %**: Atiq Exotica (Hyderabad) – 27.44%  
- **Best Rated Property**: Atiq Bay (Bangalore) – ⭐ 4.28  

---

## 📸 Demo Screenshot
Here’s a snapshot of the interactive dashboard:  

![Dashboard Demo](./Dashbord%20screenshort.png)

---
