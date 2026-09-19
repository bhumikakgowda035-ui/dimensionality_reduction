# Comparative Report: PCA vs t-SNE

## 1. Introduction

This project investigates dimensionality reduction using Principal
Component Analysis (PCA) and t-SNE on the Iris dataset.

## 2. Dataset

The Iris dataset contains 150 samples, 4 numerical features,
and 3 different classes.

## 3. Exploratory Data Analysis

The dataset was examined for:
- Dataset dimensions
- Missing values
- Statistical summary
- Class distribution

No missing values were found in the dataset.

## 4. Data Preprocessing

The numerical features were standardized using StandardScaler
before applying PCA and t-SNE.

## 5. PCA

Principal Component Analysis was applied to reduce the number of
dimensions.

The cumulative explained variance was examined to determine an
appropriate number of components.

A PCA explained-variance plot and a 2D PCA visualization were created.

## 6. t-SNE

t-SNE was used to create a two-dimensional representation of the
dataset.

Different values of perplexity and learning rate were tested.

The t-SNE visualization was created to examine the separation of
the three Iris classes.

## 7. Classification

Logistic Regression was used to compare classification performance
on:

1. Original data
2. PCA-reduced data
3. t-SNE-reduced data

## 8. Visualizations

The following plots are included in the assets/plots folder:

- pca_2d.png
- tsne_2d.png
- pca_explained_variance.png
- accuracy_comparison.png

## 9. Performance Comparison

Classification accuracy was compared between the original data,
PCA-reduced data, and t-SNE-reduced data.

The accuracy comparison plot is included in the project assets.

## 10. PCA vs t-SNE

PCA is a linear dimensionality reduction technique that can be
used for feature transformation while preserving a selected
amount of variance.

t-SNE is mainly designed for visualization and is useful for
examining local structure and patterns in high-dimensional data.

## 11. Limitations

Standard t-SNE does not provide the same straightforward transform
operation for new unseen samples as PCA. Therefore, the t-SNE
classification experiment should be considered exploratory.

## 12. Conclusion

The project demonstrates the use of PCA and t-SNE for dimensionality
reduction and visualization. PCA provides a compact representation
based on explained variance, while t-SNE provides a useful
two-dimensional visualization of the dataset.
