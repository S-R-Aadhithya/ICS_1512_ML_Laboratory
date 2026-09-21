# Assignment 8: Clustering Analysis on High-Dimensional Sensor Data

## Summary
This assignment implements and benchmarks three distinct clustering paradigms—K-Means, Agglomerative Hierarchical Clustering, and DBSCAN—on the UCI Human Activity Recognition (HAR) Smartphone dataset (10,299 instances, 561 inertial features, 6 activity classes). It explores optimal cluster estimation using Elbow analysis and Silhouette analysis, dimensionality reduction via PCA/t-SNE for visual validation, and external validation metrics against ground-truth activity labels.

## Instructions
- Ensure the UCI HAR Dataset is extracted within the folder (or extracted from `human+activity+recognition+using+smartphones.zip`).
- Run the cells in `Experiment_8_HAR_Clustering_Online.ipynb` sequentially.
- The compiled lab report and LaTeX sources are provided as `assn8_2470007.pdf` and `assn8_2470007.tex`.

## Dependencies
The required libraries to run this notebook are listed in the `dependencies.txt` file. You can install them using:
```bash
pip install -r dependencies.txt
```

## Dataset
- **UCI Human Activity Recognition (HAR) Using Smartphones**:
  - Total instances: 10,299 (Train: 7,352, Test: 2,947)
  - Features: 561 continuous features derived from triaxial linear acceleration and angular velocity sensors.
  - Ground truth: 6 activities (Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying).
