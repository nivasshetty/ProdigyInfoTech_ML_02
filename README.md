# ProdigyInfoTech_ML_02
# 🧠 Task-02: Customer Segmentation with KMeans Clustering
This project is part of my Machine Learning Internship at Prodigy InfoTech.

## ✅ Objective
Segment customers into meaningful groups based on:

- Age
- Annual Income
- Spending Score

The goal is to identify clusters that help understand customer behavior for business decision-making.

---

## 📁 Files in this Repo
- kmeans_customer_segmentation.ipynb — Complete notebook with:
  - Data preprocessing
  - KMeans clustering with optimal K using Elbow Method
  - 2D and 3D visualization of clusters
  - Exported cluster summaries

- clustered_customers.csv — Cleaned data with cluster labels  
- cluster_profiles_summary.csv — Mean profiles for each cluster  

---

## 📊 Cluster Profiles (Sample Output)

| Cluster | Average Age | Average Annual Income (k$) | Average Spending Score |
|---------|-------------|----------------------------|------------------------|
| 0       | 56.91       | 54.42                      | 48.95                  |
| 1       | 32.86       | 78.55                      | 82.17                  |
| 2       | 44.00       | 90.13                      | 17.93                  |
| 3       | 21.00       | 63.23                      | 40.68                  |
| 4       | 25.00       | 25.26                      | 77.61                  |
| 5       | 45.52       | 26.29                      | 19.38                  |
| 6       | 33.41       | 53.14                      | 50.32                  |
| 7       | 32.20       | 109.70                     | 82.00                  |

### 🔍 Insights:
- *Cluster 0:* Older customers with moderate income and balanced spending.
- *Cluster 1:* Young adults, high income, high spending – ideal premium customers.
- *Cluster 2:* Middle-aged, high income, but very low spending – potential low engagement group.
- *Cluster 3:* Very young, mid-income, moderate spending – potential long-term customers.
- *Cluster 4:* Young, low income but high spending – fashion/trend-driven segment.
- *Cluster 5:* Mid-aged, low income, low spending – least priority segment.
- *Cluster 6:* Young to mid-aged, average income and spending – balanced and stable segment.
- *Cluster 7:* Young, very high income, very high spending – top VIP segment.

---

## 📌 Key Techniques Used
- 📊 KMeans Clustering (sklearn)
- 📏 Feature Scaling (StandardScaler)
- 📉 Elbow Method to determine optimal clusters
- 📌 Data visualization using matplotlib, seaborn, and mpl_toolkits for 3D plots

---

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib (2D and 3D plots)
- Jupyter Notebook

---

## 📬 Connect with Me
- 🔗 [LinkedIn](https://www.linkedin.com/in/kalyanasrinivas-bonagiri-a33709322/)
- 📧 [Email](mailto:kalyanasrinivasbonagiri@gmail.com)
