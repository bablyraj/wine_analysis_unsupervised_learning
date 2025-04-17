# 🍷 USL - Wine Clustering & Classification

---

## 📁 About the Dataset

This dataset is adapted from the **Wine Data Set** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine), with type labels removed for **unsupervised learning** tasks.

### ⚗️ Description

The dataset includes results from a **chemical analysis** of wines grown in the same Italian region, derived from three different cultivars. The goal is to segment and classify wines based on their chemical composition.

---

## 🔬 Attributes

1. Alcohol  
2. Malic acid  
3. Ash  
4. Alcalinity of ash  
5. Magnesium  
6. Total phenols  
7. Flavanoids  
8. Nonflavanoid phenols  
9. Proanthocyanins  
10. Color intensity  
11. Hue  
12. OD280/OD315 of diluted wines  
13. Proline

---

## 🧠 Problem Statement

- Perform **unsupervised learning** to cluster wines based on chemical constituents.
- Use **supervised learning** to **predict cluster labels** derived from unsupervised methods.
- Evaluate the classification model using **Recall, Precision, and F1 Score**.

---

## ✅ Steps to Perform

### 🔹 Step 1: Research the Variables
- Understand the chemical relevance and scale of each feature (e.g., Alcohol %, Flavanoids, etc.)
- Consider their impact on wine quality and taste profiles.

---

### 🔹 Step 2: Data Preparation
- Check for missing values and outliers
- Scale numerical features (e.g., using StandardScaler or MinMaxScaler)
- Visualize distributions and relationships between features

---

### 🔹 Step 3: Apply Unsupervised Learning
- **Clustering Algorithms**:
  - K-Means
  - Hierarchical Clustering
  - DBSCAN (if needed)
- Use **Elbow Method** or **Silhouette Score** to determine the optimal number of clusters
- Apply **PCA** (Principal Component Analysis) for dimensionality reduction (optional but recommended)

---

### 🔹 Step 4: Assign Cluster Labels
- Save cluster assignments as new labels for supervised learning

---

### 🔹 Step 5: Supervised Learning

Use cluster labels as the target variable.

**Models to Try**:
- Logistic Regression
- KNN
- Random Forest
- XGBoost / LightGBM
- SVM

**Evaluate Models using**:
- **Precision**
- **Recall**
- **F1-Score**
- **Confusion Matrix**

---

### 🔹 Step 6: Insights

Document key findings, such as:
- Which chemical features were most influential in clustering?
- How well did the supervised model predict clusters?
- Were certain types of wines consistently misclassified?
- What is the ideal number of clusters based on metrics?

---

## 🎯 Outcome

By the end of this case study:
- You've used **unsupervised learning** to segment the wine dataset
- You've trained a **supervised model** to predict these segments
- You've drawn actionable **data-driven insights**

