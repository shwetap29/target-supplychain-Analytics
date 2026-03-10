# Target Supply Chain Analytics | CCC Benchmarking + Demand Forecasting + SCF

**Course Project:** Global Supply Chain / Supply Chain Analytics (Spring 2024)  
**Author:** Shweta Prasad

# 🚚 Target Corporation — Supply Chain Analytics

> Analysing supply chain efficiency, demand forecasting, and financial performance for one of the US's largest retailers using real-world financial data and Python-based analytics.

---

## 📌 Project Overview

This project examines Target Corporation's supply chain health through three analytical lenses — **cash conversion efficiency**, **demand forecasting**, and **supply chain finance** — to identify operational strengths, risks, and improvement opportunities.

## What I built

### 1) Cash Conversion Cycle (CCC) benchmarking
I benchmarked Target against key retail/pharmacy competitors using:
- **DIO** (Days Inventory Outstanding)
- **DSO** (Days Sales Outstanding)
- **DPO** (Days Payables Outstanding)
- **CCC = DIO + DSO − DPO**

**Data source note:** Financial inputs should be taken from official company filings (SEC EDGAR 10-K / annual reports) to avoid paywalled sources.

### 2) Demand forecasting (time-series)
Using weekly sales demand data:
- Built a forecasting workflow using **SARIMAX**
- Used a **time-based split** (first ~80% train, last ~20% test)
- 
**Business use:** The forecast supports inventory and replenishment planning (e.g., anticipating demand spikes and reducing stockouts/overstock).

### 3) Reverse factoring / Supply Chain Finance (SCF)
I evaluated whether reverse factoring could benefit suppliers while maintaining Target’s working-capital advantage, considering the relative cost of capital.

## Repository structure
- `notebooks/` → Analysis notebook (forecasting + CCC work)
- `slides/` → Final presentation deck
- `docs/` → Business case prompt
- `data/` → Datasets used

Built as part of my MS Business Analytics program at Sacred Heart University (Spring 2024).

---

## 🎯 Business Questions Answered

- How efficiently is Target converting inventory into cash compared to industry benchmarks?
- What demand patterns exist across product categories, and how predictable are they?
- Where are the biggest working capital risks in Target's supply chain?
- How does Target's supply chain financial performance compare to Walmart and Amazon?

---

## 🛠️ Tools & Tech Stack

| Tool | Purpose |
|---|---|
| `Python (pandas, numpy)` | Data wrangling, calculations, analysis |
| `matplotlib / seaborn` | Data visualisation |
| `Jupyter Notebook` | Analysis environment |
| `Excel` | Source data preparation |

---

## 📊 Key Analysis Areas

**1. Cash Conversion Cycle (CCC) Benchmarking**
- Calculated Days Sales Outstanding (DSO), Days Inventory Outstanding (DIO), Days Payable Outstanding (DPO)
- Benchmarked Target's CCC against Walmart and Amazon
- Identified working capital efficiency gaps and opportunities

**2. Demand Forecasting**
- Analysed seasonal demand patterns across product categories
- Built trend models to support inventory planning decisions
- Flagged high-volatility categories as replenishment risk areas

**3. Supply Chain Finance Analysis**
- Examined the relationship between inventory levels, supplier payment terms, and cash flow
- Identified periods of supply chain stress and their financial impact

---

## 📁 Repo Structure

```
target-supplychain-Analytics/
│
├── data/                  ← Source datasets (financial & operational)
├── notebooks/             ← Jupyter notebooks with full analysis
├── visualizations/        ← Charts and dashboard outputs
└── README.md
```

---

## 💡 Skills Demonstrated

`Supply Chain Analytics` · `Financial Ratio Analysis` · `Demand Forecasting` · `Python (pandas)` · `Data Visualisation` · `Benchmarking` · `Business Insight Storytelling` · `Jupyter Notebooks

## Disclaimer
This project is for academic/portfolio purposes and is not financial advice.
