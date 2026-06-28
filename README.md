# 🛒 E-Commerce Sales Performance Analysis — SQL Project

## Overview
Analysed a 5-table e-commerce database with 2,000+ order 
records using MySQL to generate actionable business insights 
on revenue, customers, products, and regional performance.

## 🔍 Key Analysis Performed

- **Revenue Trends:** Total revenue, monthly/yearly trend 
  breakdown, and revenue excluding returns using aggregate 
  functions and date filters

- **Customer Segmentation:** Classified customers into 
  Platinum/Gold/Silver/Bronze tiers using CASE WHEN on total 
  spend; computed Customer Lifetime Value and repeat customer rate

- **Product Analysis:** Identified top 10 products by revenue 
  and quantity; analysed return rates by category — flagged 
  categories with >30% return rate

- **Regional Insights:** Compared order volume and Average Order 
  Value across 10 regions using multi-table JOINs; identified 
  highest and lowest performing regions

- **Return & Refund Module:** Flagged frequent-return customers; 
  computed return rate by region and category

## 🛠️ Tools Used
- MySQL

## 📁 Dataset
- 5 tables
- 1,000 orders · 200 customers · 100 products
- 10 global regions · 2,000+ order records

## 💡 Key SQL Concepts Used
- JOINs, GROUP BY, HAVING
- Subqueries, CASE WHEN
- Aggregate Functions
- Date Filters
