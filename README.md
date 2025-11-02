# EDAHospitality
# 🏨 Booking Behavior & Revenue Analysis

This project explores booking behavior, platform performance, and revenue trends using real-world hospitality data. It combines multiple datasets, performs ad hoc analysis, and delivers actionable insights through visual storytelling.

## 📦 Dataset Overview

The project uses five CSV files containing booking, hotel, room, and platform metadata. Key fields include:
- `booking_id`, `property_id`, `booking_date`, `check_in_date`, `checkout_date`
- `no_guests`, `room_category`, `booking_platform`, `ratings_given`, `booking_status`
- `revenue_generated`, `hotel_star_rating`, `hotel_review_score`, `hotel_city`

## 🔗 Data Integration & Cleaning

- Merged multiple datasets using `property_id` and `room_category` as keys
- Validated joins and handled mismatches with inner and left merges
- Converted date columns to `datetime` format with error handling
- Imputed missing values using statistical and contextual logic
- Engineered features like `weekday`, `month`, and `lead_time`

## 🔍 Ad Hoc Analysis Highlights

- Booking volume trends by day of week and room category
- Revenue distribution across booking platforms
- Booking status breakdown (confirmed vs cancelled)
- Ratings behavior and its correlation with booking outcomes

## 📊 Visualizations

- Pie Chart: Revenue share by booking platform
- Bar Chart:Booking volume by days of week
- Correlation Heatmap with Seaborn


## 🛠️ Tools & Libraries

- pandas
- matplotlib
- seaborn
- Jupyter Notebook


