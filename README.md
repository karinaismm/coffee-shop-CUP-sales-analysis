# Cup Café — Sales & Hourly Traffic Analysis (Dec 2025)

**Repository:** coffee-shop-CUP-sales-analysis  
**Summary:** An anonymized coffee shop sales and hourly traffic analysis (December 2025) built in Tableau Public, with insights and operational recommendations.

> **Note:** “Cup Café” is a fictional business name used for portfolio purposes.  
The dataset is anonymized and partially synthetic.

---

## Project Overview
This portfolio project analyzes coffee beverage sales performance and hourly customer traffic patterns for an anonymized coffee shop during **December 2025**.

The objective is to identify key revenue drivers, understand peak demand windows, and translate analytical findings into actionable operational recommendations related to staffing, preparation planning, and performance monitoring.

---

## Business Task
**How can Cup Café improve staffing and daily operations based on sales performance and customer traffic patterns?**

---

## Key Questions
- Which beverages generate the highest revenue and sales volume?
- What are the busiest and slowest days of the week?
- How do peak demand hours differ between weekdays and weekends?
- How can staffing and preparation be optimized around demand peaks?

---

## Data
**Source:** Excel workbook with two CSV exports used in Tableau.

- `sales_daily.csv` — daily beverage sales by date, product, and size (revenue and units)
- `hours_daily.csv` — estimated hourly transactions by day and hour (traffic model)

### Data Notes
- The dataset is fully anonymized and contains no real store identifiers.
- Includes a limited manually transcribed real sample (selected beverage lines) combined with a synthetic monthly dataset generated using documented assumptions.
- Intended solely for portfolio demonstration purposes.

---

## Data Preparation & Processing
- Standardized field names and data types (dates, measures, and dimensions)
- Ensured totals were not double-counted when size-level breakdowns were present
- Created Tableau calculated fields, including:
  - Day Type (Weekday / Weekend)
  - Hour formatting for time-series analysis
- Exported clean, analysis-ready CSV files for GitHub preview and Tableau connection

---

## Analysis & Dashboard
An interactive Tableau dashboard was developed, including:

- KPI cards: Units Sold, Total Revenue, Revenue per Unit, Transactions
- Daily Revenue trend for December 2025 with a reference average line
- Revenue by Product analysis highlighting top-performing beverages
- Day × Hour heatmap visualizing traffic intensity by weekday and hour
- Day Type filter enabling weekday versus weekend comparison

---

## Key Insights (December 2025)
- Latte is the top revenue-generating beverage.
- Customer demand peaks during the morning rush (8–10 AM).
- Weekdays outperform weekends in overall sales activity.
- Traffic declines after approximately 3 PM, indicating potential opportunities to optimize labor allocation.

---

## Modeling Assumptions (Hourly Traffic)
- Store operating hours: 7:00 AM – 7:00 PM
- Peak demand patterns:
  - Weekdays: 8–9 AM and a secondary lunch peak around 12:40–1:30 PM
  - Weekends: 10–11 AM
- Customer traffic decreases after 6:00 PM compared to the 3:00–5:00 PM period

---

## Recommendations
- **Staffing:** Increase coverage during weekday morning and lunch peaks; weekends from 10–11 AM.
- **Late afternoon / evening:** Reduce staffing or reassign labor to cleaning and preparation tasks after approximately 3–6 PM.
- **Inventory & preparation:** Prioritize high-revenue beverages (latte, iced latte, coffee) ahead of peak demand windows.
- **Next analytical step:** Collect 8–12 weeks of real POS data to validate seasonality and improve forecasting accuracy.

---

## Tools & Skills
- Tableau Public (dashboards, filters, calculated fields, formatting)
- Data cleaning and structuring (CSV, Excel)
- KPI reporting and trend analysis
- Product contribution and traffic pattern analysis
- Operational analytics and data-driven recommendations

---

## Deliverables
- Interactive Tableau dashboard
- Clean CSV datasets for review on GitHub
- Documentation, assumptions, and recommendations

---

## Links
**Live Tableau Dashboard:**  
https://public.tableau.com/views/coffeshop_17684340856430/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Repository Structure
data/
sales_daily.csv
hours_daily.csv
visuals/
dashboard.png
weekends.png
weekdays.png
README.md



## Disclaimer
- **Cup Café** is a fictional business name used for portfolio purposes only.
- The dataset is **anonymized** and does not include sensitive business identifiers.
- Results should be interpreted as a **portfolio demonstration** rather than an official financial report.
