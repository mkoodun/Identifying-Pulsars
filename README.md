# Identifying-Pulsars

Classifying astronomical radio signals as **pulsars** or **non-pulsars** using machine learning.

## Overview
Developed **Decision Tree** classifiers to identify pulsar candidates in the [HTRU2 dataset](https://archive.ics.uci.edu/dataset/372/htru2).

- **Baseline model**: Showed significant overfitting on training data.
- **Model tuning**: Imporved generalisation, achieving **84% recall** on the test set.

## Dataset
- Source: UCI Machine Learning Repository - HTRU2

## Methodology
The full pipeline (data preprocessing, model training, evaluation, and improvements) is documented in the [Jupyter Notebook](https://github.com/mkoodun/Identifying-Pulsars/blob/main/Code.ipynb).

## Tech Stack
- Python (Jupyter Notebook)
- Numpy, Pandas, Scikit-learn
- Matplotlib, Seaborn

## Future Work
- Apply **nested cross-validation** to obtain more reliable generalisation performance estimates.
- Experiment with **feature selection** methods to optimise classification accuracy and improve interpretability.

---

Project originally completed on **7 March 2025** and published publicly as part of portfolio consolidation.

---
