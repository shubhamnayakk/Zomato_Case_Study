# 🍽️ Zomato SQL Data Analysis Project

## Overview
This project focuses on analyzing food delivery data using advanced SQL queries to uncover customer behavior, track growth metrics and generate actionable business insights.

---

## Objectives
- Analyze customer ordering patterns
- Measure customer acquisition and retention
- Identify high-performing cuisines and restaurants
- Evaluate the impact of promo codes
- Generate insights for business decision-making

---

## Key Analysis Performed

### 1. Top Restaurants by Cuisine
Identified top-performing outlets within each cuisine using ranking techniques.

### 2. Daily New Customer Acquisition
Tracked how many new customers were acquired each day from launch.

### 3. One-Time Customers (Jan 2025)
Found users who placed only one order in January and never returned.

### 4. Inactive Customers Analysis
Identified customers inactive in the last 7 days but acquired earlier with promo codes.

### 5. Every Third Order Targeting
Detected customers eligible for engagement campaigns after every 3rd order.

### 6. Promo Code Dependency
Found customers who always used promo codes for their orders.

### 7. Organic Customer Percentage
Calculated percentage of customers acquired organically (without promo codes).

---

## 🛠️ Tech Stack
- SQL (MySQL 8.0)
- Window Functions (ROW_NUMBER, DENSE_RANK)
- CTEs (Common Table Expressions)
- Aggregate Functions

---

## 📂 Dataset
The dataset consists of order-level data including:
- Customer ID
- Order timestamps
- Restaurant and cuisine details
- Order status
- Promo code usage

---

## How to Use
1. Create the database and table using the provided SQL script  
2. Insert the dataset  
3. Run queries one by one to explore insights  

---

## Key Insights
- Certain cuisines consistently outperform others in order volume
- A segment of customers are one-time users with no retention
- Promo codes play a major role in customer acquisition
- Identified high-value customers based on ordering frequency
- Opportunities exist to re-engage inactive users

---

## Future Improvements
- Add real-world large-scale dataset
- Optimize queries for performance
- Build dashboard visualization (Power BI/Tableau)
- Integrate with Python for advanced analytics

