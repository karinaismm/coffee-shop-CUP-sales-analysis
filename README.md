# coffee-shop-CUP-sales-analysis
Anonymized coffee shop sales &amp; hourly traffic analysis (Dec 2025) with insights and operational recommendations.

# Cup Café — Sales & Hourly Traffic Analysis (Dec 2025)

*Note: “Cup Café” is a fictional name used for portfolio purposes; the dataset is anonymized and partially synthetic.*

## Project Overview
This portfolio project analyzes coffee beverage sales and hourly traffic patterns for an anonymized coffee shop (“Cup Café”) during **December 2025**.  
The goal is to identify revenue drivers, understand peak demand hours, and provide operational recommendations (staffing, prep, and performance monitoring).

## Business Task (Ask)
**How can Cup Café improve staffing and daily operations based on sales performance and customer traffic patterns?**

### Key Questions
- Which beverages drive the most revenue and volume?
- What are the busiest days and the slowest day of the week?
- What are the peak hours on weekdays vs weekends?
- How can staffing and prep be optimized around demand peaks?

## Data (Prepare)
**Source:** An Excel workbook + two CSV exports used in Tableau.
- `sales_daily.csv` — daily beverage sales by date/product/size (revenue and units).
- `hours_daily.csv` — estimated hourly transactions for each day (traffic model).

### Data Notes
- The dataset is **anonymized** (no real store identifiers).
- The workbook includes a **limited real sample** manually transcribed from photos (selected beverage lines only), plus a **synthetic month dataset** generated using documented assumptions.

## Process (Cleaning & Setup)
- Standardized field names and data types (date, numeric measures).
- Ensured totals are not double-counted when size breakdowns exist.
- Created calculated fields in Tableau (e.g., **Day Type = Weekday/Weekend**, hour formatting for time-series charts).
- Exported clean analysis-ready tables as CSV for easy GitHub preview and Tableau connection.

## Analysis (What I Built)
I created a Tableau dashboard with:
- **Daily Revenue trend (Dec 2025)**  
- **Revenue by Product (Top beverages)**  
- **Revenue by Day of Week** (to highlight slow vs strong days)  
- **Hourly Traffic pattern** (weekday vs weekend peaks)

### Modeling Assumptions (Hourly Traffic)
- Store hours: **7:00 AM – 7:00 PM**
- Peak demand:
  - **Weekdays:** 08:00–09:00 and a second peak around **12:40–1:30 PM**
  - **Weekends:** 10:00–11:00
- After **6:00 PM**, customer traffic decreases compared to 3:00–5:00 PM.

## Key Insights (Example)
- A consistent **slow day** appears mid-week (Wednesday).
- Weekday demand peaks in the morning and during lunch hours.
- Weekend peak shifts later (10–11 AM).
- After 6 PM, traffic drops, suggesting opportunity to reduce staffing or shift tasks.

## Recommendations (Act)
1) **Staffing:** Increase coverage during peak windows (weekday mornings + lunch; weekends 10–11).  
2) **After 6 PM:** Reduce staffing or reassign to prep/cleaning tasks due to lower demand.  
3) **Inventory & prep:** Prioritize top revenue drinks (latte/iced latte/coffee) ahead of peak periods.  
4) **Next data step:** Collect longer real POS exports (8–12 weeks) to validate seasonality and improve forecasting.

## Deliverables
- Tableau dashboard (link below)
- Clean CSV datasets for review on GitHub
- Data dictionary and documentation

## Links
- **Tableau Dashboard:** https://public.tableau.com/views/coffeshop_17684340856430/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Repository Structure
data/
sales_daily.csv
hours_daily.csv
visuals/
dashboard.png
README.md



## Disclaimer
- **Cup Café** is a fictional business name used for portfolio purposes only.
- The dataset is **anonymized** and does not include sensitive business identifiers.
- Results should be interpreted as a **portfolio demonstration** rather than an official financial report.
