# Interactive Sales Dashboard (Excel)

An interactive Excel dashboard built on order-level sales data, using PivotTables, PivotCharts, slicers and a date timeline.

## Business context

The data represents a multi-channel electronics retailer selling computers, monitors, networking gear, storage, accessories and office supplies. Orders come through four channels (Online, Retail Store, Corporate Sales, Marketplace) across five regions (North, Central, East, South, West), and each order is credited to a salesperson and tagged as a new or returning customer.

## Business question

A sales manager wants to review performance across revenue, orders, units sold, average order value, trends over time, regions, product categories, sales channels and top products.

## Dataset

- 2,000 orders, 12 columns, dated 1 Jan – 31 Dec 2026 (synthetic/practice data)
- Fields: Order ID, Date, Region, Sales Channel, Customer Type, Product Category, Product, Salesperson, Quantity, Unit Price, Discount, Revenue
- Data checks: no missing values, no duplicate Order IDs, and `Revenue = Quantity × Unit Price × (1 − Discount)` holds on every row

## Workbook structure

| Sheet | Purpose |
|---|---|
| `Start_Here` | Overview and how to use the file |
| `Dashboard_Plan` | Maps each business question to a dashboard element and source column |
| `Sales_Data` | Raw data, stored as an Excel Table |
| `Supporting_Pivots` | 9 PivotTables feeding the KPI cards and charts |
| `Sales_Dashboard` | Final dashboard: 5 charts, 4 slicers (Region, Sales Channel, Customer Type, Product Category) and a date timeline |

## Dashboard features

- KPI cards: Total Revenue, Total Orders, Quantity Sold, Average Order Value
- Monthly revenue trend
- Revenue by region, product category and sales channel
- Top 5 products by revenue
- Slicers and timeline that filter every element at once

## Key findings (full year, unfiltered)

- **Total revenue:** about $2.45M from 2,000 orders (AOV about $1,226, 5,552 units)
- **Category:** Computers drive about 55% of revenue; Monitors are next at about 21%
- **Top product:** Gaming Laptop, about $433K
- **Region:** North and Central lead (about $562K and $557K); West is lowest (about $421K)
- **Channel:** Online is largest (about $792K); Marketplace is smallest (about $310K)
- **Customers:** Returning customers generate about 69% of revenue
- **Trend:** Monthly revenue is volatile, from about $151K (Jul) to about $274K (Nov)


## Tools

Microsoft Excel: PivotTables, PivotCharts, slicers, timelines, Excel Tables.
