# Logistic Regression Homework

## 📌 Overview
This project implements **logistic regression** for binary classification using the **Apple Quality Dataset**. It includes:
- Data Preparation
- Logistic Regression (with and without Regularization)
- Model Evaluation
- Comparison of Regularization Strengths
- ROC Curve Visualization

## 📂 Files
- `logistic_regression_notebook.ipynb`: Jupyter Notebook implementing logistic regression.
- `apple_quality.csv`: Dataset (loaded from GitHub).

## 🛠️ Setup
### 1️⃣ **Install Dependencies**
```bash
pip install pandas numpy scikit-learn matplotlib
```

### 2️⃣ **Run Jupyter Notebook**
```bash
jupyter notebook logistic_regression_notebook.ipynb
```

## 🚀 Implementation
### **1. Data Preparation**
- Load the dataset
- Handle missing values
- Standardize features
- Split into training/testing sets

### **2. Logistic Regression Implementation**
- Train logistic regression **without regularization**
- Evaluate model using:
  - Accuracy, Precision, Recall, F1-score, ROC-AUC

### **3. Logistic Regression with Regularization**
- Train models with **L2 regularization** (`C=0.1, 1, 10`)
- Compare model performance

### **4. AUC & Model Comparison**
- Compute **ROC-AUC score**
- Plot **ROC Curve** for the best model
- Visualize model performance across different regularization strengths

## 📊 Results
- Models with **C=1** perform best in terms of accuracy.
- Stronger regularization (`C=0.1`) prevents overfitting but reduces accuracy.
- Weaker regularization (`C=10`) fits better but may overfit.

## ❓ Theoretical Questions & Answers
**Q1: Why is standardization important?**
> Standardization ensures features have similar scales, improving convergence speed and model performance.

**Q2: What does regularization do?**
> Regularization reduces overfitting by penalizing large coefficients, improving generalization.

**Q3: How does `C` affect regularization?**
> Smaller `C` applies stronger regularization, increasing bias but reducing variance.

**Q4: Why is ROC-AUC used?**
> ROC-AUC measures how well the model separates classes, useful for imbalanced datasets.

**Q5: Why use logistic regression?**
> Simple, interpretable, computationally efficient, and effective for linearly separable data.

## 📜 License
This project is licensed under the **MIT License**.


## 📝 Author
- **Savana Al-shubayli**


