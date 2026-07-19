
# Temaje Zakaria — Data Analyst Portfolio

I turn messy business data into decisions leadership can actually act on. Six
end-to-end projects — SQL, Python, Excel, Power BI — each built the way a working
analyst actually works: find the real answer, even when it's inconvenient, and put
a dollar figure on the recommendation. A few examples: a **$364K revenue
opportunity** I quantified in a retail dataset, a churn model that would have
**lost $49,125** if deployed naively, and a finding that **all 30 of 30** A/B tests
in one portfolio were too small to trust — the kind of result most analysts don't
go looking for, because it complicates the story.

I graduated from Humber College (Business Management, 2022) and completed a
Business Analytics Certificate from Seneca College in 2025 to make this shift
deliberately, not accidentally. I'm looking to bring that same instinct — get the
number right, then say what it means for business.

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-8A2BE2?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

**Core skills:** SQL (joins, CTEs, window functions) · Python (Pandas, NumPy,
Matplotlib, scikit-learn) · Excel (pivot tables, VLOOKUP/INDEX-MATCH, conditional
formatting) · Power BI (data modeling, DAX, dashboard design) · Machine Learning
(classification, SHAP explainability) · statistical hypothesis testing · data
storytelling

## Projects

---

### [Vertex Commerce — A/B Testing & Experimentation Analytics](https://github.com/temajezakaria-code/vertex-experimentation-analytics)

![Vertex Preview](https://raw.githubusercontent.com/temajezakaria-code/vertex-experimentation-analytics/main/images/dashboard1_executive_summary.png)

**Goal:** Determine whether a portfolio of 30 A/B tests was conducted with genuine statistical rigor — properly powered, checked against guardrail metrics, and free of common experimentation pitfalls.

**Description:** An experimentation analytics study on 433,900 observations with programmed ground truth, including SQL-computed two-proportion z-tests, formal statistical power analysis, and novelty-decay curve fitting.

**Skills:** SQL (manually-derived statistical tests), statistical methods (power analysis, meta-analysis), Excel, Power BI dashboard design.

**Results:** Found that **all 30 of 30 tests** were statistically underpowered to detect a typical 5% relative lift. The single largest revenue-lift result in the portfolio (**$2.27 per user**) came from a test that wasn't statistically significant — a promising finding a primary-metric-only review would have discarded.

---

### [Nova Home Goods — Marketing Attribution & Media Mix Modeling](https://github.com/temajezakaria-code/nova-attribution-analytics)

![Nova Preview](https://raw.githubusercontent.com/temajezakaria-code/nova-attribution-analytics/main/images/dashboard1_executive_summary.png)

**Goal:** Determine whether multi-touch attribution methods (Markov chain, Shapley Value) recover a more accurate picture of marketing channel value than last-click attribution.

**Description:** An attribution modeling study on 20,000 customer journeys with programmed ground truth, implementing Markov chain and exact Shapley Value attribution from first principles.

**Skills:** SQL, statistical and game-theoretic methods (Markov chains, Shapley values), Excel, Power BI dashboard design.

**Results:** Last-click attribution had the weakest correspondence with true channel value (**0.476 rank correlation**) of four models tested; Shapley Value and Linear attribution tied for strongest (**0.619 each**). Identified a channel returning only **$0.57 per dollar spent** — well past its point of efficient return.

---

### [PrimeBank Customer Retention Intelligence](https://github.com/temajezakaria-code/primebank-churn-intelligence)

![PrimeBank Preview](https://raw.githubusercontent.com/temajezakaria-code/primebank-churn-intelligence/main/images/shap_summary.png)

**Goal:** Predict which bank customers are at risk of churning, and determine whether it's actually profitable to intervene.

**Description:** A full machine learning pipeline on a real 10,000-customer bank dataset — SQL analysis, statistical hypothesis testing, a Gradient Boosting model with SHAP explainability, and a cost-sensitive business economics analysis.

**Skills:** SQL, statistical hypothesis testing, machine learning, model explainability (SHAP), cost-sensitive decision analysis.

**Results:** Built a model with **0.869 ROC-AUC**, statistically confirmed Germany churns at 2x the rate of other markets, and found a naive "target everyone" strategy would **lose $49,125**, while the model's optimized threshold generates **~$62,750/year** in projected value.

---

### [NorthStar Retail Group — Retail Analytics](https://github.com/temajezakaria-code/northstar-retail-analytics)

![NorthStar Preview](https://raw.githubusercontent.com/temajezakaria-code/northstar-retail-analytics/main/images/dashboard_preview.gif)

**Goal:** Analyze 3 years of retail transaction data to identify revenue trends, customer retention patterns, and regional/category performance risks.

**Description:** End-to-end analytics project — SQL star-schema database, Python data cleaning and EDA, an Excel KPI dashboard, and a 4-page Power BI executive dashboard design.

**Skills:** SQL (window functions, RFM segmentation, cohort analysis), Python, Excel, Power BI.

**Results:** Identified a **41.8% revenue concentration** in 2 of 5 regions and a steep month-1 customer retention cliff, leading to a recommendation projected to add **~$364K** in incremental revenue.

---

### [Meridian Health Network — Hospital Operations Analytics](https://github.com/temajezakaria-code/meridian-health-operations-analytics)

![Meridian Preview](https://raw.githubusercontent.com/temajezakaria-code/meridian-health-operations-analytics/main/images/dashboard1_executive_operations.png)

**Goal:** Identify the root causes behind rising ED wait times, uneven staffing, appointment no-shows, and concentrated readmissions across a 4-hospital network.

**Description:** A full operations analytics build on a 414,000-row hospital dataset — SQL bottleneck analysis, Python statistical testing and forecasting, and an Excel/Power BI dashboard suite.

**Skills:** SQL (window functions, cohort analysis), Python (hypothesis testing, forecasting), Excel, Power BI.

**Results:** Found ED wait times climbed **46.6 → 64.0 minutes** (2023-2025) and Night shifts run understaffed network-wide — but directly tested (not assumed) whether the two were causally linked, honestly reporting a non-significant result.

---

### [Apex Distribution Group — Supply Chain & Inventory Intelligence](https://github.com/temajezakaria-code/apex-supply-chain-intelligence)

![Apex Preview](https://raw.githubusercontent.com/temajezakaria-code/apex-supply-chain-intelligence/main/images/dashboard1_executive_supply_chain.png)

**Goal:** Identify the root causes behind stockouts, supplier delivery delays, and uneven fulfillment performance across a 6-warehouse distribution network.

**Description:** A full supply chain analytics build on a 390,000-row dataset — SQL ABC/Pareto classification, Python root-cause testing and demand forecasting, and an Excel/Power BI dashboard suite.

**Skills:** SQL (Pareto analysis, risk scoring), Python (chi-square testing, forecasting), Excel, Power BI.

**Results:** Confirmed a real ABC revenue concentration (**13% of SKUs drive 46% of revenue**) and a **22.5-point fulfillment gap** between Online and Store — while honestly reporting that supplier delays don't significantly explain stockouts.

---


✉️ [temajezakaria@gmail.com](mailto:temajezakaria@gmail.com)

---

© 2026 Temaje Zakaria. All rights reserved.
