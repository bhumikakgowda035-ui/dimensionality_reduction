# Dimensionality Reduction Project

## Overview

This project demonstrates dimensionality reduction techniques using the Iris dataset.

The main techniques used are:

- Principal Component Analysis (PCA)
- t-Distributed Stochastic Neighbor Embedding (t-SNE)

The project also compares classification performance before and after dimensionality reduction.

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Standardize the dataset
- Apply PCA for dimensionality reduction
- Analyze explained variance
- Apply t-SNE for 2D visualization
- Compare classification accuracy
- Visualize the results

## Dataset

The Iris dataset is used for this project.

It contains measurements of:

- Sepal length
- Sepal width
- Petal length
- Petal width

The target contains three flower classes:

- Setosa
- Versicolor
- Virginica

## Project Structure

```text
ML_Project/
│
├── README.md
├── requirements.txt
│
├── notebooks/
│   └── dimensionality_reduction.ipynb
│
├── docs/
│   └── comparative_report.md
│
└── assets/
    └── plots/
        ├── pca_2d.png
        ├── tsne_2d.png
        ├── pca_explained_variance.png
        └── accuracy_comparison.png
