# Swiggy Data Analysis

Analysis of Swiggy's food delivery operations across 9 Indian cities using SQL. Dataset includes 8,680 restaurant records covering pricing, ratings, delivery times, and customer preferences across 833 geographic areas.

## Overview

This analysis examines the Swiggy platform to understand restaurant performance, pricing patterns, and delivery efficiency. The goal is to identify optimization opportunities for platform operations and restaurant partners through data-driven insights.

## Project Objectives

- Identify top-performing restaurants and food categories by volume and rating
- Analyze pricing strategies and their correlation with customer ratings
- Evaluate geographic performance and delivery efficiency by city
- Determine customer preferences by cuisine type
- Benchmark restaurant performance metrics

## Dataset Overview

| Aspect | Details |
|--------|---------|
| Records | 8,680 |
| Columns | 10 |
| Cities | 9 (Bangalore, Mumbai, Delhi, Hyderabad, Pune, Kolkata, Chennai, Ahmedabad, Surat) |
| Unique Restaurants | 7,865 |
| Geographic Areas | 833 |
| Price Range | ₹0–₹2,500 (avg ₹348) |
| Rating Range | 2.0–5.0 (avg 3.66) |
| Delivery Time | 20–109 min (avg 54 min) |

## Technologies Used

- SQL (MySQL/PostgreSQL)
- Python (data validation)
- Excel (reporting)

## Project Structure
swiggy_data_analysis/
├── swiggy_data.csv # Raw dataset
├── Query.sql # 11 SQL analysis queries
├── swiggy_report.docx # Executive summary
└── README.md


## SQL Analysis Performed

- Aggregate statistics (count, sum, average, rounding)
- Food type performance ranking by volume and ratings
- City-wise rating comparisons
- Restaurant frequency and distribution analysis
- Price and rating correlations by cuisine and restaurant
- Multi-dimensional aggregations for performance benchmarking

## Key Business Insights

- Indian cuisine dominates order volume (389 items), followed by Chinese (277) and North Indian (246)
- Average item price of ₹348 with concentration between ₹250–₹500 range
- Most restaurants maintain 3.5–4.0 star ratings; only few achieve 4.5+ consistency
- Significant delivery time variation across areas (20–109 min) suggests logistics optimization opportunity
- Franchise models (La Pino'Z, Subway, KFC) appear multiple times, indicating successful scalability
- Restaurants with higher ratings should see proportional revenue impact, suggesting quality-based positioning strategy

## Repository Contents

- **swiggy_data.csv**: Full dataset with 10 columns including location, restaurant name, price, ratings, and delivery metrics
- **Query.sql**: 11 SQL queries covering aggregations, grouping, and comparative analysis
- **swiggy_report.docx**: Summary report with findings

## How to Run

1. Load `swiggy_data.csv` into MySQL/PostgreSQL
2. Execute queries from `Query.sql` sequentially
3. Review output tables for insights
4. (Optional) Create visualizations from query results

## Author

Vivek7ok  
[GitHub](https://github.com/Vivek7ok/Swiggy_data_analysis)
