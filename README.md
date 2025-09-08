# Music Store SQL Analysis 🎵

## 📌 Project Overview
This project contains **15 PostgreSQL queries** that analyze a Music Store database to uncover valuable business insights.  
The database includes information about **customers, invoices, tracks, artists, albums, and employees**.  
The analysis focuses on identifying **top customers, revenue trends, popular genres, and sales performance**.

---

## 📂 Files in This Repository
| File Name            | Description |
|----------------------|-------------|
| `schema.png`         | ERD of the database showing table relationships |
| `music_store.sql`    | PostgreSQL dump file with tables and sample data |
| `analysis_queries.sql` | 15 analytical queries |

---

## 🗂️ Database Schema
Below is the schema diagram representing the relationships between tables:

![Database Schema](https://github.com/AVYAYAWASTHI-010/Music-Store-SQL-Analysis/blob/main/MusicDatabaseSchema.png)


---

## 🧾 Sample Analysis Questions
Here are some examples of business questions answered in this project:

1. **Who is the senior-most employee based on job title?**  
2. **Which countries have the most invoices?**  
3. **What are the top 3 highest invoice totals?**  
4. **Which city generated the most revenue?**  
5. **Who is the best customer based on total spending?**  
6. **Which artist has the most rock tracks?**  
7. **Which month recorded the highest revenue?**  
8. **Tracks that are longer than the average song length.**
9. **Identify customers who spent more than 100.**
10. **Find the most popular genre by total sales.**

... and more!

---

## 🛠️ Tech Stack
- **Database:** PostgreSQL  
- **SQL Concepts Used:**  
  - `INNER JOIN`, `LEFT JOIN`
  - `GROUP BY` and `HAVING`
  - `ORDER BY` and `LIMIT`
  - Subqueries
  - Aggregations (`SUM`, `AVG`, `COUNT`)

---

## 🚀 How to Run This Project
Follow these steps to set up and run the analysis:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/AVYAYAWASTHI-010/Music-Store-SQL-Analysis.git
cd Music-Store-SQL-Analysis

# 2️⃣ Import the database into PostgreSQL
\i music_store.sql

# 3️⃣ Run the analysis queries
\i analysis_queries.sql
