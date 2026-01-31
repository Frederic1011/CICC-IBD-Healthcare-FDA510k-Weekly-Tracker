# CICC IBD Healthcare FDA510k Weekly Tracker —— Regulatory Signals → Screening Long-list
Excel-based FDA 510(k) weekly tracker built during a CICC IBD Healthcare internship: Power Query ETL, product_code left-join with FOI classification, pivot dashboards, XLOOKUP-based enrichment for the long-list, and one-click VBA refresh to generate a management-ready weekly summary.

## 0) What this is
A lightweight Excel-based workflow that turns **foiclass and FDA 510(k) event data** into:
1) a **one-page Weekly Summary** (management-style KPIs),  
2) a set of **drill-down pivots** (Applicants / Clinical Area / Device Class / Recency), and  
3) a **Companies × Products long-list** used for early-stage screening and follow-up diligence.

**Design intent:** the output reads like a weekly internal update (clear, structured, audit-friendly), while the build demonstrates practical analyst skills (Power Query, pivots, Excel formulas, basic VBA automation and XLOOKUP).
