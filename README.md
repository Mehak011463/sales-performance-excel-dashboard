# Sales Performance & Revenue Intelligence Dashboard | Microsoft Excel

An institutional-grade Microsoft Excel commercial analytics workbook designed to evaluate enterprise retail revenue, profitability dynamics, SKU-level margin leakage, and regional sales representative efficiency across 800+ transactions.

## Executive Summary
- **Enterprise Revenue**: $725,074.37 across 800 verified transactions.
- **Operating Profit**: $255,033.87 with a 35.17% composite margin.
- **Top Territories**: East ($219.2K) and West ($210.5K) capture 59.2% of market revenue.
- **Core Insights**: Identified category margin paradox (Furniture brings 41.5% of revenue at 31.0% margin; Office Supplies yields 40.3% margin) and Q4 seasonality surge (50.9% of annual sales in Oct-Dec).

## Architecture & Technical Features
1. **Raw Staging & Cleaning Audit**: 808 raw records preserving real-world data flaws (duplicates, irregular casing, null reps, text dates) cleaned and documented in a structured audit log.
2. **Dynamic Data Model**: Structured Excel Table (`SalesData`) utilizing `INDEX/MATCH` master catalog lookups, defensive `IFERROR` margin calculations, and helper date parsing.
3. **Multi-Criteria Summary Engine**: Analytical summary tables powered by `SUMIFS`, `COUNTIFS`, and dynamic parameter bridge logic.
4. **Interactive Executive Dashboard**: 6 KPI summary cards, custom Data Validation dropdown filters for Region & Category, and 5 synchronized visualizations built to fit a 1080p display.
5. **Strategic Intelligence Memo**: Data-validated findings with a 90-day C-suite implementation roadmap.
