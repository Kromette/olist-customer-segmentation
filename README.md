# Olist Customer Segmentation

Customer segmentation project based on **unsupervised learning** and behavioral analysis of e-commerce customers.

The objective is to identify actionable customer segments that can be used by Olist's marketing team to better understand customer behavior and tailor communication campaigns.

## Project overview

Olist is a Brazilian e-commerce platform connecting merchants with online marketplaces.

The objective of this project is to build a customer segmentation based on customers' **purchasing behavior, satisfaction and available customer information**.

The segmentation should:

* cover the entire customer base;
* distinguish customers according to their purchasing behavior and satisfaction;
* produce interpretable and actionable customer profiles;
* remain relevant over time;
* provide a recommendation for how frequently the segmentation model should be updated.

The project is based on Olist's anonymized Brazilian e-commerce dataset, containing information about orders, products, payments, reviews and customer locations.

## Methodology

The project follows an end-to-end unsupervised learning approach:

1. **Exploratory data analysis**

   * Dataset quality assessment
   * Missing values and data consistency
   * Customer purchasing behavior
   * Order frequency and recency
   * Customer satisfaction
   * Geographic and behavioral analysis

2. **Feature engineering**

   * Aggregation of order-level information at customer level
   * Purchase frequency and recency
   * Monetary indicators
   * Customer satisfaction indicators
   * Behavioral features suitable for clustering

3. **Customer segmentation**

   * Comparison of several unsupervised learning approaches
   * Feature transformation and scaling
   * Hyperparameter exploration
   * Evaluation of clustering quality
   * Interpretation of resulting customer segments

4. **Business interpretation**

   * Characterization of each segment
   * Identification of high- and low-value customer profiles
   * Analysis of purchasing behavior and satisfaction
   * Translation of clusters into actionable marketing profiles

5. **Temporal stability analysis**

   * Simulation of the segmentation over time
   * Analysis of cluster stability and customer reallocation
   * Identification of when the segmentation becomes outdated
   * Recommendation for an appropriate model update frequency

## Key Data Science Topics

* Exploratory Data Analysis
* Feature engineering
* Customer segmentation
* Unsupervised learning
* Clustering
* Hyperparameter tuning
* Dimensionality reduction
* Model evaluation
* Customer behavior analysis
* Temporal stability analysis
* Business-oriented interpretation of machine learning models

## Dataset

The project uses the **Brazilian E-Commerce Public Dataset by Olist**, containing anonymized information about orders made through the Olist marketplace between 2016 and 2018.

The dataset includes information such as:

* customers and geographic location;
* orders and order status;
* products and product categories;
* payments;
* delivery information;
* customer reviews.

The original dataset is not included in this repository.

## Repository structure

```text
olist-customer-segmentation/
│
├── notebooks/
│   ├── 01_exploratory_analysis.ipynb
│   ├── 02_clustering_experiments.ipynb
│   └── 03_segmentation_stability.ipynb
│
├── presentation/
│   └── customer_segmentation.pdf
│
├── README.md
└── requirements.txt
```

## Outcome

The project delivers:

* an exploratory analysis of the customer base;
* a comparison of different clustering approaches;
* an interpretable customer segmentation;
* a characterization of the resulting customer profiles;
* a simulation of segment stability over time;
* a recommendation for maintaining the segmentation model.

## Tools & methods

**Python · pandas · NumPy · scikit-learn · data visualization · feature engineering · unsupervised learning · clustering · dimensionality reduction · model evaluation · customer analytics**

## Context

This project was completed as part of the **Data Scientist training at OpenClassrooms**.
