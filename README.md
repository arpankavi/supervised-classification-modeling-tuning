# Supervised Classification Modeling & Tuning

## Contents
- `supervised_classification_modeling_tuning.ipynb`: end-to-end notebook.
- `requirements.txt`: Python dependencies.
- Outputs generated when notebook runs: `champion_model.joblib`, `model_comparison.csv`.

## What it does
- Uses the built-in Scikit-learn Breast Cancer Wisconsin dataset.
- Trains and tunes Logistic Regression, Random Forest, Extra Trees, and Histogram Gradient Boosting.
- Uses `GridSearchCV` with stratified 5-fold cross-validation and ROC-AUC scoring.
- Evaluates with Precision, Recall, F1-score, ROC-AUC, ROC curves, and confusion matrix.
- Selects a champion model and serializes it with Joblib.

## Run it
1. Open the notebook in Google Colab or Jupyter.
2. Install dependencies from `requirements.txt` if needed.
3. Run all cells from top to bottom.
4. Commit the notebook and generated outputs (optional) to a public GitHub repository for proof.

## Important note
This is an educational ML benchmark, not a medical diagnostic tool.
