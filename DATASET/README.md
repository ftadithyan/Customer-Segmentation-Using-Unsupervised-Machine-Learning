## 📊 Dataset Description

The dataset contains customer demographic and behavioral information collected for the purpose of customer segmentation using unsupervised learning techniques.

Each row represents an individual customer, and the columns describe their attributes and assigned cluster labels.

---

### 🔹 Dataset Columns

- **CustomerID**  
  Unique identifier assigned to each customer.

- **Gender**  
  Gender of the customer (Male / Female).

- **Age**  
  Age of the customer in years.

- **Annual Income (k$)**  
  Annual income of the customer measured in thousands of dollars.

- **Spending Score (1–100)**  
  A score assigned by the business based on customer purchasing behavior and spending patterns.  
  Higher values indicate higher spending engagement.


### 📌 Target Variables
This is an **unsupervised learning problem**, so there is **no target variable**.  
The goal is to discover natural groupings within the data.

---

### 🧠 Feature Selection for Clustering
The following numerical features were primarily used for clustering:
- Age
- Annual Income (k$)
- Spending Score (1–100)

All selected features were scaled before applying clustering algorithms.

---

### 📈 Dataset Usage
The dataset is used to:
- Perform exploratory data analysis (EDA)
- Apply and compare multiple clustering algorithms
- Evaluate clustering performance using silhouette score
- Derive meaningful customer segments for business insights

---

### ✅ Data Quality
- No missing values detected
- Numerical features are continuous
- Suitable for distance-based clustering methods such as K-Means and Hierarchical Clustering
