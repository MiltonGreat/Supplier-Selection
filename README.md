# Supplier Evaluation and Selection 

### Project Overview

**Your supply chain is only as strong as your most vulnerable supplier.** In an era of constant disruption, supplier selection is no longer just about cost and quality—it's about building a resilient, ethical, and strategically aligned supply base. This project conducts a comprehensive supplier governance audit, moving beyond traditional evaluation to diagnose risk concentration, identify single points of failure, and ensure your supplier portfolio aligns with ESG commitments and operational resilience goals.

#### Supply Chain Problem: The Hidden Risks in Your Supplier Portfolio

Traditional supplier scoring often creates dangerous blind spots. An ungoverned supplier base introduces critical vulnerabilities:

- Resilience Risk: Over-reliance on a few "high-quality" suppliers creates single points of failure.
- ESG Compliance Risk: Suppliers with poor financial health or unethical practices can cause reputational damage and regulatory penalties.
- Strategic Misalignment: Selecting suppliers based only on price and quality may conflict with goals for sustainability, diversity, and geographic diversification.
  
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

1. **The Resilience & Concentration Audit**

- Cluster-Based Risk Assessment: Our analysis revealed four distinct supplier archetypes. Cluster 0 (High-quality, high-serviceability) represents your strategic partners, but over-dependence on them is a critical risk. Cluster 2 (Low-quality, high-price) are clear candidates for exit, as they represent poor value and high operational risk.

- Financial Health Stress Test: We identified financial condition as a top-3 feature. This isn't just a score—it's an early warning system for supplier bankruptcy risk that could halt your production.

2. **The ESG & Strategic Alignment Audit**

- Cost-Effectiveness vs. Value: The price_to_quality_ratio is a crucial metric, but a governed system must also weigh factors like location (for carbon footprint and logistics resilience) and flexibility (the ability to respond to demand surges).

- Diversity & Concentration Analysis: A portfolio heavy on one cluster or geographic region is vulnerable to regional disruptions. Our clustering provides the blueprint for building a diverse, balanced supplier ecosystem.

3. **The Data Integrity & Model Governance Audit**

- Model Validation: The perfect performance of Linear Regression was flagged as a critical data integrity red flag, indicating potential data leakage. A governed process mandates rigorous validation to prevent flawed decision-making.

- Feature Governance: The fact that a composite_score was the top feature (46.6% importance) is a governance issue. We must audit how this score is calculated to ensure it doesn't mask underlying biases or misaligned incentives.

### Audit Results & Strategic Recommendations

- Portfolio Resilience - Clear segmentation into 4 clusters; risk of over-reliance on Cluster 0.	MODERATE RISK. Develop a balanced sourcing strategy across clusters to build redundancy. Exit Cluster 2 suppliers.
- Financial Risk - Financial Condition is a top-3 predictor.	HIGH PRIORITY. Implement continuous financial monitoring for strategic suppliers to pre-empt disruptions.
- Model Governance - Signs of overfitting; perfect Linear Regression performance indicates data leakage.	FAIL. Do not deploy these models without addressing data integrity issues and re-validation.

### Conclusion: From Supplier Selection to Supply Base Strategy

This audit demonstrates that supplier evaluation is not a one-time event but an ongoing governance process.

The supplier base is well-segmented but potentially over-optimized for historical performance. The lack of explicit ESG metrics and the model integrity issues mean the current evaluation system could be making the supply chain more efficient in the short term but more fragile in the long term.

### Source

https://www.kaggle.com/datasets/michaelclodeemil/suppliers-ranking-grades/data?select=supplier_ranking_grades.xlsx
