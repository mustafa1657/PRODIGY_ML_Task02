# PRODIGY_ML_TASK02 - Customer Segmentation using K-Means Clustering

## About the Project
This project is part of my Machine Learning internship at Prodigy InfoTech. In this task, I used the **K-Means Clustering algorithm** to group customers of a retail store based on their purchase behavior.

## Dataset Used
- Source: [Kaggle - Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- The dataset contains details like:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

## What I Did
- I loaded the dataset using Pandas and explored it to understand the data.
- I selected **Annual Income** and **Spending Score** as features for clustering.
- I used the **Elbow Method** to find the best number of clusters (k).
- Then, I applied the **KMeans algorithm** from `sklearn.cluster`.
- Finally, I visualized the clusters using a scatter plot with different colors for each cluster and marked the centroids.

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- sklearn

## Results
- I found **5 distinct clusters** of customers.
- The clusters showed clear grouping based on income and spending behavior.
- This can help the business understand customer types like high spenders, low-income high-spenders, etc.

## Conclusion
This project helped me understand how unsupervised learning works and how clustering can be used for customer segmentation in real-world business scenarios.

