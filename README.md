# 🛍️ Customer Segmentation using K-Means Clustering

> **SkillCraft Technology – Machine Learning Internship Task 02**

A machine learning project that segments mall customers into meaningful groups using the **K-Means Clustering** algorithm.

---

## 📌 Table of Contents

- Overview
- Project Objectives
- Dataset
- Technologies Used
- Project Workflow
- Exploratory Data Analysis
- Data Preprocessing
- Model Building
- Model Evaluation
- Visualizations
- Business Insights
- Results
- Project Structure
- Installation
- Future Improvements
- Author

---

## 📖 Overview

Customer segmentation is a fundamental marketing strategy used to divide customers into groups with similar characteristics. Businesses can use these groups to design personalized marketing campaigns, improve customer satisfaction, and increase revenue.

In this project, the **K-Means Clustering** algorithm is used to segment customers based on:

- Gender
- Age
- Annual Income
- Spending Score

The optimal number of clusters was determined using the **Elbow Method** and **Silhouette Score**, ensuring that the segmentation is both data-driven and easy to interpret.

---

## 🎯 Project Objectives

- Perform exploratory data analysis (EDA).
- Understand customer demographics and spending behavior.
- Prepare data using feature engineering and standardization.
- Determine the optimal number of clusters.
- Build a K-Means clustering model.
- Evaluate clustering performance using multiple metrics.
- Visualize customer segments.
- Provide business recommendations for each customer group.


---

## 📂 Dataset

**Dataset Name:** Mall Customers Dataset

**Source:** https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Dataset Features

| Feature | Description |
|----------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Male/Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Customer spending score assigned by the mall |

**Dataset Size**

- Rows: **200**
- Columns: **5**

---

## 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn, Plotly |
| Machine Learning | Scikit-learn |
| Dimensionality Reduction | PCA |
| Notebook | Jupyter Notebook |
| Version Control | Git & GitHub |

---

## 🚀 Built With

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blue)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-purple?logo=plotly)
![Git](https://img.shields.io/badge/Git-Version%20Control-red?logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)

---

## 🔄 Project Workflow

```text
                 Mall Customers Dataset
                           │
                           ▼
                 Data Loading & Inspection
                           │
                           ▼
                Data Quality Assessment
                           │
                           ▼
              Exploratory Data Analysis (EDA)
                           │
                           ▼
                Feature Engineering & Scaling
                           │
                           ▼
          Elbow Method & Silhouette Analysis
                           │
                           ▼
                K-Means Clustering Model
                           │
                           ▼
                  Model Evaluation
                           │
                           ▼
             Customer Segmentation Results
                           │
                           ▼
          Business Insights & Recommendations
```

---


## 📊 Model Evaluation

| Metric | Value |
|---------|------:|
| Algorithm | K-Means Clustering |
| Optimal Number of Clusters | 5 |
| Silhouette Score | **0.xxx** |
| Davies-Bouldin Index | **x.xxx** |
| Calinski-Harabasz Score | **xxx.xx** |

The optimal number of clusters was selected using the **Elbow Method** and **Silhouette Score**. Although the silhouette score increased for larger values of K, **K = 5** was chosen because it provides the best balance between clustering performance and business interpretability.

## 📈 Key Results

- Successfully segmented customers into **5 meaningful clusters**.
- Applied feature scaling using **StandardScaler**.
- Determined the optimal number of clusters using the **Elbow Method** and **Silhouette Score**.
- Evaluated clustering quality using three performance metrics.
- Generated customer personas and business recommendations for each cluster.

## 📷 Project Visualizations

### Customer Segmentation

![Customer Clusters](images/customer_clusters.png)

---

### Elbow Method

![Elbow Method](images/elbow_method.png)

---

### PCA Visualization

![PCA Clusters](images/pca_clusters.png)

---

### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)



## 💼 Business Insights

The clustering analysis identified multiple customer groups with distinct purchasing behaviors.

### Business Recommendations

- 🎯 Offer premium memberships to high-income, high-spending customers.
- 🎁 Provide discounts and loyalty rewards for regular customers.
- 📢 Target high-income, low-spending customers with personalized promotions.
- 🛍️ Design budget-friendly campaigns for low-income customer segments.
- 📈 Use customer segmentation to improve marketing efficiency and increase customer retention.

- 
