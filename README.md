# 🛍️ Retail Customer Segmentation: Unsupervised Learning Analysis

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![ML](https://img.shields.io/badge/Model-K--Means%20%7C%20Hierarchical-green)](https://scikit-learn.org/)
[![Visualization](https://img.shields.io/badge/Visuals-Seaborn%20%7C%20Plotly-red)](https://plotly.com/)

## 📌 Project Overview
In retail, a "one-size-fits-all" marketing strategy is inefficient. This project applies **Unsupervised Machine Learning** to segment customers based on purchasing behavior and demographics. By identifying distinct clusters, businesses can perform **Targeted Marketing**, improve **Customer Retention**, and optimize **Product Recommendations**.

## 🧬 Key Research Questions
1. How can we group customers with similar spending patterns?
2. What is the "Optimal Number of Clusters" for this specific market?
3. What are the defining characteristics of each segment (e.g., "Big Spenders" vs. "Budget Conscious")?

## 🛠 Tech Stack
- **Data Manipulation:** Pandas, NumPy
- **Algorithms:** K-Means Clustering, Agglomerative Hierarchical Clustering
- **Evaluation:** Elbow Method, Silhouette Analysis
- **Visualization:** Matplotlib, Seaborn, 3D Plotly Clusters

## 📊 Methodology & Insights
### 1. Optimal Cluster Identification
I utilized the **Elbow Method** (Within-Cluster Sum of Squares) and **Silhouette Scores** to determine that $K=5$ provides the most distinct and stable segmentation for this dataset.



### 2. Segment Profiles
* **Cluster 0 (Target Group):** High Income, High Spending Score.
* **Cluster 1 (Sensible):** High Income, Low Spending Score.
* **Cluster 2 (Average):** Middle Income, Middle Spending.
* **Cluster 3 (Careless):** Low Income, High Spending.
* **Cluster 4 (Frugal):** Low Income, Low Spending.



## 🚀 Future Roadmap
- [ ] Implement **RFM Analysis** (Recency, Frequency, Monetary) for deeper behavioral insights.
- [ ] Integrate **Principal Component Analysis (PCA)** for high-dimensional feature reduction.
- [ ] Deploy a dynamic dashboard using **Dash** or **Streamlit**.

---
Developed by Siddharth Pal – https://www.linkedin.com/in/Siddharth-2003-Pal
