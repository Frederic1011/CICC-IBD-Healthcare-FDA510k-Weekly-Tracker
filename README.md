# FDA 510(k) Weekly Tracker — Regulatory Signals → Screening Long-list

## 0) What this is
A lightweight Excel-based workflow that turns **foiclass and FDA 510(k) event data** into:
1) a **one-page Weekly Summary** (weekly KPI snapshot),  
2) a set of **drill-down pivots** (Applicants / Clinical Area / Device Class / Recency), and  
3) a **Companies × Products long-list** used for early-stage screening and follow-up diligence.

**Design intent:** the output reads like a weekly internal update (clear, structured, review-ready), while the build demonstrates practical analyst skills (Power Query, pivots, Excel formulas, basic VBA automation and XLOOKUP).

## 1) Why it matters (business framing)
In healthcare deal screening, “what got cleared, where, and how recently” is often a fast proxy for:
- **Commercial readiness** (recent clearances),
- **Regulatory risk posture** (device class / pathway),
- **Category momentum** (clinical area concentration),
- **Repeat players** (top applicants / product activity).

This tool is built to support **weekly monitoring** and quickly surface “what changed” without manually reworking slides each week.

## 2) What you get (deliverables)
### 2.1 Weekly Summary (1-page)
A compact KPI panel intended for weekly review. Typical items include:
- Total record count
- “High” count/share (rule-based flag)
- Latest decision date + recency indicators
- Top Applicant (tie handled) + Top Clinical Area
- Top Device Class + share
- Long-list recency distribution (activity bucket)

<table align="center">
  <tr>
    <th>Basic Weekly Update</th>
    <th>Intermediate Weekly Update</th>
    <th>Advanced Weekly Update</th>
  </tr>
  <tr>
    <td><img src="outputs/05_basic_weekly_update_summary.png" width="300"/></td>
    <td><img src="outputs/06_intermediate_weekly_update_summary.png" width="300"/></td>
    <td><img src="outputs/07_advanced_weekly_update_summary.png" width="300"/></td>
  </tr>
</table>

### 2.2 Drill-down pivots (for discussion & drill)
- Applicants activity
- Clinical area distribution
- Device class distribution
- Long-list recency buckets

<table align="center">
  <tr>
    <th>Pivot – Top Applicants</th>
    <th>Pivot – Top Applicants (Enriched)</th>
  </tr>
  <tr>
    <td><img src="outputs/08_Pivot_Top_Applicants.png" width="400"/></td>
    <td><img src="outputs/09_Pivot_Top_Applicants%202.png" width="400"/></td>
  </tr>
</table>

<table align="center">
  <tr>
    <th>Pivot – Clinical Area</th>
    <th>Pivot – Clinical Area (Enriched)</th>
  </tr>
  <tr>
    <td><img src="outputs/10_Pivot_Clinical_Area.png" width="400"/></td>
    <td><img src="outputs/11_Pivot_Clinical_Area%202.png" width="400"/></td>
  </tr>
</table>

<table align="center">
  <tr>
    <th>Pivot – Top Device Class</th>
    <th>Pivot – Long-list Recency</th>
  </tr>
  <tr>
    <td><img src="outputs/12_Pivot_Top_Device_Class.png" width="400"/></td>
    <td><img src="outputs/14_Pivot_Longlist_Recency.png" width="400"/></td>
  </tr>
</table>

<div align="center">
  <b>Long-list Table</b><br/>
  <img src="outputs/13_Longlist_Companies_Products.png" width="900"/>
</div>
