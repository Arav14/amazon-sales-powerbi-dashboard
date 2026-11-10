# Amazon Sales Report Dashboard (Power BI)

Interactive Power BI dashboard analyzing 20,000 Amazon India sales orders
(INR 1.16 Cr in sales) across 9 product categories.

![Dashboard](screenshots/dashboard.png)

## Tools
Power BI Desktop, Power Query, Microsoft Excel

## Data
`Amazon-Sales-Report-20K-Rows.xlsx`: 20,000 orders with date, status,
fulfilment, category, size, courier status, quantity, amount and ship location.

## What I did
- Loaded the Excel data and cleaned it in Power Query (promoted headers, fixed data types)
- Built a total-sales KPI card and a date slicer
- Built charts for orders by category, size, ship-state, fulfilment type,
  delivery partner and courier status

## Key insights
- T-shirts and Shirts make up 81% of all orders
- 85% of orders reached "Shipped" status
- Amazon fulfils 63% of orders; merchants fulfil 36%
- Maharashtra, Karnataka, Telangana and Uttar Pradesh are the top states by orders

## How to use
Download the `.pbix` file and open it in Power BI Desktop.
