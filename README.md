# 🚀 AutoML for Small & Imbalanced Datasets

## 📌 Overview

This project implements an **Automated Machine Learning (AutoML) pipeline** designed specifically for **small and imbalanced datasets**. It integrates:

* Hyperparameter optimization using Optuna
* Class imbalance handling using SMOTE
* Multiple model selection (Random Forest, Gradient Boosting, Logistic Regression)
* Model explainability using SHAP

---

## 🎯 Problem Statement

Small datasets often lead to **overfitting**, while imbalanced datasets bias models toward majority classes. This project addresses both issues using:

* Data resampling (SMOTE)
* Automated model tuning (Optuna)
* Explainable AI (SHAP)

---

## ⚙️ Features

* ✅ Automatic model selection
* ✅ Hyperparameter tuning with 100 trials
* ✅ Imbalance handling using SMOTE
* ✅ Cross-validation based optimization
* ✅ Performance evaluation (Accuracy, Precision, Recall, F1-score)
* ✅ Model explainability using SHAP
* ✅ Visualization of optimization loss

---

## 🧠 Tech Stack

* Python
* Scikit-learn
* Optuna
* SHAP
* Matplotlib
* Imbalanced-learn

---

## 🏗️ Project Workflow

1. Load dataset (Breast Cancer dataset)
2. Preprocess data (Scaling)
3. Handle imbalance using SMOTE
4. Split dataset into train & test
5. Optimize models using Optuna
6. Train best model
7. Evaluate performance
8. Visualize trial losses
9. Explain model predictions using SHAP

---

## 📊 Results

* Best Classifier: **Gradient Boosting**
* Test Accuracy: **97.90%**
* Balanced precision & recall across classes

---

## 📷 Output Visualizations

### 🔹 Optimization Loss per Trial

(100 Optuna trials)

![Loss Graph](images/loss_plot.png)

### 🔹 SHAP Feature Importance

![SHAP Plot](images/shap_plot.png)

---

## 🛠️ Installation

```bash
git clone https://github.com/your-username/automl-imbalanced-datasets.git
cd automl-imbalanced-datasets
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python main.py
```

---

## 📁 Project Structure

```
AutoML-Imbalanced/
│
├── main.py
├── requirements.txt
├── README.md
├── images/
│   ├── loss_plot.png
│   ├── shap_plot.png
│   └── results.png
```

---

## 📈 Sample Output

```
Best Classifier: GradientBoosting
Accuracy: 97.90%

Precision: 0.98
Recall: 0.98
F1 Score: 0.98
```

---

## 🔍 Explainability

SHAP values help understand:

* Which features influence predictions
* Positive/negative contribution of features
* Model transparency

---

## 🚀 Future Improvements

* Add deep learning models
* Deploy as web app (Streamlit)
* Add more datasets
* Use advanced imbalance techniques (ADASYN)
* Add model comparison dashboard

---

## 👨‍💻 Author

BALAJI A D J & ASHAAZ AHMED KHAN A

---

## ⭐ If you like this project, give it a star!
