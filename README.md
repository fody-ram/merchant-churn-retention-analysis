# 🛒 Merchant Churn & Retention Analysis

> A comprehensive Power BI project analyzing merchant retention, churn patterns, and business health.

---

## 📌 Executive Summary

This project analyzes **merchant churn and retention** using a large e-commerce transaction dataset (2009–2011).

**Key Highlights:**

- **5,881** unique merchants analyzed
- **50.79%** overall churn rate — more than half of all merchants stopped transacting
- Average merchant **tenure is only 9.1 months**
- Late 2011 cohorts showed dramatically better retention (90–100%)
- United Kingdom dominates revenue, while Norway has the highest average order value

---

## 🎯 Project Objectives

This analysis aims to answer critical business questions:

- What is the overall churn rate and retention performance?
- Which cohorts (onboarding periods) perform best?
- Is there a relationship between tenure and churn?
- Which countries and merchant segments are most valuable?
- What are the key trends in revenue and transactions?

---

## 📊 Dashboard Pages

| Page                   | Purpose                                    |
| ---------------------- | ------------------------------------------ |
| Overview (KPI Summary) | High-level business health at a glance     |
| Churn Analysis         | Deep dive into churn drivers and risk      |
| Cohort Retention       | Performance comparison by onboarding month |
| Merchant Segmentation  | Value segmentation by country and spend    |
| Transaction Trends     | Monthly revenue and activity trends        |
| Metrics Dictionary     | Full documentation of all metrics          |

---

## 🔑 Key Findings

- **High Churn Rate**: 50.79% of merchants have churned.
- **Early Churn Risk**: Most merchants leave within the first year (average tenure = 9.1 months).
- **Strong Late 2011 Improvement**: Cohorts from Sep–Dec 2011 show significantly higher retention.
- **Seasonal Peak**: November is consistently the strongest month for transactions and revenue.
- **High-Value Merchants**: Top spenders are mostly still active and have higher tenure.

---

## 💡 Recommendations

1. **Early Onboarding Program** — Focus retention efforts on the first 3–5 months.
2. **Win-back Campaign** — Target high-spend churned merchants.
3. **Replicate Late 2011 Success** — Investigate and scale what worked in Q3–Q4 2011.
4. **Seasonal Planning** — Prepare inventory and promotions for November peaks.

---

## 📁 Data Sources

- `merchant_level.csv` — Main merchant profile (churn status, tenure, spend, etc.)
- `transactions_clean.csv` — Detailed transaction records
- `cohort_retention.csv` — Pre-calculated cohort metrics
- `monthly_activity.csv` — Monthly business trends

---

## 📖 Metrics Dictionary

_(Included as a dedicated page in the dashboard — see full definitions in the report)_

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** (DAX, Power Query)
- Python (Pandas) — Data cleaning and merchant-level aggregation
- Excel / CSV — Data storage

---

## 🚀 How to View the Dashboard

Full interactive Power BI file (.pbix) is available upon request, Due to file size, it is not uploaded here.  
**Contact me** if you'd like the complete `.pbix` file + all data sources.

You can still explore the project through:
- Detailed project report (`Merchant_Churn_Retention_Report.docx`)


Page 1 — Overview (KPI Summary)
Provides a high-level snapshot of the business: total merchants, active vs churned split, overall churn rate, retention rate, and average tenure. The donut chart and churn trend line give immediate visual context for the scale of the retention challenge.
 <img width="887" height="495" alt="image" src="https://github.com/user-attachments/assets/f6eeb632-83bf-486c-950c-128025ceb8cc" />

 
Page 2 — Churn Analysis
Deep dives into who is churning and why. The scatter plot reveals the relationship between merchant tenure and inactivity, while the bar chart shows which countries have the highest churn rates. The inactivity distribution chart highlights how many merchants are at various stages of disengagement.
 <img width="895" height="495" alt="image" src="https://github.com/user-attachments/assets/8acb6fe3-8293-414a-bf26-ab57076fba62" />

Page 3 — Cohort Retention
Analyzes retention performance by cohort, the month each merchant first joined. The line chart with 50% benchmark line shows which cohorts performed above or below average, while the heatmap matrix uses color to make retention patterns immediately visible.
 <img width="891" height="495" alt="image" src="https://github.com/user-attachments/assets/e9723ec3-e7f9-4f87-a27b-ff1276f0a166" />

Page 4 — Merchant Segmentation
Segments merchants by value,  identifying the top 10 highest-spending merchants and comparing average order value and total spend across countries. The Country and Is_Active slicers allow filtering to compare active vs churned merchant spending patterns.
 <img width="888" height="495" alt="image" src="https://github.com/user-attachments/assets/aedeb46c-dcae-465a-9aa9-27b0cc0af8b4" />

Page 5 — Transaction Trends
Shows the overall business trajectory over time, monthly revenue, active merchant counts, and transaction volume. The trend line on the transactions chart cuts through monthly noise to reveal the underlying growth or decline direction.
<img width="892" height="495" alt="image" src="https://github.com/user-attachments/assets/f6b442ff-440f-40e8-aaf2-478bcf3bd87c" />

 

**Fadwa Ramadan Ali Hassan**  
Data Analyst | Business Intelligence Specialist

- [LinkedIn](https://linkedin.com/in/yourprofile)

---

**Built as a portfolio project to demonstrate skills in KPI definition, cohort analysis, churn modeling, and business intelligence.**

---
