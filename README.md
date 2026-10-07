# supply-chain-delivery-optimisation
End-to-end supply chain &amp; delivery performance analysis using Python - BA/DA Portfolio Project

# 🚚 Supply Chain & Delivery Optimisation
### End-to-End Business Analysis | Python | SQL | Jira | Confluence

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightblue)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualisation-orange)
![Jira](https://img.shields.io/badge/Jira-Agile%20Board-blue?logo=jira)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Project Overview

This project simulates a real-world Business Analyst engagement
within a UK retail supply chain operation.

The business problem:
> *"Delivery times are inconsistent, warehouse costs are rising,
> and customers are leaving due to late or failed deliveries.
> We need to understand why — and fix it."*

Acting as a BA/DA, I gathered requirements, analysed 500 orders
across Jan–Dec 2023, identified root causes, and produced
data-driven recommendations for the operations team.

---

## 🎯 Business Questions Answered

| # | Question |
|---|---|
| 1 | Which regions have the worst delivery performance? |
| 2 | Which warehouses are underperforming? |
| 3 | Does high warehouse utilisation cause late deliveries? |
| 4 | Which shipping mode has the most failures? |
| 5 | What is the financial impact of failed deliveries? |
| 6 | How do late/failed deliveries affect satisfaction & returns? |
| 7 | What does the monthly delivery trend look like? |

---

## 📊 Key Findings

| Metric | Value |
|---|---|
| ✅ On-Time Delivery Rate | 57.2% (Industry benchmark: 85%+) |
| ❌ Failed Delivery Rate | 13.4% |
| 💷 Revenue at Risk | £146,448 from failed orders |
| ⭐ Satisfaction (Failed Orders) | 1.31 / 5 |
| 🔁 Return Rate (Failed Orders) | 56.7% |
| 🏭 Overloaded Warehouses | Edinburgh & Cardiff (>80% utilisation) |

---

## 📁 Project Structure

```
supply-chain-delivery-optimisation/
│
├── 📓 notebooks/
│   └── supply_chain_analysis.ipynb   ← Full analysis notebook
│
├── 📁 data/
│   └── supply_chain_orders.csv       ← 500-row dataset
│
├── 📁 outputs/
│   ├── fig1_delivery_overview.png
│   ├── fig2_regional_performance.png
│   ├── fig3_warehouse_performance.png
│   ├── fig4_utilisation_vs_delay.png
│   ├── fig5_shipping_mode.png
│   ├── fig6_product_category.png
│   ├── fig7_monthly_trends.png
│   └── full_correlation_heatmap.png
│
├── 📁 process-flows/
│   ├── SCDO_AS-IS_Process_Flow.xml
│   └── SCDO_TO-BE_Process_Flow.xml
│
├── 📁 docs/
│   └── SCDO_BRD_v1.0.docx           ← Business Requirements Document
│
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Core analysis language |
| **Pandas** | Data manipulation & aggregation |
| **Matplotlib / Seaborn** | Data visualisation |
| **Jupyter Notebook** | Interactive analysis & presentation |
| **Jira** | Agile board, user stories, sprint management |
| **Confluence** | BRD documentation |
| **Draw.io** | AS-IS / TO-BE process flow diagrams |
| **Git / GitHub** | Version control & portfolio sharing |

---

## 📈 Sample Visualisations

### Delivery Status Overview
![Fig 1](outputs/fig1_delivery_overview.png)

### Regional Performance
![Fig 2](outputs/fig2_regional_performance.png)

### Warehouse Utilisation vs Delay
![Fig 4](outputs/fig4_utilisation_vs_delay.png)

### Full Correlation Heatmap
![Heatmap](outputs/full_correlation_heatmap.png)

---

## 💡 Recommendations

| Priority | Recommendation |
|---|---|
| 🔴 High | Redistribute stock from Edinburgh & Cardiff — reduce utilisation below 80% |
| 🔴 High | Cap Same-Day shipping orders when fulfilment capacity is low |
| 🔴 High | Introduce priority fulfilment for Electronics & Furniture |
| 🟡 Medium | Establish monthly SLA review for London & Scotland regions |
| 🟡 Medium | Proactive customer communication for at-risk orders |
| 🟢 Low | Build monthly on-time delivery KPI dashboard |

---

## 🗂️ BA Artefacts Produced

- ✅ Business Requirements Document (BRD)
- ✅ 9 User Stories with Acceptance Criteria (Jira)
- ✅ 3 Sprint Agile Board
- ✅ AS-IS Process Flow (Draw.io)
- ✅ TO-BE Process Flow (Draw.io)
- ✅ Python Analysis (7 charts + correlation heatmap)
- ✅ Key Findings & Recommendations Summary

---
