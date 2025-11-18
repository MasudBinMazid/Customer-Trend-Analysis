# Customer Shopping Behavior Analysis 🛍️

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories. The goal was to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 🛠️ Tech Stack & Workflow
I implemented an end-to-end data analysis pipeline:
1.  **Python (Pandas):** Data cleaning, missing value imputation, and feature engineering.
2.  **PostgreSQL:** Data storage and structured analysis using SQL queries.
3.  **Power BI:** Visualization and interactive dashboard creation.

## 📂 Data Processing (Python)
Before analysis, the raw data underwent significant preprocessing:
* **Cleaning:** Handled missing values in the `Review Rating` column by imputing the median rating of product categories.
* **Standardization:** Renamed columns to snake_case for database compatibility.
* **Feature Engineering:**
    * Created `age_group` bins (Young Adult, Middle-aged, Adult, Senior).
    * Dropped redundant columns like `promo_code_used` to optimize the dataset.
* **Database Loading:** Connected Python to PostgreSQL to load the cleaned data for analysis.

## 🔍 Key Insights (SQL Analysis)
Using SQL, I answered critical business questions. Here are the highlights:

* **Revenue by Gender:** Male customers generated significantly higher revenue ($157,890) compared to female customers ($75,191).
* **Top Revenue Categories:** Clothing and Accessories are the leading categories in terms of sales volume.
* **Customer Segmentation:** The majority of the customer base (3,116 users) falls into the "Loyal" segment, indicating strong retention.
* **Subscription Impact:** While non-subscribers generate more total revenue due to volume, subscribers maintain a consistent average spend (~$59.49).
* **Demographics:** The "Young Adult" age group is the highest revenue contributor ($62,143), followed closely by "Middle-aged" shoppers.

## 📊 Power BI Dashboard
I built an interactive dashboard to visualize the trends.

![Customer Trend Dashboard](https://github.com/user-attachments/assets/b45cf8e3-ebbb-4cb6-a3cb-f4ed9ae26326)

Live Link : https://app.powerbi.com/view?r=eyJrIjoiNGJiMDJjOTUtZjE1Zi00OWQ0LWE1ZGQtNGM3ZmI0MmIwY2FkIiwidCI6ImMyMmZmN2IyLTRkYzYtNDI4Zi04NTg1LTY3N2FmNDBiYjRhZiIsImMiOjEwfQ%3D%3D

**Dashboard Highlights:**
* **Overview Cards:** Displaying Total Customers (3.9K), Average Purchase ($59.76), and Average Rating (3.75).
* **Category Breakdown:** Visuals showing Revenue vs. Sales counts by Category.
* **Demographic Trends:** Breakdowns of sales by Age Group and Subscription Status.

## 💡 Business Recommendations
Based on the data, the following strategies were recommended:
1.  **Boost Subscriptions:** Promote exclusive benefits to convert the high volume of non-subscribers.
2.  **Loyalty Programs:** specifically target "Returning" customers (701 users) to move them into the "Loyal" tier.
3.  **Targeted Marketing:** Focus ad spend on the "Young Adult" demographic and highlight top-rated items like Gloves, Sandals, and Boots.

---
*This project was created by Masud Rana Mamun.*
LinkedIn: https://www.linkedin.com/in/masudbinmazid/
