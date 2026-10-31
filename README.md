# Call Centre Performance & Operations Dashboard (Excel)

## Project Overview
This project features an interactive, dynamic operations dashboard built in Microsoft Excel to monitor call volumes, billed revenue, agent performance, and customer satisfaction (CSAT) for a multi-city call center operations team. 

The dashboard enables team leads and operational managers to drill down into individual representative metrics, spot call volume seasonality, and evaluate account-level client billing across three primary regional hubs.

---

## Key Performance Indicators (KPIs)
* **Total Calls Handled:** 1,000 calls
* **Total Billed Amount:** $96,623
* **Total Handle Duration:** 89,850 units
* **Average Customer Rating:** 3.9 / 5.0
* **Happy Callers:** 307 (high-satisfaction interactions)

---

## Core Features & Analytical Breakdown

1. **Representative Slicer & Dynamic Profiles:**
   * Interactive slicer for representatives (`R01` to `R05`) dynamically updates agent call share percentages, call volume ranking, and billed revenue ranking.
   * Dynamic headshot and profile summary card tailored to the selected representative.

2. **Temporal & Operational Analysis:**
   * **Monthly Call Trend:** Area/line chart mapping call volume changes across the year, highlighting peak activity periods in March–April and October.
   * **Day-of-Week Load Distribution:** Horizontal bar chart revealing weekend operational spikes (Saturday leading with 40 calls, followed by Sunday with 36 calls).

3. **Regional & Account-Level Revenue Matrix:**
   * Account-by-representative cross-tabulation table evaluating client billing distribution (Accounts `C0001` through `C0015`) across Cincinnati, Cleveland, and Columbus.
   * Stacked regional contribution charts analyzing location-specific call share.

4. **Customer Satisfaction (CSAT) Metrics:**
   * Rating spread visualization tracking feedback on a 1–5 scale, showing peak satisfaction concentrated in 4-star and 5-star ratings.

---

## Technical Stack & Excel Features Used
* **Pivot Tables & Pivot Charts:** Aggregating granular call logs into summarized operational metrics.
* **Interactive Slicers:** Connected across multiple pivot tables for synchronized dashboard filtering.
* **Advanced Formulas:** Utilized `XLOOKUP`, `INDEX/MATCH`, nested logical functions (`IF`, `AND`), and summary functions (`SUMIFS`, `COUNTIFS`).
* **Conditional Formatting:** Applied data bars and heat-map scales to highlight high-value accounts and SLA metrics.
* **UI/UX Design:** Custom layout structure with card containers, shadow effects, and color-coded performance themes.

---

## Dashboard Preview
<img width="1435" height="730" alt="call centre report screenshot" src="https://github.com/user-attachments/assets/91e08778-ba37-4482-a008-afff48803a6b" />

