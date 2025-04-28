# 🏍️ Motorcycle Sales Analysis (PostgreSQL)

## Project Objective

- Analyze **wholesale revenue** by **product line**.
- Understand how revenue varies **month-to-month** and **across warehouses**.

## Approach

- Filter data for **Wholesale** orders.
- Calculate **net revenue** after adjusting for payment method fees.
- Group results by **month**, **warehouse**, and **product line**.
- Summarize total **net revenue**.

## PostgreSQL Techniques and Tools Used

- `WHERE` clause to filter for **"Wholesale"** orders.
- `EXTRACT()` function to extract **month** and **year**.
- `CASE WHEN` for **payment fee adjustments**.
- `SUM()` aggregation for **total revenue**.
- `GROUP BY` for **structured aggregation**.
- **CTEs** (Common Table Expressions) for cleaner queries.
- `JOIN` to combine **sales** and **warehouses** tables.
- **Indexes** (optional) to improve query performance.
