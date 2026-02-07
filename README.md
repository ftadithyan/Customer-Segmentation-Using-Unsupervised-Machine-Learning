# 🛍️ Customer Segmentation Using Unsupervised Machine Learning

---

## 📌 Project Overview
This project focuses on customer segmentation using **unsupervised machine learning techniques**.  
The goal is to group customers based on purchasing behavior and income patterns to support business decision-making

---

## 🎯 Project Objectives
- Perform Exploratory Data Analysis (EDA)
- Apply multiple clustering algorithms
- Identify the optimal clustering model
- Interpret clusters for business insights

---

## 📊 Dataset Information
- **Dataset Name:** Mall Customers Dataset
- **Number of Records:** 200
- **Features Used:**
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## 🔧 Data Preprocessing
- Checked for missing values
- Selected relevant numerical features
- Applied feature scaling using StandardScaler

---

## 📈 Exploratory Data Analysis (EDA)
- Distribution analysis of income and spending score
- Correlation analysis
- Visualization using scatter plots and box plots

---

## 🧠 Clustering Algorithms Implemented

### 🔹 K-Means Clustering
- Used Elbow Method to find optimal number of clusters
- Initialized centroids using **K-Means++**

### 🔹 Hierarchical Clustering
- Used Agglomerative Clustering
- Visualized cluster formation using dendrograms

### 🔹 DBSCAN
- Density-based clustering
- Identified noise and outliers

---

## 📊 Model Evaluation & Validation

### 🔹 Elbow Method
Used to determine the optimal number of clusters for K-Means.

### 🔹 Silhouette Score
Used to evaluate cluster quality.

| Algorithm | Silhouette Score |
|---------|------------------|
| K-Means | **0.55** |
| Hierarchical | 0.55 |
| DBSCAN | 0.35 |

---

## ✅ Best Model Selection
Based on silhouette score and visual separation, **K-Means clustering** performed best for this dataset.

---

## 🔍 Cluster Analysis & Insights
- Identified high-income high-spending customers (Premium group)
- Identified low-income low-spending customers (Budget group)
- Identified high-income low-spending customers (Potential targets)

---

## 📌 Business Use Case
Customer segmentation helps businesses:
- Design targeted marketing campaigns
- Improve customer retention
- Optimize pricing strategies

---

## 📁 Project Structure
