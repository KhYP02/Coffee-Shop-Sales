# Coffee Shop Sales Analysis (Excel)

An Excel dashboard on six months of sales from a three-store coffee shop chain in New York. I wanted to find out when the shops are busiest, what actually drives revenue, and whether the three locations behave differently.

**Data:** 149,116 transactions, Jan to Jun 2023, across Astoria, Hell's Kitchen and Lower Manhattan.
**Tool:** Microsoft Excel (PivotTables, slicers, charts, data model measures).

## What I built

- Cleaned and extended the raw transaction data with helper columns: month, day name, day of week and hour of day.
- Built **12 PivotTables** covering revenue by month, store, product category and product type, transactions by hour and weekday, and size split.
- Created measures for **footfall** (transaction count), **average bill** and **average order size**.
- Put it together in a **6-chart dashboard** with slicers so any view can be filtered by store or month.

## Key findings

- **Revenue more than doubled** from January (81.7K) to June (166.5K), with growth every single month.
- **Mornings carry the business:** 7 to 10 AM accounts for about 45% of all transactions, with 10 AM the busiest hour.
- **Coffee and tea make up about 67% of revenue** (Coffee 270K, Tea 196K), with Bakery a distant third at 82K.
- **Top products by revenue:** Barista Espresso (91K), Brewed Chai tea (77K), Hot chocolate (72K) and Gourmet brewed coffee (70K).
- **The three stores are nearly identical** (about 230K to 237K each), so location is not the lever. Timing and product mix are.
- **Weekdays are flat** (roughly 20.5K to 21.7K transactions per day), so there is no real weekend effect.
- Average bill is about 4.69 per transaction, with about 1.4 items per order.

## Files

| File | What it is |
|---|---|
| `Coffee_Shop_Sales.xlsx` | The workbook with data, pivots and dashboard |
| `Coffee Shop Sales Analysis.pdf` | PDF export of the analysis |
| `Screenshot 2025-07-15 205129.png` | Dashboard preview |

## Author

Kharanshu Papolli, IIT (ISM) Dhanbad
[LinkedIn](https://www.linkedin.com/in/kharanshuyp)
