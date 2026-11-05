# Lazada Sales Report

Skills Used: Excel, Power BI, DAX, Data Modeling, E-commerce Analytics

A Power BI report on 2023 Lazada sales performance, covering sales value, items sold, delivery success, returns, product categories, and customer lifetime value (LTV).

Interactive dashboard: [Open in Power BI](https://app.powerbi.com/view?r=eyJrIjoiOTk1OThhNGItYmE0OC00Y2ZjLWFjZDgtM2E3ZmU3NjZmOWM3IiwidCI6Ijg5NjQxZWIwLWU1ZmMtNDRlYi05MWRiLTc4ZDI5YmFkMTc3OCIsImMiOjEwfQ%3D%3D)

## Files

| File | Description |
|------|-------------|
| [5. Lazada Sale Report.xlsx](5.%20Lazada%20Sale%20Report.xlsx) | Source data: `Sales`, `Product` and `Data Dictionary` sheets |
| [5. Lazada Sales Dashboard.pbix](5.%20Lazada%20Sales%20Dashboard.pbix) | Power BI report file |
| [5. Lazada Sales Dashboard.pdf](5.%20Lazada%20Sales%20Dashboard.pdf) | PDF export of the report |
| [5. Lazada Sales Dashboard.png](5.%20Lazada%20Sales%20Dashboard.png) | Full report preview |

## Dataset

Order-level transactions for 2023. Each row is one order line, with these fields:

- **Order info:** Date, Status (Shipped, Delivered to Buyer, Cancelled, payment_failed), Successful delivery, Returned, Return value
- **Fulfilment:** Fulfilment (Lazada / Merchant), Sales Channel, Ship-service level (Standard / Expedited)
- **Product:** SKU, Qty, Items sold, Amount, Total amount, currency (USD)
- **Customer:** Type (B2C / B2B), Customer ID, Address (city, state)

## Report Pages

1. **Overview:** KPI cards (sales value, items sold, successful deliveries, return rate) with month-over-month change; monthly sales and items-sold trend; sales value by category, fulfilment, type and shipping mode; sales by state; items sold by size.
2. **Product Analysis:** price vs. quantity sold scatter by category; customer lifetime value distribution; order-day heat matrix by category.
3. **Details:** a table that can be switched by a parameter (date, and other dimensions), showing items sold, sales value, % of total, average transaction value, return rate and return value.
4. **Key findings & Insight:** a written summary of the results.

All pages can be filtered by Month-Year, State and City.

## Key Metrics

- **Sales value:** $6,272,922
- **Quantity of items sold:** 44,692
- **Successful deliveries:** 44,570
- **Return rate:** 1.90% (return value $123,616)
- **Average transaction value:** $140.4

## Summary of Insights

1. The business made **$6.27M in sales** from 44,692 items. **Sets & Suits (49.0%)** and **Tops & Dresses (48.4%)** bring in almost all of the revenue.
2. The overall **return rate is 1.90%**, which points to good customer satisfaction. Some days still reach a return rate of up to **6.35%**, so those days need monitoring.
3. Most customers have a **lifetime value of $100–$250**. Only a small group spends more than $500.
4. **Price and quantity move in opposite directions.** Lower-priced items sell in higher volumes, especially in Tops & Dresses.
5. The **average order contains about 1 item**, so there is room to grow basket size.
6. Sales are spread evenly across states: California, American Samoa and District of Columbia lead at about $640K each.
7. Size **L** sells the most (29.15% of items), followed by M (17.58%) and XL (16.72%).

## Recommendations

- Use **loyalty programs and targeted promotions** to move customers from the $100–$250 LTV range into higher tiers.
- Introduce **bundling and cross-selling** (for example, tops with bottoms) to raise items per order.
- Apply **price-based strategies** to Tops & Dresses: keep entry-level prices for volume and bundle higher-priced items.
- **Look into the days with high return rates** (above 3%) by SKU and size to find quality or sizing problems.
- Plan stock around **size demand (L, M, XL)** to reduce stock-outs and overstock.

## Dashboard Preview

![Lazada Sales Dashboard](5.%20Lazada%20Sales%20Dashboard.png)

## Dataset Preview

![Lazada Sales Dataset preview](Data%20preview.png)
