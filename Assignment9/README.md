# Assignment 9: Perceptron Learning Algorithm (PLA) vs Multi-Layer Perceptron (MLP)

## Summary
This assignment investigates the theoretical limitations of single-layer linear threshold models versus multi-layer non-linear architectures. It benchmarks the classical Perceptron Learning Algorithm (PLA) against Multi-Layer Perceptrons (MLP) on both synthetic canonical problems (linearly separable vs non-linearly separable XOR datasets) and high-dimensional handwritten English character recognition using the Character Fonts dataset.

## Instructions
- Ensure the font dataset is extracted (or extracted from `archive (6).zip` if needed).
- Run the cells in the Jupyter Notebook `Experiment_9_PLA_vs_MLP.ipynb` sequentially.
- The compiled lab report and LaTeX sources are provided as `assn9_2470007.pdf` and `assn9_2470007.tex`.

## Dependencies
The required libraries to run this notebook are listed in the `dependencies.txt` file. You can install them using:
```bash
pip install -r dependencies.txt
```

## Datasets
1. **Synthetic Linearly Separable Dataset**: Gaussian point clouds with an existing hyperplanar separator.
2. **Synthetic XOR Problem**: Canonical non-linearly separable benchmark highlighting linear threshold limits.
3. **Character Font Images**: Grayscale image representations of handwritten / computer characters (80-20 stratified train/test split).
