# Wine Clustering Project

This repository focuses on clustering Portuguese "Vinho Verde" red wine data based on physicochemical properties, aiming to uncover patterns and meaningful groupings. The analysis leverages machine learning techniques like PCA and KMeans clustering, implemented in Python and structured in a Jupyter notebook for easy interpretation and reproduction.

## Contents

### Main Files
- **clustering.ipynb**: Contains the step-by-step implementation of the clustering project.
- **winequality-red.csv**: Dataset with physicochemical properties and quality scores for red wine variants.

## Features

1. **Dataset Overview**:
   - Physicochemical properties: 11 input features like acidity, sugar, pH, and alcohol content.
   - Output variable: `quality`, representing sensory evaluations (excluded during clustering).

2. **Preprocessing**:
   - Data cleaning: Handling duplicates and missing values.
   - Feature standardization to ensure equal contribution during clustering.

3. **Exploratory Data Analysis (EDA)**:
   - Outlier detection using box plots.
   - Correlation heatmaps to understand variable relationships.

4. **Dimensionality Reduction**:
   - Principal Component Analysis (PCA) to reduce dataset dimensionality.
   - Explained variance plots to determine the number of components to retain.

5. **Clustering**:
   - Optimal cluster determination using the Elbow Method.
   - Validation with Silhouette Analysis.
   - Application of KMeans clustering to group wines into distinct categories.

6. **Cluster Analysis**:
   - Comparing clusters by key features.
   - Assigning descriptive labels to clusters for interpretability.
   - Visualizing clusters using scatter plots and pairwise comparisons.

## Technologies Used

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` for data manipulation.
  - `seaborn`, `matplotlib` for static visualizations.
  - `plotly` for interactive visualizations.
  - `scikit-learn` for PCA, clustering, and preprocessing.
  - `yellowbrick` for clustering metrics visualization.


## License

This project is licensed under the [MIT License](LICENSE), allowing wide use, modification, and distribution.

---

