# Mall-Customer-Segmentation
📌 Project Overview

This project focuses on segmenting mall customers into distinct groups based on their purchasing behavior using K-Means clustering. The objective is to identify meaningful customer segments that can help businesses design targeted marketing strategies and improve customer engagement.

🎯 Problem Statement

Retail businesses often struggle to understand diverse customer behaviors. The goal of this project is to group customers based on annual income and spending score, enabling data-driven decision-making for personalized marketing and customer retention.

📊 Dataset

The dataset contains customer information including:
Customer ID
Gender
Age
Annual Income
Spending Score

For clustering, Annual Income and Spending Score were selected as they best represent purchasing power and spending behavior.

🛠️ Technologies & Tools

Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn

🔄 Project Workflow

Data Loading & Exploration
Loaded the dataset and performed exploratory data analysis to understand feature distributions and relationships.

Data Preprocessing
Selected relevant features and applied feature scaling to ensure effective distance-based clustering.

Optimal Cluster Selection
Used the Elbow Method to determine the optimal number of clusters.

Model Building
Applied K-Means clustering to segment customers into distinct groups.

Cluster Interpretation
Analyzed cluster centroids and assigned meaningful business labels to each customer segment.

Visualization & Insights
Visualized clusters to validate separation and interpret customer behavior.

🧩 Customer Segments Identified

Based on centroid analysis, the following customer segments were identified:
Premium Customers: High income, high spending
Potential Customers: High income, low spending
Impulsive Customers: Low income, high spending
Low-Value Customers: Low income, low spending
Average Customers: Moderate income and spending

📈 Key Insights

High-income customers with low spending represent an opportunity for targeted promotions.
Premium customers contribute significantly to revenue and benefit from loyalty programs.
Customer segmentation enables efficient allocation of marketing resources.

✅ Conclusion

This project demonstrates how unsupervised learning can be used to extract actionable business insights from customer data. The segmentation results can assist retail businesses in optimizing marketing strategies, improving customer satisfaction, and increasing overall revenue.

🚀 Future Improvements
Include additional features such as age and purchase history.
Experiment with other clustering techniques like Hierarchical or DBSCAN.
Deploy the project using a web interface for real-time analysis.
