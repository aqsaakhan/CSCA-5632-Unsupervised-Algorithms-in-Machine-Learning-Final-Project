# Online Retail Customer Segmentation - Unsupervised Learning Project
#### Aqsa Anwar
**[GitHub Repository](https://github.com/aqsaakhan/CSCA-5632-Unsupervised-Algorithms-in-Machine-Learning-Final-Project)**

## 1. Introduction
This project serves as the final project for my **"[Unsupervised Algorithms in Machine Learning](https://github.com/aqsaakhan/CSCA-5632-Unsupervised-Algorithms-in-Machine-Learning-Final-Project)"** course. In this project, I aim to use unsupervised learning techniques to segment customers of an online retail business. I'll uncover patterns in customer behavior and preferences that can inform targeted marketing strategies and personalized customer engagement.

In today's highly competitive e-commerce landscape, understanding and effectively engaging with customers is crucial for business success. With companies growth their is a huge amount of data that we should look at to drive business strategies. However, the challenge lies in transforming this data into actionable insights that can drive business strategy and improve customer experiences.

## 1.1. Dataset Overview 

I have taken this dataset from **[UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)** and it contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. It was originally an xlxs file that I converted to .csv for better handeling.

- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If
this code starts with letter 'c', it indicates a cancellation.
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct
product.
- Description: Product (item) name. Nominal.
- Quantity: The quantities of each product (item) per transaction. Numeric.
- InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.


## 1.2. Project Objective

In this project I will utilize unsupervised machine learning techniques to analyze customer purchasing behavior in an online retail setting.

I'll perform following steps:

- **Data Loading and Initial Exploration:** We'll start by loading the dataset and examine it's structure and basic statistics.
- **Data Preprocessing and Cleaning:** This step will include handling missing values, removing duplicated, converying any neccessary datatypes and handleing outliers.
- **Exploratory Data Analysis (EDA):** In this step, we'll analyze the distributions of numerical features, explore relationships between variables and then we'll visualize key insights using plots; histograms, scatter plots, etc.
- **Feature Engineering and Selection:** We'll create new features that might be useful for clustering and then implement RFM analysis.
- **Dimensionality Reduction (PCA):** We'll also apply PCA to reduce the dimensions wwhile retaining most of the variance. 
- **Clustering Analysis:** Then we'll apply different clustering algorithms (K-means, Hierarchical Clustering, DBSCAN). We'll also do experiment with different numbers of clusters.
- **Clustering Algorithm Comparison:** We'll compare the performance of different clustering algorithms using metrics like silhouette score. and will use elbow method or silhouette analysis to determine the optimal number of clusters. We'll compare different clustering algorithms including:
    - K-means Clustering
    - DBSCAN Clustering
    - Hierarchical Clustering
- **Hyperparameter Tuning:** We'll implement hyperparameter tuning for the best performing algorithm
- **Final Results and Conclusion:** Last step, we'll interpert our project findings, we'll discuss the strengths and limitations of our analysis and will suggest potential business applications based on our insights.
