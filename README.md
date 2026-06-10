# Alfido Tech Website Traffic Analysis — User Journey, Bounce Rate & Conversion Insights

**InterSpark Internship - Task 3**

---

## Goal
Analyze website traffic logs to understand user journeys, top landing pages, bounce rates, and referral sources.

## Dataset
- 226,278 traffic events
- 3,839 unique landing page links
- Date range: August 19-25, 2021 (7 days)
- 3 event types: pageview, click, preview
- Top countries: Saudi Arabia, India, United States

## What I Did
- Parsed and cleaned raw traffic log data
- Computed key metrics: sessions, CTR, bounce rate, preview rate
- Visualized user flows and top entry/exit pages
- Recommended 5 optimizations to improve conversions for Alfido Tech

## Key Metrics

| Metric | Value |
|---|---|
| Total Events | 226,278 |
| Total Pageviews | 142,015 |
| Total Clicks | 55,732 |
| Total Previews | 28,531 |
| Unique Links | 3,839 |
| Click-through Rate | 39.2% |
| Preview Rate | 20.1% |

## Key Findings
- Saudi Arabia and India are the top traffic sources
- Tesher dominates with 40,841 events — 4x the next artist
- Clear peak traffic hours identified for campaign timing
- User journey: pageview to preview to click funnel mapped

## Visualizations
1. Daily Traffic Trend
2. Event Type Breakdown
3. Top 10 Countries by Traffic
4. Top 10 Artists by Traffic
5. Hourly Traffic Heatmap
6. User Flow Funnel
7. Top 10 Landing Pages

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- FPDF2
- Google Colab

## Files
- `Alfido_Tech_Traffic_Analysis.ipynb` - Full notebook with code and visualizations
- `alfido_tech_traffic_report.pdf` - PDF report with findings and recommendations

## How to Run
1. Open `Alfido_Tech_Traffic_Analysis.ipynb` in Google Colab
2. Upload the traffic.csv dataset
3. Run all cells in order

---
*Project completed as part of InterSpark Data Analysis Internship*
