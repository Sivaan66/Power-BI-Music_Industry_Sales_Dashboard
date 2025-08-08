# 🚀 Marketing and Advertising Analysis for Sway's Album Release

- The aim of this project is to propel Sway's second album to international stardom by strategically optimizing the advertising and marketing strategy. The primary objective is to transform Sway from a regional sensation into a globally recognized and celebrated artist. 

 

- To achieve this, the project seeks to overcome several key challenges, including expanding Sway's fan base beyond specific regions, navigating the highly competitive music industry, and adapting to evolving consumer preferences in music consumption.

 

- By leveraging marketing analytics and the insights, innovative campaigns and data-driven decision-making will be employed. This approach aims to not only ensure the album's global success but also solidify Sway's position as a rising star in the international music scene.

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

 

**✓ Limited Global Reach:** Presently, Sway's popularity is confined to specific regional pockets, posing a significant hurdle in achieving global recognition. A crucial task is expanding Sway's fan base to encompass a worldwide audience, thereby broadening the album's reach.
 

**✓ Intense Competition:** The music industry operates within an environment of cutthroat competition, intensifying the difficulties faced by emerging artists. Navigating this fiercely competitive landscape necessitates a carefully crafted advertising strategy that can help Sway stand out amidst a sea of talent.
 

**✓ Evolving Consumer Preferences:** The music consumption landscape is continuously shifting, driven by rapid changes in technology and consumer behavior. Staying attuned to these dynamic preferences is imperative, as it demands continuous adaptation and innovation in our marketing approach to effectively connect with the target audience on the platforms they favor.s

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

**✓ Listeners_ID:** A unique identifier for each listener.  
**✓ Age:** The age of the listener.  
**✓ Gender:** The gender of the listener (Male, Female, Others).  
**✓ Location:** The location of the listener, randomly selected from various cities.  
**✓ Music_Preferences:** The music genre preference of the listener (Pop, HipHop, Alternative, Country, RnB).  
**✓ Income_Level:** The income level of the listener (Low, Medium, High).  
**✓ Platform:** The social media platform the listener is associated with (TikTok, Twitter, Instagram).  
**✓ Album_Sales:** The number of albums a listener has purchased.  
**✓ Streaming_Numbers:** The number of music streams per listener.  
**✓ Streaming_Platform:** The streaming platform used by the listener (Spotify, YouTube, Apple Music, Tidal, Others).  
**✓ Acquisition_Medium:** The method or medium through which the listener was acquired (Organic, Adverts, Radio plays, Influencers).  
**> Check [`/Data`](./listeners_dataset.csv/) for raw and cleaned datasets.**

**Competitors Analysis Dataset:**  

**✓ Competitor_Name:** The name of the competitor artist.  
**✓ No_of_Followers:** The number of followers or fans the competitor has.  
**✓ Album_Sales:** The competitor's album sales  
**✓ Streaming_Numbers:** The competitor's streaming numbers  
**✓ Genre:** The music genre associated with the competitor (Pop, HipHop, Alternative, RnB, Country).  
**> Check [`/Data`](./competitors_analysis_dataset.csv/) for raw and cleaned datasets.**

---

## 🔄 ETL Process

✓ **Data Importation:** SunMusic data is imported from its data source into Power BI environment.

✓ **Data Cleaning & Transformation:**  Data is cleaned and transformed in Power BI

✓ **Data Analysis:** The dataset is explored and analysed 

✓ **Data Analysis & Visualization:** The dataset is visualized in form of dashboard, reports and sent to the stakeholders or marketing and advertising department of SunMusic to optimize the insights during campaigns .

---

## 📊 Dashboard Overview

![Dashboard Screenshot](./DashBoard.pdf)

The dashboard includes:
- **KPIs:** Total Listeners, Total male listeners, Total female listeners, Streaming numbers, total album sales
- **Line Chart:** Total listeners by location, Total listeners by Age range, Total listeners by location
- **Bar Chart:** Total listeners by Age range, Total listeners by music preferences, Total listeners by income level
- **Pie Chart:** Total Listeners by aquisition medium and streaming medium
- **Filters:** Genre, Location, Competitior name

---

## 🔍 Key Insights

- From Sway's 3,000 listeners which comprises,  50.8% female, 46.7% male and 2.5% Others. 
- A significant proportion of her listeners fall within the age bracket of 39 to 45. 
- The predominant musical preference among her audience is pop. Furthermore, the majority of the listeners belong to the low-income demographic. 
- Geographically, the highest concentration of her audience is situated in Melbourne.
- Among the ten competitors, Sway's album sales and streaming numbers ranked the lowest. However, Sway boasts of a good presence on social media, with 3k  followers/listeners, making her the fourth highest among her competitors. Additionally, she has a significant following on Instagram.
- Sway contends with ten major rivals. Chris Sounds leads in album sales with 4,500 units sold. Furthermore, Melodic Maven leads in followers count while Electrovibe leads in streaming numbers in Lagos. 
- In Lagos, Sway's audience tends to lean towards Hip-Hop, while Pop takes the lead in other the locations.
- London's audience exhibits a higher prevalence in the age range 18-25, whereas Tokyo sees a larger demographic between the age range of 32-38
- Sway contends with ten major rivals. Chris Sounds leads in album sales with 4,500 units sold. Furthermore, Melodic Maven leads in followers count while Electrovibe leads in streaming numbers.
- The majority of Sway listeners were acquired through advertising effort which includes online and streaming ads
- The majority of Sway's listeners were acquired through advertising efforts.
- Spotify was the streaming platformed most used by Sway's listeners.

  **For detailed insights and further recomendations please consider to the [`/Report`](./Sway_Album_Marketing_Report.pdf/).**

---

## 🧭 How to Use

1. Download `Swey Report.pbix`
2. Open in **Power BI Desktop**
3. Use slicers (time, region) to explore custom views
4. Hover on visuals for tooltips and deep insights

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `Swey Report.pbix` | Main dashboard |
| `competitors_analysis_dataset.csv` | Competitiors data |
| `listeners_dataset.csv` | Listener's Data of Swey |
| `DashBoard.pdf` | Screenshot preview |

---

## ✅ Conclusion

This Power BI dashboard empowers stakeholders with real-time insights into sales performance, helping to identify bottlenecks, opportunities, and trends at a glance.

---

