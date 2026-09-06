# Hotel Booking Analysis Dashboard

A hotel booking data analysis project built using **Excel** and **Power BI**, covering the full workflow from raw data cleaning to an interactive dashboard.

## 📌 Project Overview

This project analyzes hotel booking data to uncover trends around bookings, cancellations, revenue, room popularity, and customer segments. The goal was to take a messy real-world dataset and turn it into a clean, decision-ready dashboard.

## 📂 Dataset

- **Source:** [Hotel Booking Demand — Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
- Original dataset: ~119,000 bookings across a City Hotel and Resort Hotel.
- Final working dataset: **4,096 cleaned records**, sampled while preserving the original cancellation ratio.

## 🛠 Tools Used

- **Excel** — data cleaning, calculated columns, initial pivot summaries
- **Power BI** — data modeling, DAX measures, interactive dashboard

## 🧹 Data Preparation

- Removed duplicate records
- Fixed inconsistent/typo values in category fields (e.g. customer type labels)
- Handled missing values
- Engineered new fields not present in the raw data:
  - `Booking_ID`
  - `Booking_Date`
  - `Check_In` / `Check_Out`
  - `Number_of_Guests`
  - `Booking_Status` (Cancelled / Confirmed)
  - `Revenue`
  - `Stay_nights`

## 📊 Power BI Dashboard

**File:** `hotel_book.pbix`

**Key DAX measures:**
- `Total Bookings`
- `Cancelled Bookings`
- `Total Revenue`
- `Cancellation Rate %`

**Visuals included:**
- KPI cards: Total Bookings, Total Revenue, Cancelled Bookings, Cancellation Rate %
- Monthly Booking Trend (line chart)
- Room Popularity (bar chart)
- Revenue by Room Type (donut chart)
- Customer Segments (donut chart)
- Cancelled vs Confirmed (donut chart)

## 💡 Key Insights

- **Room Type A** drives the highest volume of bookings and the largest share of revenue.
- **Cancellation rate stands at ~27.7%**, a significant share worth business attention.
- **Bookings peak around July–August**, with a sharp decline after September.
- **Family/Friends** is the dominant customer segment, making up roughly 79% of bookings.

## 📁 Files in this Repo

| File | Description |
|---|---|
| `Hotel_Booking_Data.xlsx` | Cleaned dataset with calculated columns |
| `hotel_book.pbix` | Power BI dashboard file |

## 🚀 How to View

1. Download `hotel_book.pbix`
2. Open it in **Power BI Desktop** (free download from Microsoft)
3. Explore the interactive dashboard — filter, click, and drill through the visuals

---

*Built as a personal data analysis project to practice end-to-end workflow: data cleaning → transformation → dashboard design.*
