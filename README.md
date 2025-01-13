# Supplier Performance Analysis and Clustering Project

### Project Overview

The project aims to analyze supplier performance by evaluating factors like defect rates, lead times, and cost efficiency. We employ machine learning models to predict supplier reliability and optimize the allocation of orders. This will help in decision-making by selecting suppliers who meet cost and delivery expectations while minimizing risk.

Key components:

- Supplier defect rates and lead times
- Order reallocation for optimized performance
- Predictive modeling for supplier selection and evaluation

#### Key Objectives

Evaluate supplier performance based on:
- Cost per Unit
- Defect Rate (%)
- Lead Time Efficiency
- Shipping Costs
- Use classification models to predict supplier categories.
- Apply clustering to group suppliers into performance-based clusters.
- Visualize supplier data and clustering results to highlight patterns and insights.

### Problem Statement

Evaluating supplier performance is essential for maintaining a resilient supply chain. This project focuses on analyzing supplier metrics to identify the most reliable and cost-effective partners for a fashion and beauty startup.

### Dataset

Dataset Name: supply_chain_data.csv

The dataset contains information related to a supply chain of makeup products, with features such as:

- Product Type, SKU, and Price
- Supplier Name and Location
- Stock Levels and Production Volumes
- Manufacturing Costs and Defect Rates
- Shipping Times, Costs, and Transportation Modes

### Solution Approach

#### Features and Preprocessing

- Defect Rate: This is a key feature that reflects supplier reliability. We performed feature scaling and encoded categorical variables (e.g., supplier names).

- Lead Times: We optimized lead times by reallocating orders among suppliers to reduce delays.

- Feature Engineering: New features were created, including:
    - Defect Rate (%)
    - Lead Time Efficiency

Preprocessing steps involved encoding categorical variables, handling missing values, and normalizing continuous features.

#### Modeling

The project involves training a classification model to predict supplier reliability based on various features. We used the following steps:

- Data Splitting: We divided the data into training (80%) and testing (20%) sets.
- Modeling Approach: Initially, we used a basic classification model (e.g., Random Forest, Logistic Regression) and evaluated it using accuracy, precision, recall, and F1-score metrics.
- Feature Importance: We analyzed the importance of different features, highlighting manufacturing costs, order quantities, and product availability.

### Results

- Identified the top 20% of suppliers who met Defect Rate (Supplier 3	- 0.226410, Supplier 4 - 0.398177, Supplier - 0.021170).
  
- Updated Lead Times After Order Reallocation: Lead times were optimized for suppliers based on defect rates and historical performance.

- Feature Importance: most important features influencing supplier performance include:
  - Manufacturing costs	(0.049958)
  - Order quantities	(0.043991)
  - Price	(0.042869)
  - Availability	(0.042432)
  - Number of products sold

### Source

https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis/data
