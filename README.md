# Target Supply Chain Analytics | CCC Benchmarking + Demand Forecasting + SCF

**Course Project:** Global Supply Chain / Supply Chain Analytics (Spring 2024)  
**Author:** Shweta Prasad

## Project overview
This project analyzes Target’s supply chain performance from both an operations and finance lens.  
The goal is to connect working-capital efficiency (CCC), demand planning (forecasting), and supplier financing (reverse factoring) to real business decisions.

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

## Disclaimer
This project is for academic/portfolio purposes and is not financial advice.
