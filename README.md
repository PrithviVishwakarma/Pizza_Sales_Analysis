# Pizza Sales Performance Analysis

## 📌 Project Overview
This project presents an end-to-end data analysis solution designed to monitor, analyze, and optimize a pizza restaurant's sales performance. By combining the data-wrangling power of **SQL** with the interactive visual storytelling of **Power BI**, this project delivers actionable business insights regarding revenue patterns, customer behavior, and product performance[cite: 1, 3].

The primary goal is to calculate key business metrics (KPIs) and uncover crucial sales trends to guide data-driven decisions for inventory management, promotional strategy, and menu optimization[cite: 3].

---

## 📂 Repository Structure & Project Assets
The project relies on the following key deliverables, which should be referred to verbatim:

*   **`pizza_sales.xlsx`**: The master dataset containing raw, transaction-level records for all pizza sales (including order dates, times, quantities, prices, categories, and sizes)[cite: 1].
*   **`ALL_QUERIES.sql`**: The repository of all SQL scripts used for database creation, KPI validation, and data aggregation[cite: 1].
*   **`PIZZA SALES SQL QUERIES Document.docx`**: A detailed, formatted document containing the exact SQL syntax alongside actual database output screenshots for query verification[cite: 1, 3].
*   **`Pizza Sales Analysis DB.pbix`**: The finalized Power BI dashboard file featuring interactive visual trends, category breakdowns, dynamic filtering, and top/bottom performance matrices[cite: 1].

---

## 📊 Business Metrics & Analytics

### 1. Key Performance Indicators (KPIs)
The following foundational business metrics were written in SQL and mirrored in Power BI to ensure complete data integrity[cite: 1, 3]:

*   **Total Revenue**: The total monetary value generated from all sales ($817,860.05)[cite: 3].
*   **Total Orders**: The cumulative count of unique transactions processed (21,350 orders)[cite: 3].
*   **Average Order Value (AOV)**: The average amount spent per order ($38.31)[cite: 3].
*   **Total Pizzas Sold**: The sum of all pizza quantities ordered (49,574 pizzas)[cite: 3].
*   **Average Pizzas Per Order**: The average number of pizzas included in a single transaction (2.32 pizzas/order)[cite: 3].

### 2. Trends & Product Performance Analysis
*   **Daily & Monthly Trends**: Aggregations to identify peak order volumes by days of the week (e.g., Friday peaks) and shifting volumes across different months[cite: 1, 3].
*   **Market Share Breakdown**: Percentage of Sales (% of Revenue) sliced by **Pizza Category** (Classic, Supreme, Chicken, Veggie) and **Pizza Size** (L, M, S, XL, XXL)[cite: 1, 3].
*   **Top & Bottom Performers**: Multi-dimensional ranking of the top 5 and bottom 5 pizza variations based on **Revenue**, **Total Quantity Sold**, and **Total Orders**[cite: 1, 3].

---

## 🛠️ Technology Stack & Workflow

### Phase 1: Database Management & SQL Verification
*   The raw data from `pizza_sales.xlsx` was ingested into a relational database management system[cite: 1].
*   SQL scripts within `ALL_QUERIES.sql` were written to clean, cast, and extract metrics[cite: 1].
*   Functions like `SUM()`, `COUNT(DISTINCT)`, `CAST()`, `TO_CHAR()`, and `LIMIT` were applied to accurately structure the business metrics[cite: 1].

### Phase 2: Business Intelligence & Power BI Dashboarding
*   Connected Power BI to the verified data pipeline[cite: 1].
*   **Data Transformation (Power Query)**: Cleaned date/time formats and validated columns.
*   **Data Modeling (DAX)**: Constructed explicit measures for KPIs to match the SQL outputs precisely[cite: 1, 3].
*   **UI/UX Design**: Built an interactive executive dashboard using canvas features, navigation buttons, and category/size filters[cite: 1, 2].

---

## 🚀 How to Run the Project

1.  **Examine the Raw Data**: Open `pizza_sales.xlsx` to understand the granular transaction fields[cite: 1].
2.  **Run the Database Scripts**: Open `ALL_QUERIES.sql` in your SQL Editor to view or execute queries against your table[cite: 1]. Refer to `PIZZA SALES SQL QUERIES Document.docx` to cross-examine results[cite: 1, 3].
3.  **Interact with the Dashboard**: Open `Pizza Sales Analysis DB.pbix` using **Power BI Desktop** to filter by month, size, or category and explore dynamic insights[cite: 1, 3].
