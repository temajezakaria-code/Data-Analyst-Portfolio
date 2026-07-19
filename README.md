
# Temaje Zakaria — Data Analyst Portfolio

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

Hi, I'm Temaje. I graduated from Humber College with a background in Business
Management in 2022, and in 2025 I completed a Business Analytics Certificate from Seneca College to
move more deliberately into data. I'm looking to break into a Data Analyst role
where I can turn messy business data into something a team can actually act on.

**Core skills:** SQL (joins, CTEs, window functions) · Python (Pandas, NumPy,
Matplotlib, scikit-learn) · Excel (pivot tables, VLOOKUP/INDEX-MATCH, conditional formatting)
· Power BI (data modeling, DAX, dashboard design) · Machine Learning (classification, SHAP explainability) · data cleaning ·
business analysis · data storytelling

## Projects

### [NorthStar Retail Group — Retail Analytics](https://github.com/temajezakaria-code/northstar-retail-analytics)

**Goal:** Analyze 3 years of retail transaction data to identify revenue trends, customer retention patterns, and regional/category performance risks.

**Description:** End-to-end analytics project — SQL star-schema database, Python data cleaning and EDA, an Excel KPI dashboard, and a 4-page Power BI executive dashboard design — built on a simulated multi-region retailer's data.

**Skills:** SQL (window functions, RFM segmentation, cohort analysis), Python (pandas, NumPy, matplotlib), Excel (pivot tables, conditional formatting, VLOOKUP/INDEX-MATCH), Power BI (data modeling, DAX).

**Results:** Identified a 41.8% revenue concentration in 2 of 5 regions and a steep month-1 customer retention cliff, leading to a targeted recommendation projected to add ~$364K in incremental revenue.

### [PrimeBank Customer Retention Intelligence](https://github.com/temajezakaria-code/primebank-churn-intelligence)

**Goal:** Predict which bank customers are at risk of churning, and determine whether it's actually profitable to intervene.

**Description:** A full machine learning pipeline on a real 10,000-customer bank dataset — SQL analysis, statistical hypothesis testing (chi-square, t-tests), a Gradient Boosting churn model with SHAP explainability, a cost-sensitive business economics analysis, and a live deployed Streamlit app for real-time predictions.

**Skills:** SQL, statistical hypothesis testing, machine learning (classification, cross-validation), model explainability (SHAP), cost-sensitive decision analysis, app deployment.

**Results:** Built a model with 0.869 ROC-AUC, statistically confirmed that Germany churns at 2x the rate of other markets (p ≈ 3.8×10⁻⁶⁶), and found that a naive "target everyone" retention strategy would lose $49,125, while the model's optimized threshold generates ~$62,750/year in projected net value.

### [Meridian Health Network — Hospital Operations Analytics](https://github.com/temajezakaria-code/meridian-health-operations-analytics)

**Goal:** Identify the root causes behind rising ED wait times, uneven staffing, appointment no-shows, and concentrated readmissions across a 4-hospital network, and recommend practical operational fixes.

**Description:** A full operations analytics build on a 414,000-row hospital dataset — SQL bottleneck and cohort analysis, Python statistical testing and time series forecasting, and an Excel/Power BI executive dashboard suite covering Executive Operations, Emergency Department, Staffing, and Patient Flow.

**Skills:** SQL (window functions, CASE-based risk scoring, cohort analysis), Python (hypothesis testing, correlation analysis, Holt-Winters forecasting), Excel (pivot tables, conditional formatting, VLOOKUP/INDEX-MATCH), Power BI dashboard design.

**Results:** Found that ED wait times climbed structurally (46.6 → 64.0 min average, 2023-2025) and Night shifts run understaffed network-wide (80-85% vs. 93% on Day/Evening) — but directly tested (not assumed) whether the two were causally linked, honestly reporting a non-significant result at the data granularity available. Delivered 15 insights and 15 recommendations, including a fast-track pathway for low-acuity ED patients projected to be the highest-leverage fix.

### [Apex Distribution Group — Supply Chain & Inventory Intelligence](https://github.com/temajezakaria-code/apex-supply-chain-intelligence)

**Goal:** Identify the root causes behind stockouts, supplier delivery delays, and uneven fulfillment performance across a 6-warehouse, 15-supplier distribution network, and recommend practical operational fixes.

**Description:** A full supply chain analytics build on a 390,000-row dataset — SQL ABC/Pareto classification and supplier risk scoring, Python statistical root-cause testing and demand forecasting, and an Excel/Power BI dashboard suite covering Executive, Warehouse, Supplier, and Inventory views.

**Skills:** SQL (window functions, Pareto analysis, compound risk scoring), Python (chi-square testing, correlation analysis, Holt-Winters forecasting), Excel (pivot tables, conditional formatting, VLOOKUP/INDEX-MATCH), Power BI dashboard design.

**Results:** Confirmed a real ABC revenue concentration (13% of SKUs drive 46% of revenue) and a striking 22.5-point fulfillment gap between Online (68.9%) and Store (91.4%) perfect-order rates — while directly testing (not assuming) whether supplier delivery delays explain stockouts, honestly reporting a non-significant result and redirecting the top recommendation toward inventory forecasting instead.

### [Vertex Commerce — A/B Testing & Experimentation Analytics](https://github.com/temajezakaria-code/vertex-experimentation-analytics)

**Goal:** Evaluate whether a portfolio of 30 A/B tests was conducted with genuine statistical rigor — properly powered, checked against guardrail metrics, and free of common experimentation pitfalls — rather than assessing individual test outcomes in isolation.

**Description:** An experimentation analytics study built on a 433,900-observation dataset with programmed ground truth, allowing statistical findings to be verified against known effects rather than accepted at face value. Includes SQL-computed two-proportion z-tests and sample ratio mismatch checks, formal statistical power analysis, novelty-decay curve fitting, and an Excel/Power BI dashboard suite evaluating program-level health rather than individual results.

**Skills:** SQL (manually-derived statistical tests, CTEs, window functions), statistical methods (hypothesis testing, power analysis, meta-analysis), Excel (pivot tables, conditional formatting, VLOOKUP/INDEX-MATCH), Power BI dashboard design, experimentation methodology.

**Results:** Found that all 30 of 30 tests in the portfolio were statistically underpowered to detect a typical 5% relative lift, including tests that would appear adequately sized under informal review. The single largest revenue-lift estimate in the portfolio ($2.27 per user) was associated with a non-significant result, illustrating how a primary-metric-only evaluation could discard a genuinely promising finding due to insufficient power rather than an absence of effect.

*More projects coming soon.*

 [temajezakaria@gmail.com](mailto:temajezakaria@gmail.com)

---

© 2026 Temaje Zakaria. All rights reserved.
