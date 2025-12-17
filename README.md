# Customer Segmentation with Clustering

This repository contains an end-to-end customer segmentation analysis using unsupervised learning techniques on credit card usage data.  
The focus is on **cluster interpretability, stability, and business relevance**, not just model metrics.


## Objective

- Segment customers based on behavioral patterns
- Compare multiple clustering algorithms
- Interpret clusters and translate them into actionable business insights


## Dataset

- Source: Kaggle – Customer Segmentation Dataset  (https://www.kaggle.com/datasets/hashemi221022/customer-segmentation-data/data)
- Domain: Credit card usage and payment behavior  


## Methodology

**Data Preparation**
- Missing value treatment using domain logic  
- Log transformation for skewed features  
- Feature scaling using StandardScaler  
- Dimensionality reduction using PCA  

**Clustering Techniques**
- K-Means (final selected model)
- DBSCAN
- Hierarchical Clustering  

Model selection was based on cluster separation, stability, and interpretability.


## Cluster Interpretation & Validation

- Clusters interpreted using PCA component loadings
- Validation included statistical metrics and business-grounded measures
- Segments described by **behavior**, not demographics, to avoid bias


## Business Applications

- Targeted product and pricing strategies
- Risk identification and credit management
- Personalization and customer lifecycle planning

https://medium.com/@apoorva.jishtu/from-raw-transactions-to-real-customer-segments-a-practical-guide-to-clustering-for-business-7ef9137b6b2c?postPublishedType=repub

