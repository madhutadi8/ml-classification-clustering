# 🧠 Breast Cancer Classification using Machine Learning

A mini project that predicts whether a tumor is *Malignant* or *Benign*
using two classification algorithms — Logistic Regression and Decision Tree —
with colorful evaluation charts and a side-by-side comparison.

---

## 📌 Problem Statement

Breast cancer is one of the most common cancers worldwide. Early and accurate
detection saves lives. This project uses machine learning to classify tumors
as Malignant (cancerous) or Benign (safe) based on 30 medical features.

---

## 📊 Dataset

| Property | Details |
|----------|---------|
| Name | Breast Cancer Wisconsin Dataset |
| Source | Built-in — sklearn.datasets.load_breast_cancer() |
| Samples | 569 |
| Features | 30 (radius, texture, perimeter, area, etc.) |
| Classes | 0 = Malignant, 1 = Benign |
| Null Values | None |

No download needed — dataset loads directly from sklearn.

---

## 🤖 Algorithms Used

### 1. Logistic Regression
- Used for binary classification problems
- Finds the best decision boundary between two classes
- Fast, simple, and highly interpretable

### 2. Decision Tree Classifier
- Tree-like structure that splits data based on feature values
- Easy to visualize and understand
- Handles non-linear relationships well

---

## 🛠️ Technologies Used

- *Language* — Python 3
- *Platform* — Google Colab
- *Libraries*
  - scikit-learn — ML models and metrics
  - pandas — data handling
  - numpy — numerical operations
  - matplotlib — plotting charts
  - seaborn — colorful visualizations

---

## 📈 Results

| Model | Accuracy | AUC Score |
|-------|----------|-----------|
| Logistic Regression | 97.37% ✅ | 0.9974 |
| Decision Tree | 94.74% | 0.9440 |

*Winner: Logistic Regression* with 97.37% accuracy and AUC of 0.9974

---

## 📉 Evaluation Charts

- ✅ Class Distribution Bar Chart
- ✅ Confusion Matrix — Logistic Regression (Blue)
- ✅ Confusion Matrix — Decision Tree (Green)
- ✅ ROC Curve Comparison
- ✅ Accuracy Bar Chart

---

## 🚀 How to Run

1. Open Google Colab — colab.research.google.com
2. Click New Notebook
3. Copy and paste the code from Mini_Project_Classification.ipynb
4. Run each cell from top to bottom
5. All charts will generate automatically

No dataset download required — everything runs out of the box.

---

## 📁 Project Structure
ml-mini-project/
│
├── Mini_Project_Classification.ipynb
└── README.md

## 👤 Author

*Madhavi Tadi*
Department of MCA.
Avanthi Pg COllege — 2026
