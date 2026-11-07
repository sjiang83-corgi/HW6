# DSCI 552 Homework 6

Shanglin Jiang

## Contents

- `notebook/Jiang_Shanglin_HW6.ipynb`: executed solutions to required Questions 1-5.
- `data/`: original APS training/test files and description.
- `results/`: figures, CV scores, and prediction tables.
- `requirements.txt`: dependencies, tested with Python 3.10.

## Run

Install dependencies with `pip install -r requirements.txt`. Open the notebook with
`notebook/` as its working directory, restart the kernel, and run all cells.
Full-data SMOTE and model fitting may take several minutes. No downsampling is used.
On macOS, XGBoost may require the OpenMP runtime (`brew install libomp`).

As required by footnote 1, validation and test batches use their own feature medians.
SMOTE is restricted to training folds. Scaling uses training-fold statistics only.
Question 6 is labeled Extra Practice and is not included.
