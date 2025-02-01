# Customer-Segmentation-KMeans

# Customer Segmentation using KMeans Clustering
A data-driven approach to segment customers based on their purchasing behavior using KMeans clustering.

# 📌 Project Overview
Customer segmentation is a key strategy for businesses to tailor marketing efforts based on different customer groups. This project applies the KMeans clustering algorithm to categorize customers based on relevant features like Monetary Value,Frequency and Recency.

## 📊 Dataset
The dataset contains customer information with features like:
- Invoice
- StockCode
- Price
- CustomerID

[DataSet Link](https://archive.ics.uci.edu/dataset/502/online+retail+ii)


## 🛠️ Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)
- Jupyter Notebook
- KMeans Clustering Algorithm

## 📈 Methodology
Exploratory Data Analysis (EDA) 🔍

- Understanding customer distribution
- Handling missing values and outliers
- Feature scaling 

## Applying KMeans Clustering 🤖

- Finding the optimal number of clusters using Elbow Method & Silhouette Score
- Training KMeans and segmenting customers
- Visualizing Segments 📊
- 2D & 3D plots of customer segments
- Insights from the segmented data
.

View the Jupyter Notebook file using the following link: [Jupyter Notebook](https://nbviewer.org/github/Krasper707/Customer-Segmentation-KMeans/blob/main/KMeans_Customer_Segmentation.ipynb)
## 📌 Results & Insights
Customers were successfully segmented into six clusters, each represented by a different color:

- 🔵 Light Blue: Low monetary value, low frequency, least recent purchases.
- 🟡 Yellow: Medium-high monetary value, medium frequency, mix of recent and old purchases.
- 🟢 Green: Medium-high monetary value, high frequency, mix of old and new recency.
- 🔴 Red: Low monetary value, low frequency, very recent purchases.
- 🔵 Dark Blue: Low-medium monetary value, medium frequency, least recent purchases.
- 🌸 Pink: Low-medium monetary value, low frequency, medium recency.

## 📌 Future Enhancements
- Try different clustering algorithms (DBSCAN, Hierarchical Clustering)
- Use Principal Component Analysis (PCA) for dimensionality reduction
- Implement customer lifetime value (CLV) prediction using ML models


