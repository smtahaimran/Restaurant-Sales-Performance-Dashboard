# Restaurant Sales Performance Dashboard

A one-page Power BI dashboard analyzing two years of transaction-level sales data for a 3-branch restaurant chain, from raw POS data to a decision-support dashboard.

<img width="611" height="338" alt="Screenshot 2026-08-19 213000" src="https://github.com/user-attachments/assets/43efda0d-6d11-4bee-a71b-def945a085d7" />


## Problem Statement:

There had two years of raw POS sales data across three branches but no consolidated view of performance, leaving unable to see which branches, channels, and menu items were driving revenue, when their peak demand periods were, and whether their discounting strategy was helping or hurting margins.

**Goal:** Consolidate the raw data into a single Power BI dashboard that supports data-driven decisions on staffing, menu planning, and promotions.

---

## Dataset:

- **Volume:** 26,945 line items across 10,404 unique orders
- **Time range:** January 2023 – December 2024
- **Scope:** 3 branches, 45 menu items across 9 categories, 3 order types (Dine-in / Takeaway / Delivery), 3 payment methods


---

## Dashboard Overview

**One-page layout:** 5 KPI cards, 4 slicers, and 7 visuals (each one mapped directly to a question in the problem statement).


**Visuals:**
- | Monthly Revenue Trend (2023 vs 2024) | Line chart | Is the business growing, and what does seasonality look like? |
- | Revenue by Branch | Donut Chart | Which branch drives the most revenue? |
- | Revenue by Category | Treemap | Which menu categories perform best? |
- | Revenue by Menu Item | Clustered Bar Chart | Which dishes to promote — and which underperform? |
- | Order Volume by Day & Hour | Matrix | When are we busiest? (staffing decisions) |
- | Order Type Share by Year | 100% stacked bar | Is our channel mix (dine-in/takeaway/delivery) shifting? |
- | Orders by Discount Level | Clustered Column Chart | Is discounting driving volume, or just eating margin? |

---

## Key Insights:


- The business grew nearly 8% from 2023 to 2024, with total sales rising from about $300,000 to $324,000. This growth wasn't random — it followed a clear seasonal pattern, peaking in December and dipping in January and February each year.
- Downtown Central is the strongest performing branch, bringing in 38% of total revenue, compared to 34% from Uptown Heights and just 28% from Riverside Mall. Riverside Mall is generating roughly 27% less revenue than the top branch.
- A small group of dishes is responsible for a large share of sales. Just five items — Ribeye Steak, Classic Beef Burger, Herb Roasted Chicken, Pepperoni Pizza, and Grilled Salmon — bring in over a quarter of all revenue, even though they make up only 5 out of 45 menu items.
- Customer demand is highly predictable by time of day. Lunch (12:00–1:00 PM) and dinner (6:00–8:00 PM) are consistently the busiest windows, and Friday and Saturday evenings are noticeably busier than the rest of the week.
- Discounts are not increasing how much customers spend per order. Customers who received a discount actually spent slightly less on average ($55.75 per order) than customers who paid full price ($60.53 per order) — and the gap grows larger with bigger discounts.

---

## Recommendations:

- Plan staffing and inventory around known busy periods. Schedule more staff during lunch and dinner hours, especially on Friday and Saturday evenings, and prepare for a sales increase in December along with a slower period in January and February.
- Look into why Riverside Mall is underperforming. Since this branch relies more heavily on delivery orders, consider whether it needs stronger delivery partnerships, faster delivery times, or local promotions to close the gap with the other branches.
- Promote and protect your five best-selling dishes. Feature them prominently on the menu, in marketing, and in online listings, and make sure they never run out of stock, since they carry a disproportionate share of your revenue.
- Reconsider low-performing menu items. Dishes like the soups, espresso, and orange juice bring in very little revenue on their own. Consider removing them, combining them into value bundles, or replacing them with better-performing alternatives to simplify kitchen operations.
- Rethink your discount strategy. Since discounts aren't encouraging customers to spend more, avoid offering them broadly. Instead, use them more selectively, such as during slow periods to bring in extra customers, or as a one-time incentive for first-time visitors, rather than as a routine promotion.

---

> **Note:** This is a synthetically generated dataset built with realistic statistical patterns.
