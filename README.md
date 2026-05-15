# Customer360 SQL Data Model
A multi-source SQL data model that integrates five datasets — conversions, orders, customers, products, and dates, into a unified Customer360 table.

## What it does
- Tracks each customer's full conversion history
- Identifies the first order placed after each conversion
- Aggregates weekly revenue per customer
- Calculates cumulative lifetime revenue

## SQL Techniques Used
- CTEs (Common Table Expressions) for modular, readable logic
- Window functions for rankings and cumulative metrics
- Time-based joins to align events across conversion windows

## Output
A single Customer360 table combining static customer attributes, first order details, weekly activity, and lifetime cumulative metrics — ready for advanced analytics.
