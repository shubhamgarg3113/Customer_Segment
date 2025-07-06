# 🧩 Customer Segmentation using K-Means Clustering

This project performs **customer segmentation** using unsupervised learning (K-Means clustering) on mall customer data. The goal is to group customers into different clusters based on their annual income and spending behavior.

## 📁 Dataset

* **Dataset Name**: `Mall_Customers.csv`
* **Source**: Loaded from Google Drive.
* **Key Features Used**:

  * `Annual Income (k$)`
  * `Spending Score (1–100)`

---

## 🎯 Objective

To identify distinct customer segments in order to enable targeted marketing strategies and personalized customer engagement.

---

## 🧪 Methodology

1. **Data Preprocessing**

   * Removed missing values (none found).
   * Selected relevant features: Annual Income and Spending Score.

2. **Clustering with K-Means**

   * Determined the optimal number of clusters using the **Elbow Method** (WCSS).
   * Chose 5 clusters as optimal.

3. **Visualization**

   * Used `matplotlib` to visualize clustered customer groups.
   * Different colors represent different segments.
   * Cluster centroids were plotted to show group centers.

---

## 📊 Visual Outputs

* **Elbow Plot**: Determines optimal `k` for K-Means.
* **Scatter Plot**: Shows 5 customer segments and their centroids.

---

## 🔧 Libraries Used

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `sklearn.cluster.KMeans`

---

## 📌 Insights

* Customers can be effectively grouped based on income and spending patterns.
* The clustering results can inform marketing decisions such as:

  * Targeting high spenders
  * Identifying budget-conscious shoppers
  * Personalizing product offerings per segment

---

## 🚀 Possible Extensions

* Use additional features like age and gender for deeper segmentation.
* Apply hierarchical clustering for comparison.
* Build a web app using Streamlit for interactive segmentation visualization.
