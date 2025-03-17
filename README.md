# Supplier Evaluation and Selection 

### Project Overview

This project focuses on evaluating and selecting suppliers based on various performance metrics using data science techniques. The goal is to identify the best suppliers by analyzing factors such as quality, price, delivery time, financial health, and more. The project involves data preprocessing, feature engineering, machine learning modeling, and cluster analysis to derive actionable insights.

#### Project Objectives

- Evaluate Supplier Performance: Analyze supplier data to identify key performance metrics.
- Feature Engineering: Create new features to enhance the dataset and improve model performance.
- Machine Learning Modeling: Train and evaluate models to predict supplier performance.
- Cluster Analysis: Group suppliers into clusters based on their characteristics for targeted selection.
  
### Dataset

The dataset contains information about suppliers and their performance across various metrics, including:

- Quality: Quality score of the supplier.
- Quantity: Quantity of goods or services supplied.
- Price: Price of goods or services.
- Delivery Time: Time taken to deliver goods or services.
- Financial Condition: Financial health of the supplier.
- Serviceability: Responsiveness and communication of the supplier.
- Reputation: Reputation and competence of the supplier.
- Flexibility: Adaptability of the supplier.
- Location: Supplier’s location and traffic connections.

### Workflow

#### Features and Preprocessing

1. Data Preprocessing: Cleaning and encoding categorical variables, handling missing values, and scaling numerical features.

2. Feature Engineering: Creating new features like Cost per Unit, Defect Rate, and Lead Time Efficiency.

3. Modeling: Train and evaluate models (Linear Regression, Random Forest, Gradient Boosting).

4. Cluster Analysis: Use K-Means clustering to group suppliers into clusters based on their characteristics.

### Key Findings

1. Feature Importance:
- The composite_score was the most important feature, contributing 46.6% to the model’s predictions.
- Other important features included financial condition, serviceability, and price.

2. Model Performance:
- Linear Regression achieved perfect performance, indicating potential data leakage or a trivial problem.
- Random Forest and Gradient Boosting showed signs of overfitting, with moderate performance on the test set.

3. Cluster Analysis:
- Cluster 0: High-quality, high-serviceability suppliers.
- Cluster 1: High-quantity, moderate-quality suppliers.
- Cluster 2: Low-quality, high-price suppliers.
- Cluster 3: Low-quantity, low-quality suppliers.

4. Cost-Effectiveness:
- Suppliers with the lowest price_to_quality_ratio were identified as the most cost-effective.

### Source

https://www.kaggle.com/datasets/michaelclodeemil/suppliers-ranking-grades/data?select=supplier_ranking_grades.xlsx
