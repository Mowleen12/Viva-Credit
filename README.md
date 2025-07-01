# 🌳 Viva Credits – Decision Tree Classifier Optimization

This project focuses on building and optimizing a **Decision Tree Classifier** to predict binary class labels. The model is trained and validated using **cross-validation** and **hyperparameter tuning (GridSearchCV)** to improve its generalization performance on synthetic classification data.

---

## 🧠 Problem Statement

> Build and optimize a Decision Tree Classifier to predict binary class labels using cross-validation and hyperparameter tuning.

---

## 🗃️ Dataset

This project uses a **synthetic classification dataset** generated using `sklearn.datasets.make_classification`. The dataset contains:

- **1000 samples**
- **20 features**
- **2 classes** (binary classification: 0 or 1)

Features include a mix of informative and redundant variables designed to simulate real-world scenarios.

---

## 🛠️ Technologies Used

- **Python**
- **Scikit-learn** – Machine learning models, cross-validation, and tuning
- **NumPy**, **Pandas** – Data handling
- **Matplotlib** (optional) – Visualization (not included in code snippet)

---

## 🤖 Model Used

### 🔹 Decision Tree Classifier
- A supervised learning algorithm that splits data based on feature conditions.
- Optimized using **GridSearchCV** to find the best values for:
  - `max_depth`
  - `min_samples_split`
  - `criterion`

### 🔍 Cross-Validation
- Performed using `cross_val_score` for model robustness and to reduce overfitting risk.

---

## 📈 Evaluation Metric

The model is evaluated using **accuracy score** as the primary metric.  
You can also consider `precision`, `recall`, or `F1-score` depending on class imbalance.
