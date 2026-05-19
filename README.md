# E-commerce Performance & Marketing Analytics Dashboard (Power BI)

## Executive Summary

This project analyzes the performance of an e-commerce business between March 2012 and March 2015. The objective is to move beyond descriptive reporting and build a decision-oriented analytics system combining revenue performance, customer behavior, product dynamics, and marketing efficiency.

The dashboard was designed to support both strategic and operational decision-making by enabling stakeholders to understand not only what happened, but why it happened and where optimization opportunities exist.

---

## Business Context

The company operates an online retail business with multiple product categories and relies heavily on digital acquisition channels such as search and paid advertising.

Over time, the business faced three core challenges:
- Understanding revenue growth drivers across time
- Reducing dependency on a single best-selling product
- Improving marketing efficiency and attribution clarity

This project was designed to address these challenges through a structured analytical framework.

---

## Analytical Approach

The project follows a full end-to-end analytics workflow:

1. Data modeling and database validation in PostgreSQL (pgAdmin4)
2. Data cleaning and transformation in Power Query
3. Star schema design with a dedicated date table
4. KPI definition and DAX measure development
5. Creation of three interconnected analytical dashboards
6. Simulation of marketing costs to enable profitability analysis (ROAS, CPA)

Additional business assumptions were introduced to enrich the dataset, including marketing cost structures and performance targets.

---

## Analytical Hypotheses

Prior to building the dashboards, several hypotheses were defined:

- Revenue peaks in 2014 compared to other years
- Customers predominantly purchase single-item baskets
- Refund rates decrease over time, reflecting improved product quality or targeting
- The top product ("The Original Mr. Fuzzy") drives a disproportionate share of revenue
- Google search is the primary acquisition channel
- Mobile usage exceeds desktop usage
- Certain ad creatives significantly outperform others in conversion efficiency

These hypotheses guided the structure of the analysis and were validated or challenged through the dashboards.

---

## Dashboard Structure

### Yearly Overview

This view provides a strategic perspective on business performance across years. It focuses on long-term trends in revenue, product mix, and acquisition channels.

Key metrics include:
- Total Turnover and Revenue
- Orders and Quantity
- Average Basket Value
- Conversion Rate
- Refund Rate

Supporting visuals include monthly trends, product revenue distribution, traffic source breakdown, and annual target tracking.

This page is designed for high-level strategic assessment and performance benchmarking.

---

### Monthly Review

This dashboard focuses on operational performance and month-over-month evolution.

It enables granular monitoring of:
- Turnover and Orders
- AOV and Conversion Rate
- Refund Rate dynamics

Key analyses include:
- Daily performance trends and volatility
- Cumulative performance vs previous month
- Revenue contribution by traffic source
- Product ranking by revenue
- Weekday performance patterns

This view is primarily used for recurring business reviews and performance monitoring.

---

### Marketing Analysis

This page evaluates acquisition and campaign performance with a focus on efficiency and return on investment.

It includes:
- Orders, Conversion Rate, AOV
- ROAS and CPA metrics
- Creative-level performance analysis
- Channel-level conversion efficiency
- Device-based traffic and conversion distribution

A key component of this analysis is a scatter plot mapping ad creatives by:
- Revenue (X-axis)
- Orders (Y-axis)
- Traffic volume (bubble size)

This enables identification of high-performing and inefficient marketing assets.

---

## Key Business Insights

The analysis reveals several important business dynamics:

- The company achieved total revenue of approximately 1.85M, with a significant acceleration in 2014, marking a clear scaling phase.
- Conversion rate improved from 4.14% to 8.44%, indicating strong gains in acquisition efficiency and/or user experience.
- Refund rates decreased consistently from 7.39% to 3.31%, reflecting improved product quality or better targeting.
- Revenue remains highly concentrated in a single product, although dependency has decreased over time (from 77.3% to 48%).
- 61% of orders consist of single-product baskets, indicating limited cross-selling behavior.
- Strong seasonality is observed, with Q4 (October–December) representing the highest-performing period.
- Google search and branded traffic remain the dominant acquisition channels.
- “Unknown traffic” shows unexpectedly high conversion rates, suggesting potential tracking limitations or untapped acquisition value.
- Marketing performance is highly driven by a small number of effective creatives, particularly g_ad_1 and b_ad_1.

---

## Strategic Interpretation

From a business perspective, the company transitions through three phases:

1. Initial concentration phase driven by a single dominant product
2. Growth and scaling phase with strong revenue acceleration and traffic expansion
3. Optimization phase characterized by improved conversion efficiency, reduced refunds, and better marketing performance

Despite strong growth, the analysis highlights several optimization opportunities:
- Better attribution of unknown traffic sources
- Improved mobile experience optimization
- Expansion of cross-selling strategies to increase basket size
- Scaling of high-performing ad creatives while reducing inefficient campaigns

---

## Limitations

- A portion of traffic is classified as unknown due to tracking constraints
- Marketing costs and campaign performance metrics are based on simulated data
- Attribution is based on available session-level tracking and does not reflect full customer journey complexity

---

## Conclusion

This project demonstrates how raw transactional and behavioral data can be transformed into a structured decision-making system.

Beyond reporting historical performance, the dashboard enables:
- Identification of growth drivers
- Evaluation of marketing efficiency
- Understanding of customer and product behavior
- Support for strategic decision-making in e-commerce contexts
