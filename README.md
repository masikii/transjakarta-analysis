# transjakarta-analysis
# TransJakarta Usage vs Revenue Analysis

## Overview
This project analyzes TransJakarta transaction data to understand the relationship between trip usage and paid transactions.

The main objective is to identify whether increased trip volume directly leads to higher revenue.

---

## Key Insight

> **Trip volume does not directly reflect paid transactions**

Despite high usage during peak hours and relatively long trip durations, a significant portion of trips are not associated with payments.

---

##  Analysis Breakdown

### 1. Payment Distribution
- Transactions are dominated by:
  - Rp3500 (~50%)
  - Rp0 (~45%)
- Indicates a large portion of zero-value transactions

---

### 2. Trip Duration
- Median ≈ 72 minutes
- Most trips last more than 1 hour

---

### 3. Time Pattern
- Peak usage:
  - 06:00
  - 17:00
- Usage is highly concentrated

---

### 4. Core Insight
- Paid and non-paid transactions follow similar patterns
- Both increase during peak hours
- No clear separation between paid and non-paid trips

---

##  Business Insight

This pattern may indicate the presence of:
- Subsidized trips
- Integrated fare systems

Meaning that usage does not always translate directly into revenue.

---

##  Dashboard

Tableau Dashboard:
https://public.tableau.com/app/profile/risky.adipratama/viz/TranjakartaDashboard/Dashboard1?publish=yes

## Power Point

Power Point:
https://1drv.ms/p/c/748f8658868b742d/IQA2ndYjAsN0T6qTQxNjEmq9AasrDPe5EmZinf2hXptlzYE?e=asraBa

---

##  Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Tableau
- Jupyter Notebook

---

##  Dataset
- TransJakarta transaction dataset (~37K records)

---

##  Recommendation

- Investigate zero-value transactions
- Explore revenue opportunities during peak hours
- Use both usage and payment metrics for decision-making

---

## 👤 Author
Risky Adipratama
