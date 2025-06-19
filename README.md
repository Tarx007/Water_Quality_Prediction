# 💧 Water Quality Prediction using Machine Learning

This project predicts multiple water quality parameters using a machine learning model built with `MultiOutputRegressor` and `RandomForestRegressor`.

---

## 📌 Project Overview

Access to clean water is a global challenge. Predicting the concentration of various water pollutants can help identify unsafe conditions early and enable timely intervention.

This project was developed as part of the **AICTE Virtual Internship sponsored by Shell (June 2025)**.

---

## 🛠 Technologies Used

- **Python 3.12**
- **Pandas, NumPy** – Data handling
- **Scikit-learn** – Machine learning modeling
- **Matplotlib, Seaborn** – Data visualization
- **Jupyter Notebook / Google Colab**

---

## 🎯 Problem Statement

Predict the following water quality parameters from time-based water sample data:

- NH₄ (Ammonium)
- BSK5 (BOD5)
- Suspended Solids (Colloids)
- O₂ (Dissolved Oxygen)
- NO₃ (Nitrate)
- NO₂ (Nitrite)
- SO₄ (Sulfate)
- PO₄ (Phosphate)
- CL (Chloride)

---

## 🔍 Dataset

- Format: `CSV` (semicolon-separated)
- Source: Provided during AICTE internship
- Preprocessing: Converted to tabular format, missing values handled

---

## 🧠 Model

A `MultiOutputRegressor` wraps around a `RandomForestRegressor` to perform **multi-target regression**.

### Evaluation Metrics:

- **R² Score**
- **Mean Squared Error (MSE)**

---

## 📊 Results

| Parameter | R² Score (approx.) |
|-----------|-------------------|
| NH₄       | 0.65              |
| SO₄       | 0.73              |
| CL        | 0.75              |
| NO₂       | -1.66             |

> Some parameters performed well, while others need better features for higher accuracy.

---

## 🚀 How to Run

### ✅ On Google Colab:
1. Open the notebook in Colab
2. Upload `water.csv` when prompted
3. Run all cells to train and evaluate the model

### ✅ On Local Machine:
1. Clone the repo
2. Ensure `water.csv` is in the same directory
3. Run `water_quality_prediction.py` or open `.ipynb` in VS Code/Jupyter

---

## 📂 Folder Structure

