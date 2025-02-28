# Supplier Performance Analysis 

### Project Overview

This project aims to analyze supply chain data to gain insights into supplier performance, identify key cost drivers, and uncover patterns that can optimize operational efficiency. By leveraging advanced machine learning techniques and thorough data exploration, we provide strategic insights to enhance procurement and supplier selection processes.

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

### Workflow

#### Features and Preprocessing

1. Data Preprocessing: Cleaning and encoding categorical variables, handling missing values, and scaling numerical features.

2. Feature Engineering: Creating new features like Cost per Unit, Defect Rate, and Lead Time Efficiency.

3. Modeling: Using machine learning algorithms to predict supplier performance and identify key cost drivers.

4. Evaluation: Assessing model performance using accuracy, precision, recall, and f1-score metrics.

### Key Findings

- Price and Lead Time were identified as the most influential factors affecting supplier performance, emphasizing the need for cost management and efficient logistics.

- Other important features include Availability and Manufacturing Costs, highlighting opportunities for inventory optimization and cost reduction.

- The model's accuracy was 35%, indicating room for improvement through advanced algorithms, hyperparameter tuning, or additional feature engineering.

### Results

- Accuracy: 35%, Precision and Recall varied across classes, indicating potential class imbalance or model limitations.

- Feature Importance: most important features influencing supplier performance include:
  - Manufacturing costs	(0.049958)
  - Order quantities	(0.043991)
  - Price	(0.042869)
  - Availability	(0.042432)
  - Number of products sold

### Source

https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis/data
