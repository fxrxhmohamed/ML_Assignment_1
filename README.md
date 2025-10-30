# 🌸 Iris Classification using KNN and Logistic Regression

This notebook explores **machine learning classification** using the famous **Iris flower dataset**, comparing the performance of **K-Nearest Neighbors (KNN)** and **Logistic Regression** models.  
It’s a hands-on demonstration of model training, scaling, evaluation, and critical reflection — all in one clean, easy-to-follow notebook.

---

## 🚀 Project Overview

This project walks through the full ML pipeline:

1. **Data Loading & Preprocessing**
   - Load the Iris dataset directly from `sklearn.datasets`.
   - Split data into **80% training** and **20% testing** sets.
   - Apply **feature scaling** using `StandardScaler` for improved performance.

2. **KNN Implementation**
   - Train multiple KNN models with different *k* values.
   - Plot **Accuracy vs. k** to visualize performance.
   - Identify and report the **optimal k** and corresponding accuracy.

3. **Logistic Regression**
   - Train a **multinomial logistic regression** model with `max_iter=1000`.
   - Display test accuracy and interpret the **model coefficients** to understand feature importance.

4. **Model Comparison**
   - Evaluate both models using:
     - Accuracy
     - Precision
     - Recall
     - F1-Score
   - Display **confusion matrices** and detailed classification reports.

5. **Critical Reflection**
   - Discuss why scaling is crucial for KNN but less critical for Logistic Regression.
   - Explain what model coefficients mean in Logistic Regression.
   - Reflect on model performance, bias-variance tradeoff, and high-dimensional feature handling.

---

## 📊 Results Summary

| Metric | KNN (k = Optimal) | Logistic Regression |
|:-------|:-----------------:|:-------------------:|
| Accuracy | **0.97** | 0.93 |
| F1-Score (Macro Avg) | **0.97** | 0.93 |
| Best For | Non-linear decision boundaries | Linear, interpretable boundaries |

✅ **KNN outperformed Logistic Regression** due to its ability to capture **non-linear relationships** between features, making it slightly more accurate on the Iris dataset.

---

## 🧠 Key Insights

- **Scaling** is critical for distance-based models like KNN.
- **KNN** adapts better to non-linear data.
- **Logistic Regression** remains powerful, interpretable, and scalable for larger datasets.
- Choosing the right model depends on **data structure**, **interpretability needs**, and **computational efficiency**.

---

## 🧩 Technologies Used

- Python 3.11  
- `scikit-learn`  
- `numpy`  
- `pandas`  
- `matplotlib`  

---

## 🎯 How to Run

1. Clone or download this repository.
2. Open the notebook:
   ```bash
   jupyter notebook ML_Notebook.ipynb
