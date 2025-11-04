# ML-Experiments-Heart-Disease
# 🫀 Machine Learning Experiments on Heart Disease Dataset

This repository contains Experiments **5 to 9** based on the Cleveland Heart Disease Dataset.  
These experiments explore clustering, dimensionality reduction, sequence modeling, decision trees, and ensemble methods to predict or understand heart disease risk.

---

## 📊 Dataset

**Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
**File Used:** `heart.csv`  
Contains 14 key medical attributes:
- Age, Sex, Chest Pain Type (cp), Resting Blood Pressure (trestbps), Serum Cholesterol (chol),  
  Fasting Blood Sugar (fbs), Resting ECG (restecg), Max Heart Rate (thalach),  
  Exercise Induced Angina (exang), Oldpeak, Slope, CA, Thal, and Target (0 = No Disease, 1 = Disease).

---

## 🧪 Experiments Overview

### **Experiment 5 – Clustering (K-Means, Gaussian Mixture, Hierarchical)**
- Goal: Group patients based on medical features without using labels.
- Algorithms: `KMeans`, `GaussianMixture`, `AgglomerativeClustering`
- Visualization: PCA-based 2D cluster comparison.
- 📎 https://colab.research.google.com/drive/1Rm5otJvZFjpdvoNUqsOOEDpyv685JXeJ?usp=sharing

---

### **Experiment 6 – Principal Component Analysis (PCA)**
- Goal: Reduce dimensionality and visualize important features.
- Output: 2D PCA scatter plot colored by heart disease target.
- 📎 https://colab.research.google.com/drive/16So9ZOWGftguUHWQAoKUN-b5re_IHTGO?usp=sharing

---

### **Experiment 7 – Hidden Markov Model (HMM)**
- Goal: Model patient progression patterns using `age` and `thalach`.
- Tool: `hmmlearn` GaussianHMM with 3 hidden states.
- Output: Hidden states and generated sample sequences.
- 📎https://colab.research.google.com/drive/1ntUM7SRFJ3lCFLmJ60iieEsr8q5D0xG7?usp=sharing

---

### **Experiment 8 – CART (Decision Tree Classification)**
- Goal: Predict heart disease presence using Decision Tree (Gini Criterion).
- Output: Decision tree visualization, accuracy score.
- 📎 https://colab.research.google.com/drive/1_JYeQDpjLbr6xarqcnlqiWhyd3qJv29f?usp=sharing
---

### **Experiment 9 – Ensemble Learning (Random Forest & AdaBoost)**
- Goal: Improve classification using ensemble techniques.
- Metrics: Accuracy, Precision, Recall, F1-score.
- 📎 https://colab.research.google.com/drive/1RwbQtA4zjC14OFM4U9F7IJGmsePCN08q?usp=sharing

---

## 🧰 Tools & Libraries Used
- Python 3.10+
- Google Colab
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `hmmlearn`
