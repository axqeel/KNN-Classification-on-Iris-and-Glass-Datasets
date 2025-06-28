# K-Nearest Neighbors Classification on Iris and Glass Datasets

This repository implements **K-Nearest Neighbors (KNN) Classification** using Python and `scikit-learn` on:
- The **Iris Dataset** (predicting species of flowers).
- The **Glass Dataset** (classifying types of glass).

---

## 🌻 What is K-Nearest Neighbors (KNN)?

**K-Nearest Neighbors** is:
- A simple, non-parametric, supervised learning algorithm used for **classification and regression**.
- It classifies a data point based on how its neighbors are classified.
- The **parameter `k`** determines the number of nearest neighbors to consider when assigning a class.

---

## 🚀 Features

✅ Loads **Iris and Glass datasets**.  
✅ Splits data into **features (`X`) and target (`y`)**.  
✅ Uses a **70%-30% train-test split** for both datasets.  
✅ Trains **KNN Classifiers (`k=5`)** on each dataset.  
✅ Evaluates performance using:
- **Classification report (precision, recall, f1-score)**
- **Accuracy score (%)**

---

## 🗂️ Datasets

### 🌼 Iris Dataset
Contains measurements of:
- Sepal length
- Sepal width
- Petal length
- Petal width

**Target:** Flower species (`setosa`, `versicolor`, `virginica`).

---

### 🔍 Glass Dataset
Contains chemical analysis of glass samples with features:
- Refractive index
- Chemical components (Na, Mg, Al, Si, K, Ca, Ba, Fe)

**Target:** Glass type (e.g., building windows, vehicle windows, containers).

---

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies using:
```bash
pip install pandas numpy scikit-learn
