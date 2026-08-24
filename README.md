# Coffee-Shop-Sales-Analysis
**Case Study 1** · Junior Data Analyst Project · 2026

## Overview

Bright Coffee Shop has appointed a new CEO focused on growing revenue and improving product performance. This project analyzes six months of transactional sales data to uncover actionable insights and deliver data-driven recommendations to support the CEO's decision-making.

## Business Questions

This analysis answers four core questions:

1. Which products generate the most revenue?
2. What time of day does the store perform best?
3. What are the sales trends across products and time intervals?
4. What recommendations can improve sales performance?

## Data Source

- **Records:** 64,065 transactions
- **Period:** January – June
- **Locations:** 3 New York stores (Hell's Kitchen, Astoria, Lower Manhattan)
- **Categories:** 9 product categories, 80 individual products
- **Total revenue represented:** $698,812.33

## Tools Used

| Stage | Tool |
|---|---|
| Planning & architecture | Miro |
| Data processing & transformation | Databricks, SQL |
| Data analysis & visualization | Microsoft Excel |
| Reporting & presentation | Microsoft PowerPoint |

## Repository Structure

├── README.md
├── data/
│   └── Coffeesales_Workshop.csv        # Cleaned source dataset
├── architecture/
│   └── data_flow_diagram.png           # Miro pipeline diagram
├── databricks/
│   └── data_processing_notebook        # Data cleaning + SQL aggregation
├── excel/
│   └── Coffeesales_Analysis.xlsx       # Dashboard & pivot analysis
└── presentation/
    └── CEO_Presentation.pptx           # Final PowerPoint deck
    
## Methodology Summary

1. **Planning (Miro):** Mapped the data flow from source → ETL pipeline → Databricks storage → analysis → presentation, and outlined the key insights and calculations required.
2. **Processing (Databricks/SQL):** Loaded the raw CSV, cleaned pricing formats, computed `total_amount = unit_price × transaction_qty`, and grouped transactions into time-of-day buckets.
3. **Analysis (Excel):** Built pivot tables and charts covering revenue by category, time of day, store location, and best/worst-selling products.
4. **Presentation (PowerPoint):** Summarized key insights and translated them into recommendations for the CEO.

## Key Insights

- **Coffee and Tea drive 66.7% of total revenue** - Coffee alone contributes 38.6% ($269,952), followed by Tea at 28.1% ($196,406). The bottom four categories combined contribute under 5%.
- **Morning generates 55.6% of all revenue** ($388,289) — more than Afternoon, Evening, and Night combined. Night trades at just 0.4% ($2,936).
- **Morning dependence varies by store** - Lower Manhattan (62.6%) and Hell's Kitchen (59.0%) are far more Morning-reliant than Astoria (45.2%), which sees comparatively strong Afternoon trade.
- **Revenue nearly doubled over the period** - up 103.8%, from $81,678 in January to $166,486 in June, with the steepest jump (+31.8%) between April and May.
- **All three store locations perform within 3% of each other** - Hell's Kitchen leads at $236,511, ahead of Astoria ($232,244) and Lower Manhattan ($230,057), indicating consistent performance rather than one underperforming location.

## Recommendations

1. **Run targeted promotions during Evening and Night** - these slots combine for only 15.1% of revenue, offering low-risk upside.
2. **Protect and prioritize top performers** - ensure inventory, staffing, and shelf space are optimized around Coffee, Tea, and the Morning rush.
3. **Promote or bundle underperforming products** - feature low-revenue categories (Branded, Loose Tea, Flavours, Packaged Chocolate) alongside best-sellers.
4. **Investigate the April–May growth driver** - understanding this spike could allow the business to deliberately replicate it during slower months (Jan–Mar).

## Author

Prepared by **Buhlebenkosi Hlengiwe Mnisi** aspiring Data Analysis/Scientist 
