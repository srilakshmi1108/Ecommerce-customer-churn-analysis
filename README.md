# E-Commerce Customer Churn Analysis

## Overview
Analyzed 100,000+ real orders from Olist, a Brazilian e-commerce platform, 
to identify customers at risk of churning using RFM segmentation.
Built an interactive Tableau dashboard to visualize customer segments and revenue impact.

## Key Findings
- 41% of customers (38,343) are At Risk of churning
- At Risk segment represents R$6M in revenue at risk
- Most customers bought only once — showing high one-time buyer rate
- Champions spend 3x more than average customers (R$480 vs R$158)
- November 2017 Black Friday spike showed 50% revenue surge

## Tools Used
- Python (Pandas, Matplotlib) — data cleaning, EDA, RFM analysis
- SQL — data querying and aggregation
- Tableau Public — interactive dashboard
- Google Colab — development environment

## Dashboard
[View Live Tableau Dashboard](https://public.tableau.com/app/profile/bushireddy.srilakshmi2239/viz/EcommerceCustomerChurnAnalysis_17742494358120/E-CommerceCustomerChurn?publish=yes)
## Project Structure
- `ecommerce_churn_analysis.ipynb` — Python notebook with full analysis
- `rfm_segments.csv` — RFM scored customer data
- `distribution_plots.png` — Price, freight and payment distributions
- `monthly_revenue.png` — Monthly revenue trend
- `category_revenue.png` — Top 10 product categories
- `rfm_segments.png` — Customer segment visualization

## RFM Segments
| Segment | Customers | Avg Spend | Total Revenue |
|---|---|---|---|
| Loyal Customers | 31,582 | R$279 | R$8.8M |
| At Risk | 38,343 | R$158 | R$6.06M |
| Champions | 7,975 | R$480 | R$3.8M |
| Hibernating | 12,295 | R$72 | R$887K |
| Lost | 3,140 | R$48 | R$150K |

## Business Recommendations
1. Target At Risk customers with discount campaigns to recover R$6M revenue
2. Reward Champions with loyalty program to maintain R$3.8M revenue
3. Re-engage Hibernating customers with win-back email campaigns
