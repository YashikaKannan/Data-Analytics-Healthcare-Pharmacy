# 📊 Task 5: Healthcare Predictive Analytics — Heart Disease Prediction

## 📌 Overview
This task applies **predictive analytics** to healthcare data, focusing on **heart disease classification**. Using the [Heart Disease Dataset (Kaggle)](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset), we build machine learning models to predict whether a patient is likely to have heart disease based on clinical and lifestyle features.

---

## ⚙️ Requirements
- Python 3.8+  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`  
- Dataset: heart.csv

---

## 📂 Workflow
1. **Data Collection**  
   - Import `heart.csv` dataset with patient attributes (age, sex, chest pain type, blood pressure, cholesterol, ECG results, max heart rate, exercise data, thal, etc.).  

2. **Exploratory Data Analysis (EDA)**  
   - Target distribution visualization.  
   - Correlation heatmap of features.  
   - Feature distribution plots (age, cholesterol, heart rate).  

3. **Data Preprocessing**  
   - Standardize continuous features.  
   - Train/test split (70/30).  

4. **Model Building**  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  
   - Support Vector Machine (SVM)  
   - K-Nearest Neighbors (KNN)  
   - Ensemble Voting Classifier  

5. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1‑Score.  
   - Confusion Matrix.  
   - ROC Curve & AUC comparison.  
   - Cross-validation scores.  

6. **Insights & Predictions**  
   - Feature importance ranking (Random Forest).  
   - Predict disease likelihood for new patients.  
   - Save trained model (`random_forest_heart_model.pkl`).  

---

## 📈 Results
- **Random Forest** achieved ~85–90% accuracy with strong recall.  
- **Gradient Boosting** and **SVM** also performed competitively.  
- **Age, cholesterol, chest pain type, and thal** emerged as top predictors.  
- ROC curves show strong separation (AUC ~0.90).  
- Ensemble Voting Classifier improved stability across metrics.  

---

## 🚀 How to Run
1. Place `heart.csv` in your working directory.  
2. Run the notebook:  
   ```bash
   python task5_heart_prediction.py
   ```
3. Visualizations will display inline.  
4. Saved model (`random_forest_heart_model.pkl`) can be loaded for deployment.  
