# NETFLIX-SHOWS-MOVIES-SQL-PROJECT
SQL-based analysis of Netflix movies and TV shows using PostgreSQL. This project explores trends, actor performance, genre insights, and growth patterns using advanced SQL techniques like joins, aggregations, window functions, and data transformation.

# 🎬 Netflix Movies & Shows Analysis (SQL Project)

## 📌 Overview
This project analyzes a dataset of movies and TV shows using PostgreSQL.  
It focuses on extracting meaningful insights using SQL concepts like JOINs, Aggregations, Window Functions, and Data Transformation.

---

## 🛠️ Tech Stack
- PostgreSQL (pgAdmin)
- SQL (Advanced Queries)
- CSV Dataset

---

## 📂 Dataset
- `titles.csv` → Movies & Shows data (from kaggle) 
- `credits.csv` → Actors & Directors info (from kaggle) 

---

## 🧱 Database Schema
- **titles** (id, title, type, release_year, imdb_score, tmdb_score, runtime, genres, etc.)
- **credits** (person_id, id, name, role, character)

---

## 🔑 Key SQL Concepts Used
- JOINs (Inner Join, Self Join)
- GROUP BY & Aggregations
- HAVING Clause
- Window Functions (LAG, ROW_NUMBER)
- CASE WHEN
- STRING_TO_ARRAY & UNNEST
- Data Cleaning (TRIM, NULL handling)

---

## 🔥 Key Insights

1. 🎯 Directors with ≥5 movies and avg IMDB >7 show consistent high performance  
2. 🎭 Certain genres have higher audience engagement based on TMDB popularity  
3. 🎬 Some actors have worked across a wide variety of genres (high versatility)  
4. 📈 TV Shows have seen rapid growth compared to Movies in recent years  
5. 🤝 Strong actor-director collaborations exist in high-rated content  
6. ⭐ A small group of actors maintain a high “hit ratio” (IMDB >7) consistently  
7. 🎥 High-rated movies are often concentrated in specific genres  
8. ⏳ Runtime varies significantly across genres impacting engagement  
9. 📊 Multi-genre movies required normalization using UNNEST for accurate analysis  
10. 🧠 Window functions helped identify year-over-year growth trends  

---

## 📊 Sample Queries
- Top rated movies
- Genre-wise analysis
- Actor performance metrics
- Collaboration analysis
- Growth trends over time

---

## 🚀 How to Run
1. Import CSV files into PostgreSQL
2. Create tables using provided schema
3. Run SQL queries in pgAdmin
4. Analyze outputs

---

## 📌 Conclusion
This project demonstrates how SQL can be used not just for querying data, but for extracting real-world business insights.

---

## ⭐ Support
If you found this project useful, don’t forget to **⭐ star the repo**!
