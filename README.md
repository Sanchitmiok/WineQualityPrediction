# 🍷 Wine Quality Prediction using XGBoost + SHAP Interpretability

This project uses machine learning to **predict the quality of red wine** based on its physicochemical properties. Built around the **XGBoost classifier**, the model achieves **96.11% accuracy** on the UCI Red Wine Dataset and includes **SHAP (SHapley Additive exPlanations)** for feature-level interpretability.

> 📄 This work was also compiled into a research paper for academic conference submission.

---

## 📌 Key Highlights

- ✅ Dataset: UCI Red Wine Quality Dataset (1,599 samples, 11 features)
- ✅ Accuracy: **96.11%** using XGBoost
- ✅ Explainability: SHAP used to identify most influential features
- ✅ Feature Importance: Alcohol, Volatile Acidity, Sulphates were top predictors
- ✅ Model Comparison: Compared with Random Forest, SVM, and Logistic Regression

---

## 📊 Technologies & Tools Used

- **Python**
- **XGBoost**
- **SHAP**
- **scikit-learn**
- **Pandas**, **NumPy**, **Matplotlib**
- (Optional: `Streamlit` or `Flask` for deployment if applicable)

---

## 🔬 Problem Statement

Traditional wine quality testing is done via human tasters – a subjective, slow, and inconsistent process. This project aims to automate and **objectively predict wine quality** using ML models trained on chemical composition data.

---

## 🧠 ML Models Trained

| Model                | Accuracy   | F1-Score Range |
|---------------------|------------|----------------|
| Logistic Regression | 88.49%     | 0.86 – 0.90    |
| SVM (RBF Kernel)    | 91.25%     | 0.89 – 0.93    |
| Random Forest       | 94.00%     | 0.92 – 0.95    |
| **XGBoost (Best)**  | **96.11%** | **0.95 – 0.97**|

---

## 📈 SHAP Feature Visualization

![SHAP Summary Plot](./assets/shap_summary.png)  
*Alcohol, Sulphates, and Volatile Acidity had the highest impact on wine quality prediction.*

---

## 🗃️ Dataset

- UCI Red Wine Quality Dataset  
- Source: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/wine-quality-xgboost.git
cd wine-quality-xgboost
pip install -r requirements.txt
python wine_model.py
