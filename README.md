# Week 2 — Water Quality Prediction (AI + Green Technology)

**Internship:** Shell–Edunet Skills4Future (Week 2: Model Selection & Building)  
**Project:** Predict water potability (safe vs unsafe) from chemical properties  
**Why:** Supports UN SDG 6 (Clean Water & Sanitation) by enabling rapid screening of water samples

## 📌 What this Week Covers
- Train/test split with stratification (preserve class balance)
- Baseline models: Logistic Regression and Random Forest
- Safe preprocessing inside pipelines (median imputation, scaling only where needed)
- Metrics reported: Accuracy, Precision, Recall, F1, ROC-AUC
- Confusion matrix visualization
- Feature importance (Random Forest)

## 🗂 Files
- `week2_water_quality.ipynb` — runnable notebook with step-by-step explanations

## 🧪 Dataset
- Expected file: `water_potability.csv` with numeric columns and a target column `Potability` (0/1).  
- Place the CSV in the same folder as the notebook or upload via Colab.

## 🛠 How to Run (Google Colab)
1. Open Colab → **File > Upload notebook** → select `week2_water_quality.ipynb`
2. Upload your `water_potability.csv` in the left Files pane (or mount Drive)
3. Run cells from top to bottom
