# Financial Portfolio Data Analysis — Detailed Insights Report

## Project Overview

This project performs an end-to-end analysis of investment portfolio data to understand portfolio performance, customer demographics, asset allocation, transaction behavior, and risk dynamics.

The analysis integrates multiple datasets including:

* Portfolio details
* Investments
* Transactions
* Performance history
* Customer demographics

The objective is to generate actionable insights that can help portfolio managers, financial advisors, and investment firms make data-driven decisions.

---

## Dataset Summary

| Dataset               | Records |
| --------------------- | ------- |
| Portfolios            | 200     |
| Investments           | 1,000   |
| Transactions          | 3,000   |
| Performance snapshots | 5,000   |
| Customers             | 500     |

There are **482 unique customers actively holding portfolios**, indicating some customers manage multiple portfolios.

---

## Key Business Questions Addressed

* How portfolios are distributed by risk and value
* Customer demographics and investment behavior
* Asset allocation trends
* Profitability and performance vs benchmark
* Transaction patterns
* Impact of cash flows on returns
* Diversification effects
* Investor segmentation signals

---

## Executive Insights

### 🟢 1. Risk Distribution

* High risk portfolios: **79**
* Medium risk portfolios: **63**
* Low risk portfolios: **58**

High-risk portfolios form the largest group.

#### Total Value by Risk

* High risk: **~$18.1M**
* Medium risk: **~$15.4M**
* Low risk: **~$14.4M**

✅ Capital is heavily concentrated in higher risk strategies.

---

### 🟢 2. Customer Demographics

* Average age: **46.7 years**
* Average income: **287k**

#### Portfolio Value by Age Group

* 20–30: ~$8.5M
* 30–40: ~$10.5M
* 40+: ~$34.2M

✅ Older investors control the majority of invested capital.

---

### 🟢 3. High-Risk Investor Profile

Average income of high-risk investors:

~281k

✅ Higher income correlates with higher risk tolerance.

---

### 🟢 4. Asset Allocation Trends

#### Investment Counts

* Mutual Funds: 267
* Bonds: 257
* Stocks: 241
* Real Estate: 235

#### Market Value by Asset

* Mutual Funds: ~$41.6M
* Bonds: ~$40.4M
* Stocks: ~$36.9M
* Real Estate: ~$36.5M

✅ Mutual funds dominate allocation — suggesting preference for diversification.

---

### 🟢 5. Portfolio Profitability

Aggregated purchase vs market values show overall positive gains across portfolios, indicating favorable market conditions or effective allocation.

Top portfolios reach values close to **$500k**.

---

### 🟢 6. Transaction Behavior

| Type     | Count | Total Value |
| -------- | ----- | ----------- |
| Buy      | 1,035 | ~$27.7M     |
| Dividend | 985   | ~$25.6M     |
| Sell     | 980   | ~$25.8M     |

✅ Buy activity slightly dominates — suggesting net accumulation.

---

### 🟢 7. Benchmark Performance

Portfolios outperform benchmark roughly:

**49.6% of the time**

Indicates mixed performance — not consistently beating markets.

---

### 🟢 8. Volatility Insights

Some portfolios exhibit very high return standard deviation (>10%), suggesting aggressive trading or concentrated exposure.

High volatility portfolios may require risk monitoring.

---

### 🟢 9. Net Inflows vs Returns

Correlation between inflows and returns:

~0 (−0.009)

No meaningful relationship detected.

Interpretation:

* Adding money doesn’t guarantee higher returns.
* Performance depends more on asset selection.

---

### 🟢 10. Diversification Effect

Correlation between number of asset types and returns:

 ~0

Diversification stabilizes risk but doesn’t strongly boost returns.

---

## Behavioral Insights

### Investor Patterns Observed

* Wealthier clients take higher risks
* Older investors hold larger portfolios
* Mutual funds preferred for stability
* Active trading present but not excessive
* Performance dispersion indicates varied strategies

---

## Business Implications

### For Portfolio Managers

* Focus on improving alpha generation
* Monitor high volatility portfolios
* Provide tailored strategies by age segment

### For Advisors

* Encourage goal-based investing
* Educate clients on risk vs reward

### For Firms

* Segment clients by behavior
* Improve benchmark beating strategies

---

## Risks Identified

* High volatility clusters
* Inconsistent benchmark outperformance
* Heavy reliance on mutual funds
* Capital concentration among older clients

---

## Recommendations

* Introduce risk-adjusted performance tracking
* Develop client risk profiling models
* Analyze strategy drift over time
* Build predictive return models

---

## Tools Used

* Microsoft Excel (data modeling and analysis)
* Pivot tables
* Aggregations
* Statistical summaries

---

## Project Value

This project demonstrates the ability to:

* Work with multi-table financial datasets
* Generate business insights
* Perform performance analysis
* Interpret investor behavior
* Translate data into strategy recommendations

---
