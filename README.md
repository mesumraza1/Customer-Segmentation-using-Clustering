# Customer Segmentation using Clustering

This folder contains code and resources for a customer segmentation project using clustering techniques. The analysis is performed using K-Means and Hierarchical Clustering on the Mall Customers dataset to uncover customer groupings based on features like spending score and annual income.

## Files and Directories

* `KMeans_Clustering.ipynb`: Jupyter Notebook that implements K-Means clustering for customer segmentation. It includes data preprocessing, visualization (e.g., Elbow Method), and cluster labeling.
* `Hierarchical_Clustering.ipynb`: Jupyter Notebook that implements Hierarchical Clustering (Agglomerative). It includes dendrogram plotting and cluster visualization.
* `data/Mall_Customers.csv`: Dataset used for customer segmentation. Contains features like Gender, Age, Annual Income, and Spending Score[cite: 1].

## Dataset

The project uses the **Mall Customers Dataset**, which includes:

* **CustomerID**: Unique identifier for each customer.
* **Gender**: Male or Female.
* **Age**: Age of the customer.
* **Annual Income (k$)**: Annual income in thousands of dollars.
* **Spending Score (1–100)**: Score assigned by the mall based on customer behavior and spending nature[cite: 1].

## Clustering Techniques

The project explores two clustering algorithms in detail:

* **K-Means Clustering**: Applied after using the Elbow Method to determine the optimal number of clusters. Visualizations help interpret the segmentation based on income and spending behavior.
* **Hierarchical Clustering**: Dendrograms are used to choose the number of clusters, followed by agglomerative clustering for customer segmentation[cite: 2].

## Requirements

Typical dependencies include:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

## Insights

This segmentation helps businesses understand their customer base better and develop targeted marketing strategies. Each cluster represents a unique customer profile based on their income and spending score patterns.
