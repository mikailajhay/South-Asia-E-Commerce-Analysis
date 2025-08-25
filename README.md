## South Asia E-commerce Orders Analysis (100K Records)

## Overview
An exploratory analysis built in Google Colab using a public Kaggle dataset of 100,000 e-commerce order lines from a large South Asian retailer. The notebook focuses on order volumes, product demand, and shipping timelines. A simple, optional simulation adds unit prices to illustrate revenue-style charts.

## Dataset
- Source: Kaggle — “E-Commerce Dataset – South Asia (100K Records)”
- Columns:
  - `rec_id` — record identifier
  - `order_id` — customer order identifier
  - `order_date` — order creation timestamp
  - `shipped_at` — fulfillment/shipping timestamp
  - `prod_sku` — product SKU
  - `prod_qty` — quantity ordered

## What’s included
- KPI cards: total orders, total quantity, average shipping delay, and (optional) simulated revenue total
- Trends: monthly orders and simulated revenue
- Deep dives: top SKUs by quantity, shipping delay distribution
- Optional: platform/channel split (simulated) to demonstrate a basic dashboard view

## Key findings (from this run)
- Busiest month: March 2015 with 8,116 orders
- Top 5 SKUs by quantity:  
  ROON_24465_06th Oct_TV_2nd_Duplicate; 8.9014E+12; ROON_24478_30th Oct_TV_AD_4th_Duplicate; ROON_24494_13th_Nov_TV_AD; ROON_244322_14Aug
- Average shipping delay: 52.8 days

## Tech stack
Python, Pandas, Plotly, Google Colab
