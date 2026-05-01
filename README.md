# An Explainable Machine Learning Framework for Binary Classification Using Real-World Data

## Project Information

- Project Title: An Explainable Machine Learning Framework for Binary Classification Using Real-World Data
- Project Type: Research
- Submission Status: Submitted

## Team Details

- Jatin Ahuja — Roll Number: 2210991706
- Harshit Bagga — Roll Number: 2210991634

This repository contains a Jupyter notebook for binary classification analysis and local model explainability using LIME.

## Contents

- `binary_classification_lime.ipynb` - Main notebook demonstrating dataset loading, model training, evaluation, and LIME explanations.
- `dataset/` - Folder containing review and product data in TSV format.
  - `products-data-0.tsv`
  - `products-data-1.tsv`
  - `products-data-2.tsv`
  - `products-data-3.tsv`
  - `reviews-0.tsv`
  - `reviews-1.tsv`
  - `reviews-2.tsv`
  - `reviews-3.tsv`

## Project Overview

This project is focused on:

- Loading and exploring textual data for classification
- Building a binary classification model
- Evaluating model performance
- Explaining predictions using LIME (Local Interpretable Model-agnostic Explanations)

## Project Summary

This work uses real-world product and review data in TSV format to train a binary classifier that predicts outcomes from text features. The notebook includes data preparation, model training, evaluation, and interpretable predictions using LIME to show why individual decisions were made.

## Getting Started

### Prerequisites

- Python 3.8 or newer
- Jupyter Notebook / JupyterLab
- Common Python packages such as `pandas`, `scikit-learn`, `numpy`, and `lime`

### Running the Notebook

1. Install dependencies if needed:

```bash
pip install pandas scikit-learn numpy lime jupyter
```

2. Open the notebook:

```bash
jupyter notebook binary_classification_lime.ipynb
```

3. Run the notebook cells in order to explore the dataset, train a classifier, and generate LIME explanations.

## Notes

- The notebook is the main entry point for this project.
- The dataset files are tab-separated values (TSV) and are located in the `dataset/` directory.
- If you want to extend this project, consider adding a requirements file or a Python script for preprocessing and training.
