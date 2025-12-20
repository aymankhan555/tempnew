📊 E-commerce Funnel Analysis & Conversion Optimization

📄 Case Study Report (PDF):
👉 https://github.com/aymankhan555/Ecommerce_Funnel_Analysis/blob/main/Report_Slide/Funnel%20Analysis%20Case%20Study.pdf
📌 Project Overview

This project analyzes user behavior across an e-commerce purchase funnel to identify conversion bottlenecks, drop-off points, and revenue leakage. The analysis tracks how users move through the journey:

View → Add to Cart → Purchase

The project combines Python-based analysis, a business-focused case study report, and an interactive Power BI dashboard to translate data into actionable insights.

🧠 Business Context

The platform experiences high product views but relatively low purchase completion. Stakeholders want to understand:

Where users drop off in the funnel

Which products attract attention but fail to convert

How funnel performance changes over time

How much revenue is lost due to user drop-off

Goal: Identify conversion bottlenecks and revenue leakage points across the user journey and provide data-driven recommendations.

📂 Dataset Summary

Rows: 286,831

Columns: 10

Key Fields:
event_time, event_type, user_id, product_id, price, category, brand, user_session

Only relevant funnel events were used:

view

cart

purchase

Negative prices (refunds/reversals) were excluded from revenue calculations to reflect realized sales.

🔍 Key Funnel Metrics (From Dashboard)

Total Views: 358K

Add to Cart: 83K

Purchases: 26K

Overall Conversion (View → Purchase): 7.15%

Overall Funnel Drop-off: 92.85%

Step-wise Drop-off

View → Cart: 76.70%

Cart → Purchase: 69.31%

These metrics highlight significant friction at both the product persuasion and checkout stages.

🛍 Product-Level Insights

High visibility does not guarantee high conversion

Some products with fewer views outperform highly viewed products in conversion

Several products convert below 2%, indicating lost revenue opportunities

👥 User Behavior Insights

Repeat users: 74,120

Single-event users: 295,332

Most users interact only once, signaling weak retention and limited return engagement.

⏱ Time-Based Funnel Trends
Daily Funnel Trend

Stable funnel ratios across most days

Sharp decline during late December, likely due to seasonal or campaign effects

Recurring weekly patterns in traffic

Weekly Funnel Trend

Low baseline activity across most weeks

Massive spike during weeks 49–52 (holiday season)

Conversion efficiency remains stable despite traffic surges

This confirms strong seasonality in business performance.

💰 Revenue Impact

Average Purchase Price: $5.06

Actual Revenue: $129,476

Potential Revenue (Cart stage): $421,888

Revenue Lost After Cart Stage: $292,412

Revenue Lost After View Stage: $1.68M

A large share of revenue is lost due to funnel drop-offs.

📊 Dashboard

The Power BI dashboard includes:

Executive KPI cards (Users, Conversion %, Drop-off %, Revenue)

Funnel visualization (Views → Cart → Purchase)

Step-wise conversion & drop-off charts

Daily and weekly funnel trends

📸 Dashboard Preview:
(Image included in repository)

📄 Case Study Report

A business-focused PDF report summarizes:

Problem statement

Funnel findings

Product and time-based insights

Revenue impact

Strategic recommendations

📎 Report:
👉 https://github.com/aymankhan555/Ecommerce_Funnel_Analysis/blob/main/Report_Slide/Funnel%20Analysis%20Case%20Study.pdf

💡 Key Recommendations

Improve product pages for high-view, low-conversion items

Introduce trust badges and limited-time discounts

Simplify checkout flow

A/B test CTA placement and pricing presentation

Optimize product recommendations

Retarget cart abandoners via email or ads

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib)

Power BI

Funnel Analysis & Revenue Impact Modeling

🚀 Why This Project Stands Out

Business-first analytics approach

Clear funnel diagnostics

Revenue-focused insights

Strong storytelling for stakeholders

Resume-ready end-to-end analysis
