S – Situation

A major food-delivery platform faced a severe service crisis that disrupted customer experience, slowed operations, and reduced revenue.
The company had large, scattered datasets—orders, customers, delivery partners, ratings, cancellations, and financials—with no unified understanding of how the crisis impacted different parts of the business.
I was responsible for conducting a full-funnel analysis to uncover the root causes, quantify the business impact, and highlight changes in customer behavior.

T – Task

My goals were to:

Ingest and clean all datasets into a unified structure

Compare pre-crisis vs crisis periods across operations, customers, finance, and sentiment

Identify which operational failures contributed most to cancellations

Analyze customer segments, geographic shifts, and order patterns

Perform hypothesis testing (t-tests) to statistically validate operational assumptions

Deliver clear, actionable insights the business could use to improve service recovery

A – Action
1. Built a clean, integrated data model

Ingested datasets from orders, customers, partners, reviews, and finance

Cleaned inconsistent columns and engineered crisis/pre-crisis labels

Created a unified analysis-ready dataset across 9 notebooks

2. Conducted deep Exploratory Data Analysis

Analyzed daily and hourly revenue, order frequency, and order value shifts

Compared customer behavior across segments, cities, and order types

Identified major drops in new user sign-ups and changes in demand patterns during the crisis

3. Operational Breakdown — identifying the root cause

Mapped delivery delays across cities and delivery partners

Found multiple cities experiencing severe delay spikes

Measured the impact of delays on cancellations

Ran a two-sample t-test to statistically confirm:
Orders delayed >20 minutes had significantly higher cancellation rates compared to orders delayed <20 minutes.
This proved delays were the primary driver of crisis-era customer churn.

4. Cancellation Analysis

Segmented cancellations by customer type, payment method, and geography

COD customers and new users had the highest cancellation increases

City-specific patterns revealed where service breakdowns were worst

5. Sentiment & Rating Analysis

Extracted review sentiment

Found a steep decline in customer sentiment during the crisis

Regression showed ratings only weakly explained customer satisfaction → indicating multiple underlying issues beyond food quality

Delivery delays and app experience were major pain points

6. Financial & Revenue Impact Analysis

Analyzed discounting behavior, delivery fees, and restaurant earnings

Found sharp declines in:

Restaurant subtotal revenue

Delivery fee income

High-value orders

Customers shifted toward mid-priced meals and reduced discretionary spending

R – Result

The analysis delivered a clear narrative of the crisis across the entire business:

Delays were statistically proven to be the biggest driver of cancellations
→ Confirmed through t-tests and operational analysis

Customer sentiment and trust deteriorated significantly

Order volume, average order value, and revenue fell sharply

Geographic hotspots of operational failure were identified

High-risk customer segments and payment methods were mapped

The insights provided leadership with a full crisis blueprint, enabling targeted recovery strategies across operations, customer experience, and marketing

This project demonstrated my ability to handle complex multi-source data, conduct deep EDA, apply hypothesis testing, and deliver story-driven business insights that directly support decision-making.
