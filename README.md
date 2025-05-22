# 🛍️ Mall Customer Segmentation using KMeans Clustering

This project applies KMeans Clustering on a mall customer dataset to segment customers into distinct groups based on their **Age**, **Annual Income**, and **Spending Score**. These insights can help businesses tailor marketing strategies for different customer segments.

---

## 📁 Dataset

**File:** `Mall_Customers.csv`

**Features Used:**
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

**Features Dropped:**
- `CustomerID`
- `Gender` (for simplicity in clustering)

---

## 🧠 Techniques Used

- **Data Preprocessing** with `pandas`
- **Feature Scaling** using `StandardScaler`
- **KMeans Clustering** via `scikit-learn`
- **Elbow Method** to determine the optimal number of clusters
- **Cluster Analysis** to understand customer types

---

## 🛠️ Installation

Make sure you have the required packages installed:

```bash
pip install pandas scikit-learn matplotlib
