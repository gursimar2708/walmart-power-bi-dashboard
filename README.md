# Walmart Market Business Intelligence Dashboard | Power BI

## Project Overview

This project presents an interactive Business Intelligence dashboard
developed in Power BI to analyze Walmart's market performance across
the United States, Mexico, and Canada.

The dashboard focuses on three key areas of retail performance:
transaction volume, profitability, and returns. It also analyzes
product brand performance, geographic performance, weekly revenue
trends, and revenue against targets.

The goal of the analysis was to turn transaction-level retail data
into a management-level view that could help identify areas of strong
performance, potential operational issues, and markets requiring
attention.

---

## 🎥 Interactive Dashboard Demo

> Click below to watch the Power BI dashboard in action.

[▶️ Watch the Power BI Dashboard Demo](https://drive.google.com/file/d/1vim-Q42ZYkQLpwR1KJAb9LsrJbKThDm8/view?usp=sharing)

---

## Business Problem

Walmart operates across multiple countries, stores, cities, and
product brands, creating a large volume of transactional data.

Looking at individual transactions does not provide management with
an immediate view of whether the business is meeting its targets,
which products are driving revenue, where transactions are concentrated,
or whether increasing sales are accompanied by increasing returns.

The business therefore needs a centralized dashboard that can answer:

- Are current-month transactions and profit meeting targets?
- How does current-month performance compare with the previous month?
- Which product brands contribute the most revenue?
- Which countries, states, and cities generate the highest transaction
  volumes?
- How is revenue changing over time?
- Are returns increasing alongside sales?
- Which markets require additional attention?
- Where are there opportunities to improve revenue and profitability?

---

## Project Objectives

The dashboard was designed to:

1. Monitor total transactions, profit, returns, and revenue performance.
2. Compare current-month performance against previous-month benchmarks
   and targets.
3. Identify high-performing product brands.
4. Analyze geographic performance from country to city level.
5. Track weekly revenue trends.
6. Monitor return-rate patterns alongside sales performance.
7. Present the findings through an interactive executive-style dashboard.

---

## Dashboard Solution

The Power BI dashboard combines multiple analytical views into a
single interactive reporting interface.

### 1. KPI Performance Monitoring

The dashboard provides KPI cards for current-month transactions,
profit, and returns.

The current dashboard shows:

| KPI | Current Month | Target | Variance |
|---|---:|---:|---:|
| Transactions | 18,325 | 17,339 | +986 / +5.69% |
| Profit | $71,682 | $67,872 | +$3,810 / +5.61% |
| Returns | 496 | 482 | +14 / +2.90% |

Transactions exceeded the target by 986, representing a 5.69% positive
variance.

Profit exceeded the target by $3,810, representing a 5.61% positive
variance.

Returns were 14 above the target level, representing a 2.90% variance.
Because lower returns are preferable, this metric requires attention
even though transaction and profit targets were exceeded.

---

## 2. Product Brand Performance

A matrix visual was used to compare product brands using:

- Total Transactions
- Total Profit
- Profit Margin
- Return Rate

Conditional formatting was applied to make differences easier to
identify.

The analysis highlighted that the **top 10 product brands contributed
approximately 25% of overall revenue** while also exceeding the
revenue target.

This indicates that a relatively small group of brands is responsible
for a significant share of revenue generation.

### Business Implication

High-performing brands can be monitored closely for inventory
availability, pricing, promotions, and customer demand because changes
in these brands could have a noticeable effect on overall revenue.

---

## 3. Geographic Performance

The dashboard includes geographic analysis across:

**Country → State → City**

The interactive map allows transaction performance to be explored at
store-city level, while the treemap provides a hierarchical view of
market performance.

The analysis identified **Portland as a high-performing city, reaching
1,000+ sales in December**.

The dashboard also highlighted stronger month-over-month performance
in the **Mexico market**, with both profit and revenue performing well
compared with the previous month.

### Business Implication

Geographic performance can be used to identify locations with strong
customer activity and markets where additional investigation may be
required.

---

## 4. Revenue Trend Analysis

A weekly revenue column chart was used to examine revenue movement
through the year.

The analysis is filtered to the **1998 data** to provide a consistent
time-series view of weekly revenue performance.

This allows changes in weekly sales activity to be observed rather than
relying only on monthly or annual totals.

---

## 5. Revenue vs Target

A gauge visual compares the latest revenue performance against the
target.

The dashboard displays approximately **$120K in current revenue**,
with the gauge showing the latest period relative to the target level.

This provides management with a quick view of whether current
performance is tracking close to the expected revenue level.

---

# Key Insights

### 1. Transactions exceeded the target by 5.69%

Current-month transactions reached **18,325**, compared with a target
of **17,339**.

That represents:

**+986 transactions | +5.69% above target**

This indicates stronger-than-target transaction activity during the
current month.

---

### 2. Profit exceeded the target by 5.61%

Current-month profit reached **$71,682**, compared with a target of
**$67,872**.

That represents:

**+$3,810 | +5.61% above target**

The increase in profit alongside higher transaction volume indicates
that the current month generated stronger financial performance than
the target benchmark.

---

### 3. Returns were above the target by 2.90%

The dashboard records **496 returns** against a target of **482**.

That is:

**+14 returns | +2.90% above target**

This is an important counter-signal to the positive sales and profit
performance.

Higher transaction activity is positive, but the increase in returns
suggests that product quality, fulfillment, customer experience, or
other return-related factors should be investigated.

---

### 4. Top 10 brands generated approximately 25% of revenue

The analysis found that the **top 10 product brands account for around
one-quarter of total revenue**.

This indicates meaningful revenue concentration among the highest-
performing brands.

These brands represent an important area for inventory planning,
promotion, and performance monitoring.

---

### 5. Portland exceeded 1,000 sales in December

Portland was identified as a high-performing city, reaching **1,000+
sales in December**.

This provides a location-level example of where transaction activity
was particularly strong.

---

### 6. Mexico showed stronger month-over-month performance

The dashboard identified Mexico as a market showing stronger
performance compared with the previous month in both **revenue and
profit**.

The result suggests that Mexico's performance should be monitored
closely to understand which products, stores, or customer segments are
contributing to the improvement.

---

# Business Recommendations

Based on the dashboard findings, the following actions can be
considered:

### 1. Investigate the increase in returns

Returns were **2.90% above the target**, despite transactions and
profit exceeding their targets.

The next analysis should break returns down by:

- Product brand
- Product category
- Store
- City
- Country
- Return reason

This could help determine whether the increase is concentrated in
specific products or locations.

---

### 2. Protect the performance of top revenue-generating brands

Since the top 10 brands contribute approximately **25% of total
revenue**, Walmart should closely monitor their:

- Inventory availability
- Sales trends
- Profit margins
- Return rates
- Promotional performance

Maintaining availability for high-performing brands can help protect
their contribution to overall revenue.

---

### 3. Investigate the drivers behind Mexico's improvement

Mexico showed stronger revenue and profit performance compared with the
previous month.

A deeper analysis should examine whether the improvement is associated
with specific:

- Products
- Brands
- Stores
- Cities
- Customer segments
- Promotional activities

This would help determine whether the improvement is temporary or
part of a sustained trend.

---

### 4. Study high-performing locations

Portland exceeded **1,000 sales in December**, making it useful as a
benchmark for understanding strong store-level performance.

The business could compare high-performing locations with lower-
performing locations to identify differences in product mix, demand,
pricing, and customer activity.

---

# Technical Implementation

## Data Model

The Power BI model connects multiple business tables, including:

- Transaction_Data
- Products
- Customers
- Stores
- Regions
- Calendar
- Return_Data

The model was structured to allow transaction, product, geographic,
calendar, and return information to be analyzed together.

---

## Power BI Features Used

- DAX measures
- Data modelling
- Power Query
- KPI cards
- Matrix visual
- Conditional formatting
- Geographic map
- Treemap
- Gauge chart
- Weekly revenue trend
- Drill-down
- Slicers
- Bookmarks
- Interactive filtering
- Page navigation
- Visual interactions

---

## DAX

DAX measures were used to calculate and compare key business metrics
such as transactions, profit, returns, revenue, profit margin, targets,
and period-based performance.

Examples of analytical calculations include:

- Total Transactions
- Total Profit
- Total Returns
- Profit Margin
- Return Rate
- Current Month vs Previous Month
- Revenue vs Target

---

# Dashboard Pages

### Topline Performance

The main dashboard provides an executive-level overview of:

- Current-month transactions
- Current-month profit
- Current-month returns
- Product brand performance
- Geographic performance
- Weekly revenue
- Revenue vs target

### Market Report & Insights

A dedicated insights page summarizes important findings from the
analysis, including Portland's December performance, the contribution
of the top 10 brands, changes in returns, and Mexico's month-over-month
performance.

---

# Skills Demonstrated

**Business Intelligence**
- KPI development
- Business problem identification
- Performance monitoring
- Business insights
- Recommendation development

**Power BI**
- Dashboard development
- Data modelling
- Interactive visualizations
- Drill-down analysis
- Slicers and bookmarks

**DAX**
- Measure creation
- KPI calculations
- Target comparisons
- Period-based analysis

**Data Analysis**
- Trend analysis
- Geographic analysis
- Product performance analysis
- Return analysis
- Comparative analysis

---

# Project Outcome

The dashboard converts Walmart's transactional data into an
interactive management reporting solution.

The analysis showed that current-month transactions were **5.69% above
target** and profit was **5.61% above target**, while returns were
**2.90% above the target level**.

The dashboard also identified approximately **25% of revenue coming
from the top 10 product brands**, **1,000+ December sales in Portland**,
and stronger month-over-month revenue and profit performance in Mexico.

Together, these findings provide a starting point for monitoring
revenue performance, protecting high-performing brands, investigating
return-related issues, and understanding differences between markets
and locations.

---

# Project Files

- `Walmart Market Report.pbix` — Power BI dashboard
- `walmart power bi dashboard.pdf` — Project documentation
- `Dashboard 1.jpg` — Main dashboard
- `Dashboard 2.jpg` — Interactive dashboard view
- `Dashboard 3.jpg` — Insights view
- `Dashboard 4.jpg` — Data model
- `Power BI project.mp4` — Dashboard demonstration

---

# Dashboard Preview

![Dashboard Overview](Dashboard%201.jpg)

![Interactive Dashboard](Dashboard%202.jpg)

![Market Insights](Dashboard%203.jpg)

![Data Model](Dashboard%204.jpg)

---
