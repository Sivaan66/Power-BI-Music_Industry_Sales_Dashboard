# 🚀 Power BI Sales Performance Dashboard

A fully interactive Power BI dashboard that analyzes and visualizes company sales data across multiple dimensions — product, region, and time. This project is designed to provide actionable insights for business decision-making.

---

## 📖 Table of Contents
- [Problem Statement](#problem-statement)
- [Business Objectives](#business-objectives)
- [Data Description](#data-description)
- [ETL Process](#etl-process)
- [Dashboard Overview](#dashboard-overview)
- [Key Insights](#key-insights)
- [How to Use](#how-to-use)
- [Files Included](#files-included)
- [Conclusion](#conclusion)

---

## 🧩 Problem Statement

The prevailing business challenge is to optimize the marketing and advertisement strategy for Sway's second album release to ensure it gains global recognition and success. Some challenges include:

 

✓ Limited Global Reach: Presently, Sway's popularity is confined to specific regional pockets, posing a significant hurdle in achieving global recognition. A crucial task is expanding Sway's fan base to encompass a worldwide audience, thereby broadening the album's reach.
 

✓ Intense Competition: The music industry operates within an environment of cutthroat competition, intensifying the difficulties faced by emerging artists. Navigating this fiercely competitive landscape necessitates a carefully crafted advertising strategy that can help Sway stand out amidst a sea of talent.
 

✓ Evolving Consumer Preferences: The music consumption landscape is continuously shifting, driven by rapid changes in technology and consumer behavior. Staying attuned to these dynamic preferences is imperative, as it demands continuous adaptation and innovation in our marketing approach to effectively connect with the target audience on the platforms they favor.s

---

## 🎯 Business Objectives

- Achieving global recognition and success
- Data-Driven Decision Making
- Platform Optimization
- Audience Segmentation
- Campaign Effectiveness

---

## 🗃️ Data Description

SunMusic has information on 3000 listeners, which will be analyze for actionable insights:

**Listeners Dataset:**

✓ Listeners_ID: A unique identifier for each listener.  

✓ Age: The age of the listener.  

✓ Gender: The gender of the listener (Male, Female, Others).  

✓ Location: The location of the listener, randomly selected from various cities.  

✓ Music_Preferences: The music genre preference of the listener (Pop, HipHop, Alternative, Country, RnB).  

✓ Income_Level: The income level of the listener (Low, Medium, High).  

✓ Platform: The social media platform the listener is associated with (TikTok, Twitter, Instagram).  

✓ Album_Sales: The number of albums a listener has purchased.  

✓ Streaming_Numbers: The number of music streams per listener.  

✓ Streaming_Platform: The streaming platform used by the listener (Spotify, YouTube, Apple Music, Tidal, Others).  

✓ Acquisition_Medium: The method or medium through which the listener was acquired (Organic, Adverts, Radio plays, Influencers).  

**Competitors Analysis Dataset:**  

✓ Competitor_Name: The name of the competitor artist.  

✓ No_of_Followers: The number of followers or fans the competitor has.  

✓ Album_Sales: The competitor's album sales  

✓ Streaming_Numbers: The competitor's streaming numbers  

✓ Genre: The music genre associated with the competitor (Pop, HipHop, Alternative, RnB, Country).  

> Check [`/Data`](./competitors_analysis_dataset.csv/) for raw and cleaned datasets.

---

## 🔄 ETL Process

- **Extracted** raw sales data from Excel files
- **Transformed** using Power Query (date parsing, missing value treatment, category grouping)
- **Loaded** into Power BI for modeling and visualization

> See the [cleaning SQL](./Scripts/clean_data.sql) and [data dictionary](./Docs/Data_Dictionary.md)

---

## 📊 Dashboard Overview

![Dashboard Screenshot](./Images/dashboard_overview.png)

The dashboard includes:
- KPIs: Total Revenue, Units Sold, Avg Revenue/Unit
- Line Chart: Sales trend over time
- Bar Chart: Sales by region
- Pie Chart: Revenue by product category
- Filters: Time, Region, Product Type

---

## 🔍 Key Insights

| Insight | Detail |
|--------|--------|
| 🟢 Region A | Contributed 32% of total revenue |
| 🔴 Product X | Declining sales for 3 consecutive quarters |
| 📈 Q4 Spike | Most sales happen in Q4 (seasonal trend) |

---

## 🧭 How to Use

1. Download `PowerBI_Dashboard.pbix`
2. Open in **Power BI Desktop**
3. Use slicers (time, region) to explore custom views
4. Hover on visuals for tooltips and deep insights

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `PowerBI_Dashboard.pbix` | Main dashboard |
| `Raw_Dataset.csv` | Unprocessed sales data |
| `Cleaned_Dataset.csv` | Prepped data for BI |
| `dashboard_overview.png` | Screenshot preview |
| `Project_Report.pdf` | Full documentation of project |

---

## ✅ Conclusion

This Power BI dashboard empowers stakeholders with real-time insights into sales performance, helping to identify bottlenecks, opportunities, and trends at a glance.

---

## 🙋‍♂️ Author

**Your Name**  
[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue)](https://github.com/yourusername)

---
