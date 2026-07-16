# Sales Executive Performance Dashboard (Excel)

An interactive Excel dashboard that tracks daily sales performance for 140 sales
executives across 8 regions in India, and shows how each person is doing
against their sales target.


## Objective

The sales team records daily sales for each executive over a 5-day period.
This project turns that raw data into a dashboard that instantly shows:

- Who the top-performing sales executives are
- Who is falling behind their target
- How close (or far) each executive is from hitting their target
- A view that can be filtered/sliced by region

## Dataset

- **Rows:** 140 sales executives
- **Regions covered:** Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi, Surat
- **Columns:** Employee Code, Sales Executive Name, Region, Daily Sales (Day 1–Day 5),
  Total Sales, Target, Target Hit %, Away From Target %
- **Target per executive:** 500 units

## What the Dashboard Shows

1. **Top Sales Executives by Total Sales** — bar chart ranking
2. **Sales Executives Furthest From Target** — highlights who needs support
3. **Target Hit % by Executive** — donut/pie view of achievement rate
4. **Away From Target % by Executive** — shows the performance gap
5. **Slicer filter** — lets you filter results interactively (by region/executive)

## Tools Used

- Microsoft Excel
- Pivot Tables
- Excel Charts (bar chart, donut chart)
- Slicers (interactive filtering)
- Formulas: SUM, percentage calculations for Target Hit % and Away From Target %

## Key Insights

- Key Insights
- Built an interactive Excel dashboard using Pivot Tables, Pivot Charts, Slicers, and KPIs.
- The dashboard enables dynamic analysis of sales performance across multiple cities.
- Identifies top and bottom-performing sales executives based on total sales.
- Tracks target achievement percentage for each sales executive.
- Highlights the remaining percentage required to achieve assigned sales targets.
- Provides visual analysis using bar, pie, and line charts for quick decision-making.
- Interactive slicers allow users to filter data by city and instantly update all dashboard components.
## File Structure

```
├── data/
│   └── Product_Sales_Analysis.xlsm     # Full workbook (raw data + dashboard)
├── screenshots/
│   └── dashboard_overview.png          # Dashboard preview image
└── README.md
```

## How to Use

1. Download `Product_Sales_Analysis.xlsm` from the `data` folder.
2. Open it in Microsoft Excel (macros/slicers work best in Excel, not Google Sheets).
3. Go to the **Dashboard** tab to view the interactive charts.
4. Use the slicer to filter results by region or executive.
5. The **Raw Data** tab contains the full underlying dataset.

## About This Project

This project was built as part of my data analytics portfolio to practice
turning raw, messy sales data into a clear, decision-ready dashboard using
pivot tables and Excel formulas.

---
**Author:** Noman Mustafa
**Connect:** [LinkedIn](https://linkedin.com/in/noman-mustafa-a8a61b419) | [GitHub](https://github.com/Zaib425)
