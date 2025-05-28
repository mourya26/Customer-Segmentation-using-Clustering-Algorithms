# 📊 Customer Segmentation using Clustering Algorithms  

## 🚀 Project Overview  
This project aims to segment customers based on their purchasing behavior and demographics using **unsupervised machine learning techniques**. We applied **K-Means, Hierarchical Clustering, and DBSCAN** to identify distinct customer groups and optimize marketing strategies.  

---

## 🔍 Dataset  
- The dataset contains customer demographics, spending habits, and product purchase history.  
- **Feature Selection & Engineering** was performed to enhance clustering performance.
- Dataset link : https://www.kaggle.com/code/karnikakapoor/customer-segmentation-clustering
  
---

🏆 Clustering Techniques Used  
1️⃣ **K-Means Clustering**  
   - Optimized number of clusters using **Elbow Method & Silhouette Score**.  
   - Evaluated using **Davies-Bouldin Score & Calinski-Harabasz Index**.  

2️⃣ **Hierarchical Clustering**  
   - Visualized clusters using a **dendrogram**.  
   - Compared linkage methods (**ward, complete, single**).  

3️⃣ **DBSCAN (Density-Based Clustering)**  
   - Detected noise points & high-density clusters.  
   - Tuned `eps` and `min_samples` parameters for best results.  

---

## 📊 Evaluation Metrics  
✅ **Silhouette Score** → Measures cluster compactness & separation. (Higher is better)  
✅ **Davies-Bouldin Score** → Measures cluster compactness. (Lower is better)  
✅ **Calinski-Harabasz Index** → Measures variance ratio between & within clusters. (Higher is better)  

| Algorithm  | Silhouette Score ↑ | Davies-Bouldin ↓ | Calinski-Harabasz ↑ |
|------------|-----------------|-----------------|-----------------|
| **K-Means**  | 0.4077  | 1.4911  | 1181.1550  |
| **Hierarchical**  | **0.4339**  | 1.6704  | 1071.6032  |
| **DBSCAN**  | 0.3706  | **1.7422 (Worst)**  | **91.97 (Worst)**  |

---

## 🔹 Best Algorithm for Customer Segmentation  
✔ **K-Means performed the best** due to balanced performance across all metrics.  
✔ **Hierarchical Clustering** achieved the highest **Silhouette Score** but lacks scalability.  
❌ **DBSCAN struggled** due to varying densities in the dataset.  

## 🔧 Technologies Used  
- Python 🐍  
- Pandas & NumPy 📊  
- Matplotlib & Seaborn 📈  
- Scikit-learn 🤖  
- Jupyter Notebook 📓  

---

## 📌 Next Steps  
- 🔹 **Hyperparameter tuning for K-Means & DBSCAN**  
- 🔹 **Feature scaling & PCA for improved clustering**  
- 🔹 **Deploying customer segmentation insights for marketing strategies**  

---

## 📜 How to Run the Project  
1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/mourya26/Customer-Segmentation-using-Clustering-Algorithms.git
   cd customer-segmentation
