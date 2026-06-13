# Car Dealership Financial Risk Assessment Report

## Executive Summary

This report presents a comprehensive financial risk assessment of the car dealership's monthly performance data (100 records from the Sales Expenses table in the Car Dealership Airtable base), supplemented with regulatory and industry-scale context critical to understanding the dealership operating environment.

---

## 1. Financial Risk Assessment

### 1.1 Months with Negative Net Profit

**4 out of 100 months** recorded a negative net profit, representing a 4% loss-month incidence rate:

| # | Month | Net Profit | Best Selling Category | Highest Expense Type |
|---|-------|-----------|----------------------|---------------------|
| 1 | 2015-05 | -17,641.33 | Electric | Utilities |
| 2 | 2020-07 | -11,345.47 | Sedan | Maintenance |
| 3 | 2021-04 | -14,166.63 | Electric | Employee Salaries |
| 4 | 2022-10 | -11,150.22 | Sedan | Rent |

### 1.2 Total Cumulative Net Loss

The total cumulative net loss across all negative-profit months is **-$54,303.65**.

The largest single-month loss occurred in **May 2015** at -$17,641.33, driven by Utilities as the highest expense category. The most recent loss month was **October 2022** at -$11,150.22, with Rent as the dominant expense.

### 1.3 Highest Expense Type Analysis in Negative-Profit Months

The four Highest Expense Type values among the negative-profit months are:

- **Utilities** (2015-05)
- **Maintenance** (2020-07)
- **Employee Salaries** (2021-04)
- **Rent** (2022-10)

**Finding: All four Highest Expense Types are distinct.** No single expense category repeats among the loss months. This indicates that losses are not concentrated in one cost driver but are distributed across different operational expense categories, suggesting varied and episodic root causes rather than a systemic single-category overspend.

### 1.4 Additional Observations

- **Best Selling Category pattern**: Electric and Sedan each appear twice as the best-selling category in loss months, suggesting these segments may carry thinner margins or higher associated costs.
- **Temporal spread**: Loss months span from 2015 to 2022 with no clustering, indicating isolated events rather than a sustained downturn period.
- **Loss severity trend**: The largest loss (-$17,641.33) occurred earliest (2015-05), with subsequent losses ranging from -$11,150 to -$14,167, suggesting some improvement in loss magnitude over time.

---

## 2. Regulatory Context: US Franchise Laws Restricting Direct Manufacturer Sales

### 2.1 Legal Framework

According to the Wikipedia article on car dealerships, the specific type of US state laws that restrict direct manufacturer-to-consumer auto sales are **state franchise laws** (also referred to as state dealer franchise protection laws).

Key regulatory facts:

- **By 2010, all 50 US states and the District of Columbia had enacted some form of franchise laws** prohibiting manufacturers from selling vehicles directly to consumers, requiring new cars to be sold only through licensed, independently owned franchised dealerships.
- These laws also restrict the establishment of new dealerships that compete with existing ones (by 2009, most states imposed such restrictions).
- All states impose severe limits on manufacturers' ability to terminate a franchise relationship.
- Most states prevent manufacturers from engaging in "quantity forcing" (requiring dealers to purchase unordered vehicles).
- Many states limit manufacturer discrimination between dealers and mandate specific warranty repair compensation terms.

### 2.2 Economic Assessment

Economists have characterized these franchise laws as a form of **rent-seeking** that:
- Increases consumer vehicle prices
- Limits competition
- Raises profits for incumbent dealers
- Extracts rents from automobile manufacturers

Multiple studies have confirmed that dealer protection regulations increase car costs for consumers and limit manufacturer profitability.

### 2.3 Impact on New Entrants

Companies attempting direct-to-consumer models (e.g., Tesla) have faced constant legal pressure from these franchise laws, being forced to operate galleries where cars can only be ordered online rather than purchased on-site.

### 2.4 Relevance to Dealership Risk Assessment

These franchise laws create a **regulatory moat** that protects existing dealerships from manufacturer competition but also constrains business model innovation. For this dealership:
- The franchise law framework provides market stability and protects against manufacturer direct-sale disruption
- However, it also limits flexibility in sales channel evolution (e.g., online direct sales)
- Regulatory dependence means policy changes could significantly impact competitive positioning

---

## 3. Industry Scale Context: NADA Representation

### 3.1 National Automobile Dealers Association (NADA) Scale

Per the NADA website (nada.org/about), the organization's key scale metrics are:

- **16,000+ franchised new-car dealer members** represented
- **32,500+ franchises** represented across those dealers
- **Founded in 1917**
- NADA serves as the voice of franchised new-car and -truck dealers before Congress, executive branch, federal agencies, and federal courts

### 3.2 Historical Dealer Count Trend

The Wikipedia article notes a long-term decline in US dealership count:
- 1927: 53,125 dealerships (peak)
- 1960: 33,658
- 1980: 23,379
- 2001: 22,007

This consolidation trend reflects increasing scale economies and regulatory barriers to new dealership entry.

### 3.3 Relevance to Dealership Risk Assessment

With NADA representing 16,000+ dealers and 32,500+ franchises, the dealership operates within a large, organized industry bloc with significant collective lobbying power. This scale:
- Provides industry-wide advocacy protecting the franchise model
- Enables access to NADA educational resources and best practices
- Suggests the 4% loss-month rate should be benchmarked against industry norms available through NADA data resources

---

## 4. Conclusions and Risk Rating

| Risk Dimension | Assessment |
|---------------|-----------|
| Loss frequency | **Low** — Only 4% of months show losses |
| Cumulative loss magnitude | **Moderate** — $54,303.65 total, with largest single loss at $17,641 |
| Expense concentration risk | **Low** — No single expense category dominates loss months |
| Regulatory protection | **Strong** — State franchise laws provide significant market protection |
| Industry support infrastructure | **Strong** — NADA represents 16,000+ dealers with robust advocacy |

**Overall Financial Risk Rating: LOW-MODERATE**

The dealership demonstrates generally stable profitability with episodic, non-systemic losses distributed across varied expense categories. The regulatory environment (state franchise laws) and industry infrastructure (NADA's 16,000+ dealer representation) provide significant structural support. The primary risk factors are the variability in loss-driving expense categories and the dependence on regulatory protections that could evolve over time.

---

*Report generated from: Car Dealership Airtable base (Sales Expenses table, 100 records), Wikipedia article on car dealerships, and NADA website (nada.org).*
