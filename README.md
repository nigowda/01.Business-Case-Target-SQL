# 🛒 Target Brazil E-Commerce SQL Case Study

## 📌 Overview
This case study analyzes over 100,000 e-commerce orders from Target Brazil between 2016 and 2018. Using SQL on Google BigQuery, the project reveals insights into customer behavior, seasonal trends, delivery performance, and payment patterns, supporting data-driven business decisions.

---

## 📊 Dataset Summary

- 📁 Source: [Google Drive Folder](https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb)
- 📦 Format: 8 CSV files
- 📂 Tables Used:
  - `orders`
  - `order_items`
  - `customers`
  - `payments`
  - `geolocation`
  - `products`
  - `reviews`
  - `sellers`

---

## 🔍 Key Insights

### 🧭 Exploratory Analysis
- Identified schema and data types across all tables
- Mapped customer distribution by city and state
- Extracted order time range and seasonal patterns

### 📈 Order Trends
- Yearly and monthly growth in order volume
- Time-of-day segmentation: Dawn, Morning, Afternoon, Night
- Monthly order counts per state

### 💰 Economic Impact
- % increase in payment value (Jan–Aug 2017 vs 2018)
- Total & average order price and freight by state

### 🚚 Delivery Performance
- Delivery time vs estimated delivery date
- Top 5 states by:
  - Highest/lowest average freight cost
  - Fastest/slowest delivery time
  - Most efficient delivery vs estimated date

### 💳 Payment Analysis
- Monthly breakdown of payment types
- Distribution of orders by installment count

---

## 🧠 SQL Techniques Applied

- Time-series analysis using `EXTRACT`, `FORMAT_DATETIME`, `LAG`
- Delivery metrics using `DATE_DIFF`
- State-level aggregations with `JOIN`, `GROUP BY`, and CTEs
- Payment trend analysis by type and installment count
- Seasonal and hourly segmentation of order behavior

> ✅ All queries executed on BigQuery using the `TARGET_SQL` schema.

---

## 🛠️ Tech Stack

- SQL (Google BigQuery)
- Python (for future visualizations)
- Jupyter / Data Studio (optional dashboarding)

---

## 📁 Repository Contents

- `Target_SQL_NishanthGowda.docx`: Full case study document
- `README.md`: Project overview and insights
- SQL queries embedded in case study file

---

## 📬 Contact

- **Name**: Nishanth Gowda  
- **Email**: [nishanthgowdahsn27@gmail.com](mailto:nishanthgowdahsn27@gmail.com)  
- **LinkedIn**: [linkedin.com/in/nishanthgowda](https://www.linkedin.com/in/nishanthgowdahsn27/)  
- **Portfolio**: [https://github.com/nigowda]

---

> ⭐ Feel free to fork, star, or reach out for collaboration
