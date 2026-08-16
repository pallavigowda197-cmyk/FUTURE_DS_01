# Superstore Sales & Profitability Analysis

A business sales analysis built for a Data Science & Analytics internship task —
cleaning raw sales data, analyzing revenue trends, and building a client-ready
dashboard with actionable business recommendations.

## 🎯 Objective

Analyze retail sales data to answer the core questions a real business stakeholder
would ask:

- Which products generate the most revenue?
- How do sales change over time?
- Which categories or regions are most profitable?
- Where should the business focus to grow faster?

## 🗂️ Dataset

**[Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)**
— 9,994 order line items / 5,009 unique orders, Jan 2014–Dec 2017, covering
Sales, Profit, Discount, Category, Sub-Category, Region, and Segment.

The raw file is included at [`data/Sample - Superstore.csv`](data/Sample%20-%20Superstore.csv).

## 🛠️ Tools Used

- **Microsoft Excel** — data cleaning, formula-driven analysis (`SUMIF`, `SUMPRODUCT`), charts

## 📊 Deliverable

**[`Superstore_Sales_Dashboard.xlsx`](Superstore_Sales_Dashboard.xlsx)** — a 3-tab workbook:

| Tab | Contents |
|---|---|
| **Raw Data** | Full cleaned dataset, formatted as an Excel Table |
| **Dashboard** | KPI summary, Sales & Profit by Category / Region / Segment, Top 10 Sub-Categories, Monthly Sales Trend (2014–2017) — all built with live formulas and charts |
| **Insights & Recommendations** | Written analysis answering each business question, with concrete recommendations |

All dashboard figures are **live formulas** referencing the raw data, so they
recalculate automatically if the underlying data changes.

## 📈 Key Findings

- **Total Sales:** $2.30M &nbsp;|&nbsp; **Total Profit:** $286K &nbsp;|&nbsp; **Margin:** 12.5% &nbsp;|&nbsp; **Orders:** 5,009
- **Technology** is the strongest category (17.4% margin), led by Phones and Copiers.
- **Furniture** sells well ($742K) but is barely profitable (2.5% margin) — Tables and
  Bookcases are sold at a loss due to heavy discounting.
- Revenue grew **51%** from 2014 ($484K) to 2017 ($733K), with a consistent Q4 seasonal spike.
- **West** and **East** regions lead on margin; **Central** lags at 7.9%, pointing to
  excess discounting.

## 💡 Recommendations

1. Tighten discount limits on Tables and Bookcases to recover an estimated $20K in lost profit.
2. Prioritize marketing and inventory investment in Technology (Phones, Copiers).
3. Investigate discounting practices in the Central region.
4. Plan inventory/staffing around the Q4 demand spike; use Q1 for promotions.

*(Full detail in the Insights & Recommendations tab.)*

## 🚀 How to Use

1. Download `Superstore_Sales_Dashboard.xlsx`.
2. Open in Excel — the **Dashboard** tab is the main view.
3. Explore the **Raw Data** tab or edit it; all dashboard formulas recalculate automatically.
