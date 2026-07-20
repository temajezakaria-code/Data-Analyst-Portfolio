# Temaje Zakaria — Data Analyst

I chase the true answer, not the convenient one. Across six analytics projects: a
30-test experimentation program turned out **entirely underpowered**, a naive
"target everyone" churn strategy would **lose money** while a smarter one **makes
it**, and a marketing channel spending **$1.77M** returns just **57 cents per
dollar**. Here's the proof.

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

| 6 Projects | 60+ SQL Queries | 1.5M+ Rows Analyzed | 3 Honest Null Results |
|---|---|---|---|

**Jump to:** [Vertex ⭐ start here](#vertex-commerce--product--tech) · [Nova](#nova-home-goods--marketing) · [PrimeBank](#primebank--banking) · [NorthStar](#northstar-retail--retail) · [Apex](#apex-distribution--supply-chain) · [Meridian](#meridian-health--healthcare)

*Actively adding new projects — this portfolio is a running practice, not a one-time build.*

---

### Vertex Commerce — Product / Tech ⭐ *(start here — my most technically distinctive project)*

<img src="https://raw.githubusercontent.com/temajezakaria-code/vertex-experimentation-analytics/main/images/dashboard1_executive_summary.png" width="500">

**All 30 of 30 A/B tests were statistically underpowered** — even ones that looked adequately sized.

<details>
<summary>See the full breakdown (goal, method, skills, results)</summary>
<br>

**Goal:** Determine whether a portfolio of 30 A/B tests was conducted with genuine statistical rigor — properly powered, checked against guardrail metrics, and free of common experimentation pitfalls.

**Description:** An experimentation analytics study on 433,900 observations with programmed ground truth, including SQL-computed two-proportion z-tests, formal statistical power analysis, and novelty-decay curve fitting.

**Skills:** SQL (manually-derived statistical tests), statistical methods (power analysis, meta-analysis), Excel, Power BI dashboard design.

**Results:** The single largest revenue-lift result in the portfolio (**$2.27 per user**) came from a test that wasn't statistically significant — a promising finding a primary-metric-only review would have discarded.

[**→ View full project**](https://github.com/temajezakaria-code/vertex-experimentation-analytics)
</details>

---

### Nova Home Goods — Marketing

<img src="https://raw.githubusercontent.com/temajezakaria-code/nova-attribution-analytics/main/images/dashboard1_executive_summary.png" width="500">

A channel spending **$1.77M** returns just **$0.57 per dollar**.

<details>
<summary>See the full breakdown (goal, method, skills, results)</summary>
<br>

**Goal:** Determine whether multi-touch attribution methods (Markov chain, Shapley Value) recover a more accurate picture of marketing channel value than last-click attribution.

**Description:** An attribution modeling study on 20,000 customer journeys with programmed ground truth, implementing Markov chain and exact Shapley Value attribution from first principles.

**Skills:** SQL, statistical and game-theoretic methods (Markov chains, Shapley values), Excel, Power BI dashboard design.

**Results:** Last-click attribution had the weakest correspondence with true channel value (**0.476 rank correlation**) of four models tested; Shapley Value and Linear attribution tied for strongest (**0.619 each**).

[**→ View full project**](https://github.com/temajezakaria-code/nova-attribution-analytics)
</details>

---

### PrimeBank — Banking

<img src="https://raw.githubusercontent.com/temajezakaria-code/primebank-churn-intelligence/main/images/shap_summary.png" width="500">

"Target everyone" **loses $49,125**; the optimized model **nets ~$62,750/year**.

<details>
<summary>See the full breakdown (goal, method, skills, results)</summary>
<br>

**Goal:** Predict which bank customers are at risk of churning, and determine whether it's actually profitable to intervene.

**Description:** A full machine learning pipeline on a real 10,000-customer bank dataset — SQL analysis, statistical hypothesis testing, a Gradient Boosting model with SHAP explainability, and a cost-sensitive business economics analysis.

**Skills:** SQL, statistical hypothesis testing, machine learning, model explainability (SHAP), cost-sensitive decision analysis.

**Results:** Built a model with **0.869 ROC-AUC** and statistically confirmed Germany churns at 2x the rate of other markets.

[**→ View full project**](https://github.com/temajezakaria-code/primebank-churn-intelligence)
</details>

---

### NorthStar Retail — Retail

<img src="https://raw.githubusercontent.com/temajezakaria-code/northstar-retail-analytics/main/images/dashboard1_executive_summary.png" width="500">

**41.8%** of revenue sits in just 2 of 5 regions.

<details>
<summary>See the full breakdown (goal, method, skills, results)</summary>
<br>

**Goal:** Analyze 3 years of retail transaction data to identify revenue trends, customer retention patterns, and regional/category performance risks.

**Description:** End-to-end analytics project — SQL star-schema database, Python data cleaning and EDA, an Excel KPI dashboard, and a 4-page Power BI executive dashboard design.

**Skills:** SQL (window functions, RFM segmentation, cohort analysis), Python, Excel, Power BI.

**Results:** Identified a steep month-1 customer retention cliff, leading to a recommendation projected to add **~$364K** in incremental revenue.

[**→ View full project**](https://github.com/temajezakaria-code/northstar-retail-analytics)
</details>

---

### Apex Distribution — Supply Chain

<img src="https://raw.githubusercontent.com/temajezakaria-code/apex-supply-chain-intelligence/main/images/dashboard1_executive_supply_chain.png" width="500">

A **22.5-point** fulfillment gap between Online and Store, hiding behind an aggregate number that looked fine.

<details>
<summary>See the full breakdown (goal, method, skills, results)</summary>
<br>

**Goal:** Identify the root causes behind stockouts, supplier delivery delays, and uneven fulfillment performance across a 6-warehouse distribution network.

**Description:** A full supply chain analytics build on a 390,000-row dataset — SQL ABC/Pareto classification, Python root-cause testing and demand forecasting, and an Excel/Power BI dashboard suite.

**Skills:** SQL (Pareto analysis, risk scoring), Python (chi-square testing, forecasting), Excel, Power BI.

**Results:** Confirmed a real ABC revenue concentration — **13% of SKUs drive 46% of revenue**.

[**→ View full project**](https://github.com/temajezakaria-code/apex-supply-chain-intelligence)
</details>

---

### Meridian Health — Healthcare

<img src="https://raw.githubusercontent.com/temajezakaria-code/meridian-health-operations-analytics/main/images/dashboard1_executive_operations.png" width="500">

ED wait times climbed **46.6 → 64.0 min** — tested the obvious explanation directly, found it didn't hold up, said so.

<details>
<summary>See the full breakdown (goal, method, skills, results)</summary>
<br>

**Goal:** Identify the root causes behind rising ED wait times, uneven staffing, appointment no-shows, and concentrated readmissions across a 4-hospital network.

**Description:** A full operations analytics build on a 414,000-row hospital dataset — SQL bottleneck analysis, Python statistical testing and forecasting, and an Excel/Power BI dashboard suite.

**Skills:** SQL (window functions, cohort analysis), Python (hypothesis testing, forecasting), Excel, Power BI.

**Results:** Directly tested whether Night-shift understaffing explains the wait-time increase — found no statistically significant link, and reported that honestly rather than assuming it.

[**→ View full project**](https://github.com/temajezakaria-code/meridian-health-operations-analytics)
</details>

---

**Skills:** SQL · Python (Pandas, scikit-learn, SHAP) · Excel · Power BI · statistical hypothesis testing · Git

✉️ [temajezakaria@gmail.com](mailto:temajezakaria@gmail.com)

---

© 2026 Temaje Zakaria. All rights reserved.
