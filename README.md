# 🛍️ Customer Segmentation with Unsupervised Learning

This project applies K-Means and DBSCAN clustering algorithms to segment mall customers based on purchasing behavior. Using the **Mall_Customers.csv** dataset, the analysis identifies natural groups to support marketing decisions and customer insights.

---

## 📌 Project Overview

The goal of this project is to explore customer purchasing patterns using unsupervised machine learning.  
By applying clustering algorithms, we aim to answer:

- Are there natural groups of customers?
- What characterizes each group?
- How do different clustering methods compare?

---

## 📂 Dataset Description

The dataset contains **200 mall customers**, including:

- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1–100)

These features make the dataset ideal for clustering and segmentation tasks.

---

## 🧠 Methods & Algorithms Used

### **1. Data Preprocessing**
- Handling missing values  
- Feature scaling (StandardScaler / MinMaxScaler)  
- Optional PCA for dimensionality reduction  

---

### **2. K-Means Clustering**
- Used to form *k* groups based on similarity  
- Determined optimal k using:
  - Elbow Method  
  - Silhouette Score  

---

### **3. DBSCAN Clustering**
- Density-based algorithm  
- Handles outliers and irregular cluster shapes  
- Parameters tuned: `eps` and `min_samples`

---

### **4. Evaluation Metrics**
- Silhouette Score  
- Visual analysis using PCA scatter plots and cluster graphs  

---

## 📊 Results Summary

**K-Means:**
- Identified clear and well-separated clusters  
- Achieved a strong silhouette score  
- Effective due to spherical nature of dataset clusters  

**DBSCAN:**
- Detected noise (outliers)  
- Captured dense regions  
- Highly sensitive to scaling and parameters  

---

## 📌 Key Insights

- Customer segmentation enhances data-driven marketing.
- K-Means performs well on well-separated clusters.
- DBSCAN is powerful for detecting density-based clusters and noise.
- Using both models provides a deeper and more comprehensive understanding of customer groups.

---

## 📝 Conclusion

This project demonstrates how unsupervised learning reveals hidden patterns in customer behavior.  
The insights gained can support targeted marketing, recommendation systems, and improved customer experience strategies.

## 🗂️ Project Structure

