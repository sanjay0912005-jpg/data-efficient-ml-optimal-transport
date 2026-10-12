Data-Efficient Machine Learning Using Optimal Transport

Project Overview

This project explores data-efficient machine learning by comparing a Logistic Regression baseline with an optimal transport-inspired classification approach on the Breast Cancer Wisconsin dataset.

The goal is to investigate how classification performance changes when different proportions of training data are used.

Objectives

- Evaluate classification performance at different training-data fractions.
- Compare a conventional machine learning baseline with an OT-inspired distance-based approach.
- Measure accuracy, balanced accuracy, and F1-score.
- Examine the limitations and potential of data-efficient classification methods.

Dataset

- Dataset: Breast Cancer Wisconsin dataset
- Source: scikit-learn
- Task: Binary classification

Methods

- Logistic Regression baseline
- Optimal transport-inspired distance-based classifier
- Training-data fractions: 10%, 20%, 40%, 80%, and 100%
- Repeated experiments using multiple random seeds

Evaluation

The experiments record accuracy, balanced accuracy, and F1-score. Results are saved in CSV files, and a graph compares model performance across training-data fractions.

Repository Contents

- "Data_Efficient_Machine_Learning_Using_Optimal_Transport.ipynb" — research notebook and experiments
- "final_validation_summary.csv" — summarized experimental results
- "final_validation_all_trials.csv" — results from individual trials
- "final_model_comparison.png" — model comparison graph

Limitations

This is an exploratory project using one dataset. The OT-inspired classifier should not be interpreted as a fully validated optimal transport method without further mathematical and experimental verification. Results may depend on the data split and experimental setup.

Future Work

- Test on additional datasets.
- Compare against a mathematically defined optimal transport classifier.
- Evaluate robustness across more random seeds and independent test splits.
- Investigate statistical significance and computational cost.

Tools

Python, scikit-learn, NumPy, pandas, Matplotlib, and Google Colab.
