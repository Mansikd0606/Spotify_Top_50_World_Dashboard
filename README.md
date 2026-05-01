# Spotify_Top_50_World_Dashboard

🔹 Project Overview

This project focuses on analyzing global music trends using a dataset inspired by Spotify Top-50 charts. The goal was to uncover insights about song popularity, artist performance, album types, and listening behavior through an interactive Power BI dashboard.

---

🔹 Objectives
 - Analyze song popularity trends over time
 - Identify top-performing artists and songs
 - Compare explicit vs non-explicit content
 - Understand the impact of album type and duration on popularity
 - Build an interactive and visually appealing dashboard

---

🔹 Dataset Description

The dataset contains the following key columns:
 - Date (chart tracking date)
 - Song & Artist
 - Popularity Score
 - Position (ranking)
 - Duration (ms)
 - Album Type (Single, Album, Compilation)
 - Release Date
 - Explicit Content Flag
 - Album Cover URL

---

🔹 Tools & Technologies Used
 - Power BI Desktop (Data visualization & modeling)
 - Power Query (Data cleaning & transformation)
 - DAX (Data Analysis Expressions) (Measure creation)

---

🔹 Data Cleaning & Transformation
Performed using Power Query:
 - Handled missing/null values
 - Standardized date formats
 - Created derived columns (Month, Year)
 - Removed duplicates

---

🔹 Key DAX Measures Created
 - Total Songs
 - Distinct Artists
 - Average Popularity
 - Top 10 Songs Count
 - Explicit %
 - Avg Duration
 - Popularity vs Rank Score
 - Top Artist & Top Song

---

🔹 Dashboard Features

🏠 Overview Page
- KPI Cards:
  - Total Songs (789)
  - Distinct Artists (342)
  - Avg Duration (3.28 min)
  - Avg Popularity (90)
- Visuals:
  - Songs by Album Type
  - Explicit vs Non-Explicit Distribution
  - Popularity Trend by Month
  - Distinct Songs by Month

---
    
🎤 Artist Analysis Page
 - Songs by Artist
 - Popularity by Artist
 - Top Songs by Artist
 - Artist-level performance table
👉 Insight:
 - Few artists dominate charts with multiple entries
 - Some artists have high popularity but fewer songs

---

🎵 Song Analysis Page
 - Popularity by Songs
 - Avg Duration by Songs
 - Total Songs by Artist
 - Detailed table with:
   - Release Date
   - Album Type
   - Popularity
   - Duration

---

🔹 Key Insights
 - 🎯 Singles dominate charts compared to albums and compilations
 - 📈 Popularity peaks mid-year and dips in certain months
 - 🔞 Explicit songs form a significant portion of top charts
 - � Top artists consistently appear with multiple songs
 - ⏱ Most popular songs fall within 2–4 minutes duration
 - 🏆 Strong correlation between popularity and ranking position

---

🔹 Challenges Faced

👉 1. Data Quality Issues
 - Missing values in release dates and album types
 - Solved using Power Query transformations
   
👉 2. Handling Time-Based Analysis
 - No proper date hierarchy
 - Created custom Month-Year columns
   
👉 3. DAX Complexity
 - Writing measures like Top N, ranking logic
 - Solved using CALCULATE, TOPN, SUMMARIZE
   
👉 4. Dashboard Design
 - Making UI clean and professional
 - Used consistent color themes and layout
   
👉 5. Performance Optimization
 - Large visuals slowing report
 - Optimized by reducing unnecessary columns

---

🔹 New Skills & Tools Learned
 - Advanced DAX calculations
 - UI/UX design in Power BI
 - Interactive dashboard building
 - Business storytelling with data

---

🔹 Conclusion

This project demonstrates how data visualization can be used to uncover meaningful insights from music streaming data. The dashboard enables stakeholders to understand trends, identify top-performing artists, and make data-driven decisions.











