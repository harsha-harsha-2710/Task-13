# Task 13: PCA – Dimensionality Reduction

## Objective
To apply Principal Component Analysis (PCA) for dimensionality reduction and study the trade-off between variance retention and model accuracy.

## Dataset
Sklearn Digits Dataset (8x8 grayscale images)

## Tools Used
- Python
- Scikit-learn
- Matplotlib

## Steps Performed
- Loaded and flattened the digits dataset
- Scaled features using StandardScaler
- Applied PCA with multiple components (2, 10, 30, 50)
- Plotted cumulative explained variance
- Reduced dataset using optimal PCA components
- Trained Logistic Regression on original and reduced data
- Compared accuracy of both models
- Visualized data using 2D PCA

## Results
- Original dataset accuracy: ~97%
- PCA reduced dataset (30 components) accuracy: ~95%
- Features reduced from 64 to 30

## Conclusion
PCA effectively reduces dimensionality while retaining most of the variance and maintaining high classification accuracy.
