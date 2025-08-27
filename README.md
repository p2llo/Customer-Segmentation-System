Perfect 👍 Thanks for sharing the full project details.
Here’s a professional **README.md** you can upload to GitHub for your **Customer Segmentation System** project:

---

````markdown
# 🛍️ Customer Segmentation System

This project builds a **Customer Segmentation System** using **Clustering Algorithms**.  
The model groups customers into distinct segments based on their **age, annual income, and spending score**, which helps in designing **personalized marketing strategies** and improving **customer satisfaction and retention**.

---

## 📌 Features
- Data preprocessing (handling missing values, encoding, scaling)
- Dimensionality reduction check (PCA)
- **K-Means Clustering**
  - Elbow method for optimal clusters
  - 3D cluster visualization
  - Cluster distribution analysis
  - Evaluation using **Silhouette Score** & **Davies-Bouldin Score**
- **Hierarchical Clustering**
  - Dendrogram for cluster selection
  - 3D cluster visualization
  - Cluster distribution analysis
  - Evaluation using **Silhouette Score** & **Davies-Bouldin Score**
- Cluster Profiling & Customer Analysis

---

## 📂 Dataset
The dataset used is from Kaggle:  
[Customer Segmentation Dataset](https://www.kaggle.com/datasets/govindkrishnadas/segment)

- **Rows:** 1599 customers  
- **Columns:** CustomerID, Gender, Age, Annual Income (k$), Spending Score (1–100)  
- CustomerID and Gender were excluded from clustering.

---

## ⚙️ Tech Stack
- **Language:** Python 🐍
- **Libraries:**  
  - `numpy`, `pandas`, `matplotlib`
  - `scikit-learn` (KMeans, AgglomerativeClustering, PCA, metrics)
  - `scipy` (hierarchical clustering)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/p2llo/customer-segmentation-system.git
````

2. Navigate to the folder:

   ```bash
   cd customer-segmentation-system
   ```
3. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:

   ```bash
   jupyter notebook Customer_Segmentation_System.ipynb
   ```

---

## 📊 Results

### 🔹 K-Means Clustering

* **Optimal Clusters:** 4
* **Silhouette Score:** 0.283
* **Davies-Bouldin Score:** 1.14
* **Cluster Profiles:**

  * **Cluster 0:** Impulsive Spenders → Young, moderate income, high spending
  * **Cluster 1:** Wealthy Elders → Older, high income, high spending
  * **Cluster 2:** Affluent Moderates → Middle-aged, high income, moderate spending
  * **Cluster 3:** Stable Retirees → Older, moderate income, moderate spending

### 🔹 Hierarchical Clustering

* **Optimal Clusters:** 2
* **Silhouette Score:** 0.229
* **Davies-Bouldin Score:** 1.61

✅ **Final Model Selected:** **K-Means** (better performance and balanced segmentation).

---

## 📌 Future Improvements

* Apply **DBSCAN** or **Gaussian Mixture Models** for better flexibility.
* Deploy as a **Flask/Django web app** for real-time segmentation.
* Create **interactive dashboards** using **Plotly/Dash/Streamlit**.

---

