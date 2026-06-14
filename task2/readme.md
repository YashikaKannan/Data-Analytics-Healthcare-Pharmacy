# Task 2: Healthcare Data Visualization (Pharma Dataset)

## 📌 Objective
Transform the cleaned pharmaceutical dataset into **charts and graphs** to uncover insights about product types, active ingredients, dosage strengths, and marketing categories.  
This task focuses on visual storytelling to better understand healthcare and pharma trends.

---

## 🛠 Steps Performed
1. **Load Dataset**  
   - Imported `Pharma_data_cleaned.csv` using `pandas`.  
   - Normalized column names for consistency.

2. **Product Type Distribution**  
   - Bar chart showing frequency of different `PRODUCTTYPENAME`.

3. **Proprietary Names Word Cloud**  
   - Word cloud generated from `PROPRIETARYNAME` to visualize brand name diversity.

4. **Active Ingredient Frequency**  
   - Bar chart of top 15 `SUBSTANCENAME` values to highlight most common active ingredients.

5. **Dosage Strength Distribution**  
   - Histogram of `ACTIVE_NUMERATOR_STRENGTH` to show dosage ranges.

6. **Dosage Form Distribution**  
   - Bar chart of `DOSAGEFORMNAME` to analyze how drugs are delivered (tablet, capsule, injection, etc.).

7. **Route of Administration**  
   - Bar chart of `ROUTENAME` to visualize common administration methods (oral, topical, intravenous).

8. **Marketing Category Distribution**  
   - Bar chart of `MARKETINGCATEGORYNAME` to show regulatory/marketing categories.

9. **Labeler Frequency**  
   - Bar chart of top 15 `LABELERNAME` values to identify leading pharmaceutical companies.

---

## 📊 Tools & Libraries
- **Python 3.x**
- **pandas** → data handling  
- **matplotlib** → charting  
- **seaborn** → advanced visualizations  
- **wordcloud** → text visualization  

---

## ✅ Results
- Clear visualizations of product types, dosage forms, and administration routes.  
- Identified top active ingredients and proprietary names.  
- Highlighted dosage strength distribution patterns.  
- Showed leading pharmaceutical companies and their product counts.  

---

## 📂 Outputs
- Visualizations generated directly in Jupyter Notebook / Python script.  
- Dataset used: `Pharma_data_cleaned.csv`.  
- Word cloud and multiple bar charts provide a comprehensive view of pharma trends.
