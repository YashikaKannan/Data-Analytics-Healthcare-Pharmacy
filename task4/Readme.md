# 📊 Task 4: Adverse Drug Reaction (ADR) Data Analysis

## 📌 Overview
This task analyzes **Adverse Drug Reaction (ADR) reports** to identify potential drug safety issues and protect patient health. Using the FDA FAERS dataset (2015–2026), we explore patient demographics, suspected drugs, reaction severity, and reporting trends to detect **safety signals**.

---

## ⚙️ Requirements
- Python 3.8+  
- Libraries: `pandas`, `matplotlib`, `seaborn`  
- Dataset: FDA Adverse Event Reports 2015–2026 (Cleaned)  

---

## 📂 Workflow
1. **Data Collection**  
   - Import ADR dataset (`fda_adverse_events_2015_2026_CLEAN.csv`).  
   - Inspect columns: report metadata, seriousness flags, demographics, drug info.  

2. **Data Cleaning**  
   - Handle mixed types with `low_memory=False`.  
   - Normalize categorical fields (`serious`, `patient_sex`, `age_group`).  

3. **KPIs**  
   - Total ADR reports.  
   - % serious ADRs.  
   - Number of suspected drugs.  
   - Reporting countries.  

4. **Exploratory Analysis**  
   - Severity distribution (pie chart).  
   - ADR counts by System Organ Class (SOC).  
   - Top drugs linked to serious ADRs.  
   - Demographics: age distribution, gender ratio.  
   - Country-wise ADR counts.  

5. **Signal Detection**  
   - Compute **Proportional Reporting Ratio (PRR)** for high-risk drugs.  
   - Flag medicines disproportionately associated with serious ADRs.  

6. **Extended Analysis**  
   - Serious vs non-serious ADR flags.  
   - Age group vs seriousness.  
   - ADR trend over time (2015–2026).  
   - Fatal ADRs by drug.  
   - Hospitalization analysis.  

---

## 📈 Insights
- **25% of ADRs are serious**, requiring close monitoring.  
- **Diclofenac** and **Metformin** show strong links to serious ADRs.  
- **Gastrointestinal disorders** are the most commonly reported ADRs.  
- ADRs are reported across **32 countries**, indicating global safety signals.  
- **Fatal and hospitalized cases** highlight drugs needing stricter pharmacovigilance.  

---

## 🚀 How to Run
1. Place the dataset (`fda_adverse_events_2015_2026_CLEAN.csv`) in your working directory.  
2. Run the notebook:  
   ```bash
   python task4_adr_analysis.py
   ```
3. Visualizations will display inline (or can be saved with `plt.savefig()` if needed).  

---

## 📌 Deliverables
- **Python Notebook (~180 lines)** for ADR analysis.  
- **Visual outputs**: pie charts, bar charts, line charts, heatmaps.  
- **README documentation** (this file) explaining objectives, workflow, and insights.  
