# 🍕 Food Delivery Cost & Profitability Analysis

## Overview
This project analyzes the operational costs and profitability of a food delivery service using Python, SQL, and Tableau. The goal is to uncover inefficiencies and simulate improved pricing strategies.

## Objectives
- Calculate total costs, revenue, and profit per order
- Identify loss-making patterns (e.g. discount-heavy orders)
- Simulate changes in commission and discount rates
- Visualize key business insights in Tableau

## Tools Used
- Python (pandas, matplotlib, seaborn)
- SQLite (for structured querying)
- Tableau Desktop (interactive dashboards)

## Key Findings
- Discounts caused 45% of total losses
- Average profit margin was negative across payment methods
- Simulated strategy (30% commission, 6% discount) turned losses into profit

## File Structure
| File | Description |
|------|-------------|
| `food_delivery_data.csv` | Original raw dataset |
| `load_to_sqlite.py` | Loads data into SQLite (`food_delivery.db`) |
| `delivery_analysis.ipynb` | EDA, metric calculations, simulations |
| `sql_queries.sql` | Profit and KPI queries used in Tableau |
| `dashboard.twbx` | Tableau dashboard with all key visuals |
| `screenshots/` | Visual exports for use in README or portfolio |

## Preview
![Profit Distribution](screenshots/profit_distribution.png)
![Cost Breakdown Pie](screenshots/cost_breakdown_pie.png)

## How to Reproduce
1. Run `load_to_sqlite.py` to create the SQLite DB
2. Explore or run SQL queries from `sql_queries.sql`
3. Open `dashboard.twbx` in Tableau Desktop

---
