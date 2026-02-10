# EV Market Analysis (India) — Power BI Dashboards

Interactive Power BI project analyzing India’s EV landscape across **makers** and **states** to support **AtliQ Motors’** market-entry decision making.

> **Dataset Source:** This project uses the dataset provided as part of a **CodeBasics Data Challenge**.

---

## Business Problem
AtliQ Motors (USA-based EV manufacturer) is planning to expand into India, where its market share is currently **< 2%** (vs. ~25% in North America’s EV/Hybrid segment). The India leadership requested a detailed market study of the existing EV market to guide product and go-to-market strategy.

---

## Dashboards Included

### 1) EVs Sold by Makers
Focus: performance comparison across top EV manufacturers (2022–2024)
- **KPIs:** Total EVs sold, revenue (2W makers), revenue (4W makers), CAGR
- **Trends:** Monthly & quarterly sales patterns for top makers
- **Share & Ranking:** Top/Bottom makers by EVs sold + market share
- **Category Mix:** EV split by category (e.g., 2-wheelers vs 4-wheelers)
- **Growth:** CAGR view for top makers

### 2) EVs Sold by States
Focus: EV adoption, penetration, and future outlook by geography
- **KPIs:** Total vehicles sold, total EVs sold, revenue (2W/4W makers), projected EV sales (2030)
- **Projections:** 2030 projected EV sales with EV CAGR & penetration rate (Top 5 states)
- **Penetration Analysis:** Top states by penetration rate with EV sales contribution
- **Comparison:** EV sales & penetration comparison (e.g., Delhi vs Karnataka)
- **State-level Table:** EV penetration trends (2022–2024) + YoY decline indicator

---

## Interactivity & Key Controls
- **TopN selector** to dynamically change the number of items shown
- **Top/Bottom toggle** for rankings
- Cross-filtering across visuals for quick drilldowns

---

## Tech Stack
- **Power BI** (data modeling, DAX measures, interactive visuals)
- **Power Query** (data cleaning & transformations)

---

## Data Modeling Notes (High Level)
- Built measures for **EV sales, revenue, market share, YoY growth, CAGR, penetration rate**, and **2030 projections**
- Designed with performance-friendly summarizations for maker/state analysis

---

## Key Insights Enabled (Examples)
- Identify **top EV makers** and how their **market share** evolves over time  
- Compare **2W vs 4W category dominance** and revenue contribution  
- Spot **high-penetration states** and evaluate **growth vs adoption** trade-offs  
- Understand **which states are projected to lead by 2030**  

---
