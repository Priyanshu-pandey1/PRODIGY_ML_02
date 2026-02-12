# PRODIGY_ML_02: Customer Segmentation using K-Means Clustering

## 📝 Task Description
This project was developed during my **Machine Learning Internship** at **Prodigy InfoTech**. The objective of **Task-02** was to create a K-Means clustering algorithm to group customers of a retail store based on their purchase history, specifically using features like age, annual income, and spending score.

## 🚀 Project Overview
In this task, I implemented an **Unsupervised Learning** approach to identify hidden patterns in customer data. To make the model more robust and visualize high-dimensional data, I utilized **PCA (Principal Component Analysis)** for dimensionality reduction.

## 📊 Dataset
The project uses the **Mall Customer Segmentation Data** from Kaggle.
- **Source:** [Kaggle Dataset Link](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Features Used:** `Age`, `Annual Income (k$)`, `Spending Score (1-100)`.

## 🛠️ Tech Stack & Workflow
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, Seaborn, Matplotlib, Scikit-learn
- **Key Techniques:**
  - **StandardScaler:** To normalize the range of independent variables.
  - **PCA:** To reduce the 3D feature space into 2D for optimized visualization.
  - **Elbow Method:** To determine the optimal number of clusters (K).

## 📈 Clustering Results
Based on the **Elbow Method**, the optimal number of clusters was identified as **K=5**. 



### Customer Segments Identified:
1. **The Target Group:** High income and high spending score.
2. **The Careful Group:** High income but low spending score.
3. **The Average Group:** Middle-of-the-road income and spending habits.
4. **The Impulsive Group:** Low income but high spending score.
5. **The Sensible Group:** Low income and low spending score.



## 🧪 Implementation Steps
1. **Data Preprocessing:** Handled missing values and explored data distributions.
2. **Feature Scaling:** Standardized the features to ensure the distance-based algorithm (K-Means) performs correctly.
3. **Dimensionality Reduction:** Used PCA to transform the data into two principal components.
4. **Hyperparameter Tuning:** Applied the Elbow Method to find the most efficient cluster count.
5. **Model Training:** Implemented `KMeans` with `n_init=10` and `random_state=42` for consistent results.
6. **Visualization:** Plotted the final clusters and their centroids for clear business interpretation.

---
**Intern Name:** Priyanshu Pandey  
**Track:** Machine Learning  
**Company:** Prodigy InfoTech  
**Internship Month:** February 2026
