# 🛍️ Mall Customers Segmentation Project

## 📋 Project Overview

This project explores the **Mall Customers Dataset**, which contains information about 200 customers including their demographic details, annual income, and spending habits. The goal is to perform **exploratory data analysis (EDA)**, **visualizations**, and **customer segmentation** using clustering techniques, primarily **K-Means clustering**.

Through this project, we aim to discover meaningful customer groups based on their behaviors and demographics to enable targeted marketing strategies.

---

## 📦 Dataset Information

- **Dataset Name:** Mall Customers Dataset
- **Records:** 200 customers
- **Features:** 5 columns
- **Missing Values:** None

### 🧾 Features Description

| Feature | Description |
|:-------|:------------|
| `CustomerID` | Unique ID assigned to each customer |
| `Gender` | Gender of the customer (`Male`/`Female`) |
| `Age` | Age of the customer (in years) |
| `Annual Income (k$)` | Annual income of the customer (in thousands of dollars) |
| `Spending Score (1-100)` | Score assigned by the mall based on customer behavior and spending habits |

---

## 🎯 Project Objectives

- Perform data cleaning and correction (rename features for better readability).
- Conduct detailed Exploratory Data Analysis (EDA).
- Visualize key patterns and distributions (Age, Income, Spending Score).
- Understand relationships between features (e.g., Income vs Spending Score).
- Apply **K-Means clustering** to segment customers into different groups.
- Interpret the characteristics of each customer cluster.
- Derive business insights to inform marketing and sales strategies.

---

## 📊 Techniques and Tools Used

- **Python Libraries:** 
  - `Pandas` for data handling
  - `Matplotlib` and `Seaborn` for visualizations
  - `Scikit-learn` for clustering (K-Means)
- **Data Visualization:** 
  - Histograms, KDE plots, Boxplots, Scatter plots
- **Clustering:** 
  - Elbow method to determine the optimal number of clusters
  - K-Means clustering to segment customers

---

## 🔍 Key Insights

- Customers can be grouped into distinct clusters based on their annual income and spending habits.
- Age, gender, and income have significant influence on spending behavior.
- Identified potential high-value customer segments that could be targeted through personalized marketing campaigns.

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Install required libraries using:
    ```
    pip install pandas matplotlib seaborn scikit-learn
    ```
3. Open the Jupyter Notebook or Kaggle Notebook and run the cells sequentially.
---

## 📜 License

This project is licensed under the MIT License — feel free to use, modify, and distribute.

