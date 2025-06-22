# 🚲 Cyclistic Bike-Share Case Study

This project is part of the Google Data Analytics Certificate capstone, based on the fictional company **Cyclistic**, a bike-share program in Chicago.

## 📌 Business Task

Analyze how annual members and casual riders use Cyclistic bikes differently. The goal is to provide insights that will help the marketing team convert more casual riders into annual members.

## 🧠 Key Questions

1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can digital media influence casual riders to become members?

## 🧰 Tools Used

- **Google Sheets** for data cleaning, transformation, and analysis  
- **Pivot Tables** for aggregations  
- **Charts** for visualizations  
- **Google Slides/Docs** (optional) for presentation

## 📊 Data Sources

Public datasets from [Divvy Bike Share](https://divvy-tripdata.s3.amazonaws.com/index.html), covering the most recent 12 months of trip data. Data was anonymized and complies with privacy guidelines.

## 🔄 Data Processing

- Calculated ride length: `ride_length = ended_at - started_at`
- Extracted `day_of_week` using `=WEEKDAY(started_at, 1)`
- Filtered and formatted to remove null or incorrect data

## 📈 Analysis Highlights

- **Average Ride Length** by `member_casual`
- **Ride Trends** by `day_of_week`
- **Most Frequent Ride Day** using mode
- **Pivot Tables** to analyze usage patterns

## ✅ Key Findings

- Casual riders generally take longer rides than members.
- Members tend to ride more consistently throughout the week.
- Weekends show higher usage by casual riders, suggesting leisure trips.

## 💡 Recommendations

1. Launch weekend-focused promotions targeting casual riders.
2. Offer discounts or trial memberships to high-usage casual riders.
3. Use targeted digital marketing on days when casual ridership is highest.

## 🗂️ Files

- `/data`: Raw and cleaned CSV files  
- `/notebooks`: Analysis sheets or scripts  
- `/slides`: Optional presentation of findings

