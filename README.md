# Customer Segmentation with KMeans

A machine learning project developed as part of the **AUEB AI Data Factory – Machine Learning & Data Analysis Bootcamp**.

The goal of the project is to segment supermarket customers into meaningful groups using **KMeans clustering**, with a focus on identifying high-spending customer segments that could support targeted marketing strategies.

## Project Overview

The dataset contains customer information including:

- Customer ID
- Age
- Gender
- Annual Income
- Spending Score

The clustering process focuses primarily on **Annual Income** and **Spending Score**, while also examining the potential contribution of additional features such as Age and Gender.

## Methodology

The project includes:

- Exploratory data analysis
- Outlier detection and removal
- Correlation analysis
- Feature selection
- Feature scaling
- KMeans clustering
- Elbow Method for cluster selection
- Silhouette Score evaluation
- Hyperparameter tuning
- Cluster visualization
- Identification of high-spending customer segments

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Clustering Evaluation

The optimal number of customer clusters is evaluated using both:

- **Elbow Method**, based on clustering inertia
- **Silhouette Score**, based on cluster cohesion and separation

These methods are compared in order to select an appropriate number of clusters for customer segmentation.

## Business Objective

The final segmentation aims to identify customer groups with high spending behavior and provide useful insights that could support targeted marketing strategies.

## Repository Structure

```text
customer-segmentation-ml/
│
├── notebooks/
│   └── customer_segmentation.ipynb
│
├── data/
│   └── mall_customers.csv
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Key Learning Outcomes

Through this project I gained hands-on experience with:

- Applying unsupervised machine learning techniques
- Preparing and selecting features for clustering
- Evaluating the appropriate number of clusters
- Comparing Elbow Method and Silhouette Score
- Tuning KMeans parameters
- Visualizing customer segments
- Translating clustering results into business-oriented insights

## Future Improvements

Possible extensions of the project include:

- Compare KMeans with alternative clustering algorithms
- Apply dimensionality reduction techniques such as PCA
- Perform more advanced customer profiling for each cluster
- Build an interactive visualization dashboard
- Evaluate clustering stability across different initialization strategies
