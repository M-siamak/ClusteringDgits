# Clustering Performance Evaluation with KMeans, NMI, and ARI

This repository contains a Jupyter notebook that demonstrates the evaluation of **KMeans clustering** performance using **Adjusted Rand Index (ARI)** and **Normalized Mutual Information (NMI)** metrics. The notebook performs clustering on a dataset, calculates the clustering inertia for multiple runs, and evaluates clustering consistency using ARI and NMI.

## Overview

The notebook covers the following steps:
1. **Clustering with KMeans**: The **KMeans clustering algorithm** is applied to the dataset, with multiple initializations for performance evaluation.
2. **Inertia Calculation**: The **inertia** (WCSS) is calculated for different **K** values and multiple runs to assess clustering consistency.
3. **Clustering Performance Evaluation**:
   - **Adjusted Rand Index (ARI)**: Measures the similarity between clustering results.
   - **Normalized Mutual Information (NMI)**: Evaluates the shared information between clustering and true labels.
4. **Visualization**: The results of clustering evaluation (inertia, ARI, NMI) are visualized to help understand the behavior of KMeans clustering.

## Files in this Repository

- **`clustering_nmi_ari_analysis.ipynb`**: The main Jupyter notebook where **KMeans clustering** is performed, and the performance metrics **ARI** and **NMI** are calculated and visualized.

## Features

- **KMeans Clustering**: Implements the **KMeans** algorithm to cluster data into K groups.
- **Inertia Calculation**: Evaluates clustering inertia across multiple initializations and K values.
- **Clustering Evaluation**: Measures clustering quality using **ARI** and **NMI** metrics.
- **Visualization**: Plots the clustering performance metrics for easy interpretation.

## Requirements

To run this notebook, you will need the following Python libraries:
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**

Yo
