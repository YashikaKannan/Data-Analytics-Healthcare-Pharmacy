# Task 2: Healthcare Data Visualization

## 📌 Objective
Transform cleaned healthcare data into **charts and graphs** to uncover insights and support better decision‑making.  
Focus areas:
- Disease distribution  
- Age distribution  
- Gender ratio  
- Medication usage  

---

## 🛠 Steps Performed
1. **Load Cleaned Dataset**  
   - Imported `Pharma_data_cleaned.csv` using `pandas`.

2. **Age Distribution**  
   - Histogram of patient ages.  
   - Grouped patients into age ranges (0–18, 19–35, 36–50, 51–65, 65+).  
   - Boxplot of age by disease.

3. **Gender Ratio**  
   - Pie chart showing male vs female patient percentages.

4. **Disease Distribution**  
   - Horizontal bar chart of patient counts per disease.  
   - Stacked bar chart showing disease distribution by gender.

5. **Medication Usage**  
   - Pie chart of medication usage percentages.  
   - Bar chart of total dosage per medication.

6. **Advanced Visualizations**  
   - Correlation heatmap (Age vs Dosage).  
   - Scatterplot of Age vs Dosage by disease.  
   - Pairplot for numeric columns.  
   - Heatmap of medication usage by age group.  
   - (Optional) Word cloud for disease names.

---

## 📊 Tools & Libraries
- **Python 3.x**
- **pandas** → data handling  
- **matplotlib** → charting  
- **seaborn** → advanced visualizations  
- *(Optional)* **wordcloud** → text visualization  

---

## ✅ Results
- Clear visualizations of patient demographics, disease prevalence, and medication usage.  
- Identified trends such as most common diseases, medication usage patterns, and age group distributions.  
- Advanced plots (heatmaps, scatterplots, pairplots) provide deeper insights into relationships between variables.  

---

## 📂 Outputs
- Visualizations generated directly in Jupyter Notebook / Python script.  
- Cleaned dataset from Task 1 (`Pharma_data_cleaned.csv`) used as input.  
- Optional summary report can be extended with visualization insights.
