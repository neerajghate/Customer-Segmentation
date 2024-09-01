# Customer Segmentation Using Machine Learning to Generate Insights

## Abstract
In today’s data-driven world, customer-centric companies heavily rely on effective resource management to drive growth. This project focuses on an automated approach to customer acquisition, efficiency, and task execution by identifying potential customers and grouping them into specific segments based on various parameters. This approach aims to generate useful insights for faster execution and to revolutionize the supply-chain and service model, ultimately leading to exponential customer growth.

## Keywords
- Customer Segmentation
- Machine Learning
- Clustering
- Insights

## Problem Statement
As a supermarket owner, understanding customer behavior is crucial. This project aims to identify target customers who can be easily converted, providing actionable insights to the marketing team for strategic planning.

## Introduction
Customer segmentation is a critical component for any direct-to-consumer (D2C) company. By analyzing and predicting customer locations and behaviors, companies can improve product/service delivery and optimize their supply chain. This project leverages machine learning algorithms and clustering methods to predict and classify customers based on geographic and behavioral data, thereby enhancing the efficiency of supply-chain operations and overall company growth.

## Objective
The main objective of this project is to identify different segments within the existing customer base by analyzing spending patterns and past interactions.

## Design/Architecture
- **Data Collection:** Customer data is sourced from `Customer.csv`.
- **Data Processing:** The dataset is cleaned and pre-processed for analysis.
- **Clustering:** K-means clustering is applied to segment customers.
- **Insight Generation:** Analysis of clusters to derive actionable insights.

## Proposed Work
This project proposes the use of K-means clustering to efficiently segment customers. The expected outcome is to identify key customer segments that can be targeted for marketing campaigns, leading to better customer acquisition and retention.

## Methods/Techniques/Algorithms

### K-means Clustering
- **Principle:** K-means clustering is an unsupervised learning algorithm used for grouping unlabelled data into clusters.
- **Steps:**
  1. Initialize a dictionary to store the Sum of Squared Errors (SSE) for each value of k.
  2. Run the algorithm for a range of k values and store the SSE for each run.
  3. Plot SSE vs k to find the "elbow point," which indicates the optimal number of clusters.

### Tools Used
- **Numpy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

## Observations/Results
- The average credit limit among customers is approximately 35K, with 50% of customers having a credit limit below 18K, indicating a positive skew.
- There is a high variation in credit limits, as observed from the standard deviation.
- On average, customers own about 5 credit cards, with some owning up to 10.
- Customer interactions predominantly occur through calls, followed by online channels. Some customers have never interacted with the bank.

## Conclusion
This project provides valuable insights into customer segmentation using machine learning. By understanding customer behavior and preferences, businesses can tailor their marketing strategies, optimize resource allocation, and enhance overall efficiency.

## How to Run the Project
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebook or Python script provided to see the analysis and results.


