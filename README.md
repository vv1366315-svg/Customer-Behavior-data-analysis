# 🛍️ Customer Shopping Behavior Analysis

A complete data analytics project using **Python, SQL (PostgreSQL), and
Power BI** to uncover insights from 3,900 customer transactions.

## 📌 Project Overview

This project explores customer shopping behavior to identify spending
patterns, product preferences, customer segments, and the business
impact of discounts, subscriptions, and shipping choices.

The workflow includes: - Data cleaning & preprocessing using Python\
- Business transaction analysis using PostgreSQL\
- Insights visualization through Power BI\
- Actionable business recommendations

## 📂 Dataset Summary

-   **Rows:** 3,900\
-   **Columns:** 18\
-   **Includes:**
    -   Age, Gender, Location, Subscription Status\
    -   Item Purchased, Category, Amount, Size, Color, Season\
    -   Discount Applied, Previous Purchases\
    -   Review Rating, Shipping Type\
-   **Missing Data:** 37 missing values in Review Rating

## 🧹 Data Preparation & Cleaning (Python)

-   Loaded dataset with pandas\
-   Explored using `.info()` and `.describe()`\
-   Imputed missing review ratings by median per category\
-   Standardized column names to snake_case\
-   Added new features: age_group, purchase_frequency_days\
-   Removed redundant column promo_code_used\
-   Loaded cleaned data to PostgreSQL

## 🧮 Business Analysis Using SQL

-   Revenue by Gender\
-   High-Spending Discount Users\
-   Top 5 Products by Review Rating\
-   Shipping Type Comparison\
-   Subscribers vs Non-Subscribers\
-   Discount-Dependent Products\
-   Customer Segmentation (New, Returning, Loyal)\
-   Top 3 Products per Category\
-   Repeat Buyers & Subscription Likelihood\
-   Revenue by Age Group

## 📊 Power BI Dashboard

Interactive dashboard includes: - Revenue insights\
- Customer segmentation\
- Product performance\
- Discount and shipping patterns\
- Demographic analysis

## 💡 Business Recommendations

-   Promote subscriptions\
-   Implement loyalty programs\
-   Optimize discount strategy\
-   Feature top-rated products\
-   Target profitable age groups\
-   Enhance express shipping offerings

## 🛠️ Tech Stack

-   Python (pandas, numpy, matplotlib)\
-   PostgreSQL\
-   Power BI\
-   Markdown documentation

## 📁 Suggested Repository Structure

    📦 customer-shopping-analysis
    │-- README.md
    │-- data/
    │-- notebooks/
    │-- sql/
    │-- dashboard/
