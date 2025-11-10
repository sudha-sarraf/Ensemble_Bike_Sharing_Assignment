# DA5401 – Assignment 8: Ensemble Learning for Bike Sharing Demand

**Name:** Sudha Sarraf  
**Roll Number:** ns25z247

---

## 📘 Assignment Overview

This assignment focuses on implementing and comparing various **ensemble learning techniques** for predicting hourly bike-sharing demand using the **UCI Bike Sharing Dataset** (`hour.csv`).

The primary objective is to understand how different ensemble methods — **Bagging, Boosting, and Stacking** — improve model performance compared to single baseline models by addressing the **bias–variance trade-off**.

---

## 🧠 Models Implemented

1. **Baseline Single Model**
   - Decision Tree Regressor and Linear Regression (best used as baseline)
2. **Bagging Regressor**
   - Variance reduction through bootstrap aggregation
3. **Gradient Boosting Regressor**
   - Bias reduction through sequential learning
4. **Stacking Regressor**
   - Combination of diverse models using Ridge Regression as meta-learner

---

## 📊 Evaluation Metric

All models were evaluated using the **Root Mean Squared Error (RMSE)** on the test set.  
A comparative table was created to identify the best-performing model.

**Best Model:** *Stacking Regressor*  
**Key Reason:** It effectively combines diverse learners to minimize both bias and variance, resulting in the lowest RMSE.

---

## 🧩 Files Included

- `Ensemble_Bike_Sharing_Assignment.ipynb` – Complete Jupyter Notebook with code, visualizations, and results  
- `README.md` – Short description and submission details  
- `hour.csv` – Dataset (from UCI Machine Learning Repository)

---

## 📚 Dataset Source

UCI Machine Learning Repository – [Bike Sharing Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00275/Bike-Sharing-Dataset.zip)

---

## 🏁 How to Run

1. Ensure that `hour.csv` is placed in the same folder as the notebook.  
2. Open `Ensemble_Bike_Sharing_Assignment.ipynb` in Jupyter Notebook or Google Colab.  
3. Run all cells sequentially from top to bottom.  
4. The notebook will:
   - Preprocess the dataset  
   - Train all models  
   - Compare RMSEs  
   - Display final evaluation and conclusion

---


