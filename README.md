# OIB-SIP
Data science
# 🌸 Iris Flower Classification Model

The *Iris Flower Classification Model* is a classic example of a *supervised machine learning* classification task. This project uses the well-known *Iris dataset*, which contains measurements of iris flowers from three different species.

## 📌 Objective

To build a machine learning model that can accurately *classify iris flowers* into one of three species — *Setosa, **Versicolor, and **Virginica* — based on four numerical features:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

---

## 📊 Dataset Overview

- *Samples:* 150
- *Features:* 4 numerical attributes
- *Classes:* 3 (Setosa, Versicolor, Virginica)

The dataset is included in *scikit-learn* and is a standard benchmark for classification problems.
---

## 🛠️ Tools & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for machine learning models)

---

## 🔍 Exploratory Data Analysis (EDA)

Performed EDA to:
- Understand feature distributions
- Visualize relationships between features using scatter plots and pair plots
- Detect class separability

---

## 🤖 Models Implemented

Implemented and compared the performance of the following classification models:

- *Logistic Regression*
- *K-Nearest Neighbors (KNN)*
- *Decision Tree*
- *Support Vector Machine (SVM)*

---

## 🧠 Model Evaluation

Evaluation metrics used:
- Accuracy Score
- Confusion Matrix
- Classification Report

The dataset was split into *training and testing sets* to validate the model's generalization performance.

---

## ✅ Results

All models showed high accuracy, especially on this well-structured dataset.

---

## 📁 Project Structure
The dataset is included in *scikit-learn* and is a standard benchmark for classification problems.
iris-flower-classification/
│
├── iris_classification.ipynb       # Main Jupyter notebook
├── iris_dataset.csv                # Dataset (optional if not using sklearn’s load function)
├── images/                         # Visualizations and plots
└── README.md                       # Project documentation
