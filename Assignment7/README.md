# Assignment 7: Dimensionality Reduction via PCA & Empirical Classifier Evaluation

## Summary
This assignment investigates the empirical impact of dimensionality reduction via Principal Component Analysis (PCA) compared to using full original feature sets across 10 supervised classification models and 3 distinct benchmark datasets (Breast Cancer Wisconsin, Spambase, and Iris). It evaluates variance retention (at 95% threshold), 5-fold cross-validation performance, test Macro F1 scores, and statistical significance via paired $t$-tests and Wilcoxon signed-rank tests.

## Instructions
- Ensure all dependencies are installed.
- Run the Jupyter Notebook `Experiment_7_PCA_Model_Evaluation.ipynb` sequentially from top to bottom.
- The compiled lab report and LaTeX sources are provided as `assn7_2470007.pdf` and `assn7_2470007.tex`.

## Dependencies
The required libraries to run this notebook are listed in the `dependencies.txt` file. You can install them using:
```bash
pip install -r dependencies.txt
```

## Datasets
1. **Breast Cancer Wisconsin (Diagnostic)**: Available via `sklearn.datasets.load_breast_cancer` (569 samples, 30 features, 2 classes).
2. **Spambase**: Loaded via `ucimlrepo` (`fetch_ucirepo(id=94)`) or UCI repository (4,601 samples, 57 features, 2 classes).
3. **Iris**: Available via `sklearn.datasets.load_iris` (150 samples, 4 features, 3 classes).
