# Business Analytics Laboratory & Power BI Retail Intelligence

> **A business analytics laboratory and intelligence portfolio comprising 5 empirical analytical experiments and an interactive Power BI retail performance dashboard.**

[![Power BI](https://img.shields.io/badge/BI-Power%20BI-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Analytics](https://img.shields.io/badge/Domain-Retail%20Analytics-blue)](https://github.com/keerthi19hub)
[![PDF](https://img.shields.io/badge/Documentation-Technical%20Report-red)](https://github.com/keerthi19hub/Business-Analytics)

---

## 1. Laboratory Overview

The **Business Analytics Laboratory** demonstrates applied business intelligence (BI), quantitative decision support, and commercial data modeling.

The centerpiece of this repository is a multi-dimensional **Retail Database Analytics Dashboard** built in **Microsoft Power BI** (`Assignment 1 Retail db.pbix`) supported by a comprehensive technical analytical report (`Business Analytics.pdf`) and 5 structured laboratory experiments evaluating sales velocity, customer cohorts, and KPI trends.

---

## 2. Laboratory Experiments & Scope

| Experiment | Title / Focus Area | Analytical Objectives & Methods |
| :--- | :--- | :--- |
| **Experiment 1** | **Retail Performance Dashboard** | Star-schema modeling, retail sales aggregation, regional revenue breakdowns, and Power BI interactive slicers (`Assignment 1 Retail db.pbix`). |
| **Experiment No:2** | **Customer Segmentation & Sales Velocity** | Demographic filtering, customer order frequencies, ticket size distribution, and Pareto analysis. |
| **Experiment no:3** | **Key Performance Indicator (KPI) Tracking** | Measuring Gross Margin, Net Revenue, Year-over-Year (YoY) growth, and inventory turnover ratios. |
| **Experiment No 4** | **Descriptive Analytics & Statistical Summaries** | Mean transaction value, standard deviation of regional sales, and variance profiling. |
| **Experiment :06** | **Executive Reporting & Decision Insights** | Data storytelling, translating quantitative metrics into actionable business inventory recommendations. |

---

## 3. Power BI Dashboard Architecture (`Assignment 1 Retail db.pbix`)

- **Data Modeling:** Built on a relational schema linking transactions, store locations, product categories, and customer demographics.
- **DAX Calculations:**
  - Total Sales Revenue: `SUM(Transactions[TotalAmount])`
  - Average Order Value (AOV): `DIVIDE([Total Sales], DISTINCTCOUNT(Transactions[OrderID]))`
  - Regional Contribution %: Percentage distribution across retail store outlets.
- **Visuals:** Executive card KPIs, donut charts for category distributions, clustered column charts for monthly revenue velocity, and drill-through maps.

---

## 4. Repository Structure

```
Business-Analytics/
├── Assignment 1 Retail db.pbix    # Interactive Power BI dashboard file
├── Business Analytics.pdf         # Comprehensive technical analysis report
├── Experiment 1/                  # Experiment 1 files and documentation
├── Experiment No:2/               # Experiment 2 files
├── Experiment no:3/               # Experiment 3 files
├── Experiment No 4/               # Experiment 4 files
├── Experiment :06/                # Experiment 6 files
└── README.md                      # Project documentation
```

---

## 5. Usage & Exploration

### Viewing the Power BI Dashboard
1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
2. Open `Assignment 1 Retail db.pbix`.
3. Interact with the visual filters (Date Range, Store Location, Product Category) to explore drill-down metrics.

### Reviewing the Technical Report
- Open `Business Analytics.pdf` directly in any PDF viewer or browser to inspect the formal methodology and business conclusions.

---

## 6. Author & Academic Context

- **Author:** **Keerthi N** (*Alliance University, BCA*)
- **Subject:** Business Analytics & Intelligence
- **Verified Contribution:** Designed the Power BI data models, engineered DAX metrics, structured the 5 experimental studies, and authored the technical report.

---

## 7. License

Released under the [MIT License](https://opensource.org/licenses/MIT).
