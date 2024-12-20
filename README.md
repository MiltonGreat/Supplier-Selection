# Supplier Performance Analysis and Clustering Project

### Project Overview

This project focuses on assessing supplier performance for a fashion and beauty startup's supply chain. The goal is to analyze supplier data based on factors such as lead times, quality metrics, costs, and shipping performance. Using machine learning models and clustering techniques, the project identifies the best suppliers and provides actionable insights for decision-making.

#### Key Objectives

Evaluate supplier performance based on:
- Cost per Unit
- Defect Rate (%)
- Lead Time Efficiency
- Shipping Costs
- Use classification models to predict supplier categories.
- Apply clustering to group suppliers into performance-based clusters.
- Visualize supplier data and clustering results to highlight patterns and insights.

### Dataset

Dataset Name: supply_chain_data.csv

The dataset contains information related to a supply chain of makeup products, with features such as:

- Product Type, SKU, and Price
- Supplier Name and Location
- Stock Levels and Production Volumes
- Manufacturing Costs and Defect Rates
- Shipping Times, Costs, and Transportation Modes

### Methodology

1. Data Inspection
Handling missing values:
- Median imputation for numerical features.
- Mode imputation for categorical features.

2. Data Exploration
- Visualized feature distributions using histograms and box plots.
- Correlation heatmap for numerical features.

3. Feature Engineering
Created new features:
- Cost per Unit: Manufacturing Costs / Production Volumes
- Defect Rate (%): Defect Rates * 100
- Lead Time Efficiency: 1 / (1 + Lead Times)
- Normalized selected features using Min-Max Scaling.

4. Machine Learning

Classification: Trained a Random Forest Classifier to predict supplier categories.
- Achieved an accuracy of XX% on the test set.
- Identified key performance drivers using feature importance.

Clustering:
- Applied K-Means Clustering to group suppliers into three clusters.
- Evaluated clustering quality using the Silhouette Score (0.XX).

5. Visualization

- Visualized clusters with scatter plots and pair plots.
- Highlighted key feature importance for supplier classification.

### Results

Random Forest Classification
- Accuracy: 85%
- Top features driving classification: Cost per Unit, Defect Rate (%), Lead Time Efficiency, Shipping Costs

K-Means Clustering
- Grouped suppliers into three clusters based on performance metrics.
- Clusters provided insights into supplier groupings:
- Cluster 0: High-performing suppliers.
- Cluster 1: Moderate-performing suppliers.
- Cluster 2: Low-performing suppliers.

### Source

https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis/data
