# 📊 Task 3: Pharma Sales Analysis

## 📌 Overview
This task analyzes **pharmaceutical sales data** from Kaggle across different time granularities (monthly, weekly, daily). The goal is to identify **medicine usage trends, revenue patterns, top‑selling categories, seasonal fluctuations, and cumulative growth**.  

We use three datasets:  
- **salesmonthly.csv** → Monthly aggregated sales (macro trends)  
- **salesweekly.csv** → Weekly aggregated sales (seasonal cycles)  
- **salesdaily.csv** → Daily sales with weekday/month breakdowns (micro patterns)  

---

## ⚙️ Requirements
- Python 3.8+  
- Libraries: `pandas`, `matplotlib`, `seaborn`  
- Kaggle dataset
---

## 📂 Scripts

### 1. Monthly Sales Analysis (`salesmonthly.csv`)
- Computes **KPIs**: total & average monthly sales per category.  
- Plots **monthly trends** with 3‑month moving averages.  
- Identifies **top categories** and visualizes category share (pie chart).  
- Generates **correlation heatmap** between drug categories.  
- Breaks down **yearly sales by category**.  
- Tracks **cumulative growth** across 2014–2019.  

### 2. Weekly Sales Analysis (`salesweekly.csv`)
- Computes **weekly KPIs**.  
- Plots **weekly sales trends** for each category.  
- Applies **4‑week rolling averages** to smooth fluctuations.  
- Visualizes **category share of weekly sales**.  
- Generates **correlation heatmap** for weekly data.  
- Aggregates **yearly totals from weekly data**.  
- Highlights **top categories by weekly sales volume**.  

### 3. Daily Sales Analysis (`salesdaily.csv`)
- Computes **daily KPIs**: total & average sales per category.  
- Plots **daily sales trends**.  
- Analyzes **average sales by weekday** (e.g., Monday vs Sunday).  
- Aggregates **monthly totals from daily data**.  
- Creates **heatmap of sales by month and year**.  
- Generates **correlation heatmap** for daily categories.  
- Visualizes **total sales by weekday** to capture seasonal patterns.  

---

## 📈 Insights
- **Macro trends (monthly)** show long‑term growth and highlight dominant categories like `N02BE` (analgesics).  
- **Seasonal cycles (weekly)** reveal fluctuations in demand, useful for inventory planning.  
- **Micro patterns (daily)** uncover weekday effects and monthly seasonality, aiding short‑term forecasting.  

---

## 🚀 How to Run
1. Place the CSV files (`salesmonthly.csv`, `salesweekly.csv`, `salesdaily.csv`) in your working directory.  
2. Run each script independently:  
   ```bash
   python task3_monthly.py
   python task3_weekly.py
   python task3_daily.py
   ```  
3. Visualizations will be displayed inline (or saved if you add `plt.savefig()` calls).  

---

## 📌 Deliverables
- **Three Python scripts** for monthly, weekly, and daily analysis.  
- **Visual outputs**: line charts, bar charts, pie charts, heatmaps.  
- **README documentation** explaining objectives, workflow, and insights.  
