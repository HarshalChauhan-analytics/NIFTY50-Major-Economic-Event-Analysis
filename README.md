# NIFTY 50 Economic Event Analysis (2020–2025)

An empirical event study analyzing the impact, market volatility, and recovery dynamics of the **NIFTY 50 Index** across major geopolitical, macroeconomic, and political events between 2020 and 2025.

# 📌 Project Overview

This project evaluates how the Indian stock market reacts to unexpected macro-level shocks and scheduled market events using the **Event Study Methodology**. By assessing Daily Log Returns, Abnormal Returns (AR), Cumulative Abnormal Returns (CAR), and Volatility (Standard Deviation), this study quantifies market resilience and recovery timelines.

### Analyzed Events
1. **COVID-19 Market Crash (2020)** – Exogenous biological shock & global liquidity crisis.
2. **Russia-Ukraine Conflict (2022)** – Geopolitical shock & global supply chain crisis (crude oil/commodities).
3. **Indian General Election Results (2024)** – Domestic political uncertainty and policy expectation adjustments.

## 🛠️ Methodology & Statistical Framework

The study utilizes a **±15 to ±30 trading day event window** surrounding each event date ($t_0$).

* **Return Model:** Calculated using Daily Log Returns ($R_t = \ln(P_t / P_{t-1})$).
* **Benchmark Comparison:** Evaluated against baseline pre-event estimation windows.
* **Statistical Testing:** Conducted in **SPSS v27** to test for significant deviation from normal market behavior:
  * **Paired Samples t-Test** (Pre- vs. Post-event mean return shifts).
  * **Independent Samples t-Test** (Sub-period impact comparisons).
  * **One-Way ANOVA** (Variance & volatility across all three event periods).

## 📊 Summary of Findings

| Metric / Parameter | COVID-19 Crash (2020) | Russia-Ukraine War (2022) | Lok Sabha Elections (2024) |
| :--- | :--- | :--- | :--- |
| **Peak Drawdown ($t_0$)** | ~-12.98% (Single Day) | ~-4.78% (Single Day) | ~-5.93% (Single Day) |
| **Volatility ($\sigma$)** | Extreme High (~4.2%) | Moderate (~1.4%) | Elevated (~1.8%) |
| **Recovery Window** | Extended (~55+ Trading Days) | Short-to-Mid (~12–18 Days) | V-Shaped (< 3 Trading Days) |
| **Market Efficiency** | Severe Mispricing / Panic | Orderly Re-pricing | Rapid Realignment |

---

## 📁 Repository Structure

```text
├── SIP_FINAL_REPORT_BEPF04.docx          # Complete Academic Project Report (Lit Review, Methodology, SPSS Results)
├── WEEK6_NIFTY50_Event_Analysis_Harshal.xlsx # Full Dataset & Analysis Workbook
│   ├── Sheet 1: Raw Data (2020-2025)
│   ├── Sheet 2: COVID-19 Analysis
│   ├── Sheet 3: Russia-Ukraine Analysis
│   ├── Sheet 4: Elections 2024 Analysis
│   └── Sheet 5: Comparative Summary
└── README.md                             # Project Documentation
