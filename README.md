# Breast Cancer Detection Using Random Forest

## Project Overview

This project uses supervised machine learning to classify breast tumors as malignant or benign based on diagnostic features.

The objective is to explore the dataset, identify meaningful patterns, train a Random Forest classifier, and evaluate its predictive performance.

## Objectives

- Perform Exploratory Data Analysis (EDA).
- Analyze feature distributions and correlations.
- Build a Random Forest classification model.
- Evaluate performance using classification metrics.
- Interpret feature importance and model limitations.

## Dataset

The dataset contains 569 observations and 30 numerical predictor features, along with a target variable.

- `0` — Malignant
- `1` — Benign

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Dataset loading and inspection
2. Missing-value and duplicate checks
3. Exploratory Data Analysis
4. Feature-target separation
5. Stratified train-test split
6. Random Forest model training
7. Model evaluation
8. ROC-AUC analysis
9. Cross-validation
10. Feature importance analysis

## Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 95.61% |
| ROC-AUC | 99.37% |
| Mean 5-Fold CV Accuracy | 95.61% |

## Key Learnings

- How to perform EDA for a classification problem.
- Why stratified sampling is useful.
- How to interpret a confusion matrix and classification report.
- Why accuracy alone is insufficient for medical classification.
- How to evaluate feature importance and model generalization.

## Limitations

- The dataset is relatively small.
- Results depend on the dataset and evaluation procedure.
- External validation is necessary before considering real-world clinical use.
- Feature importance indicates predictive contribution, not causation.

## Disclaimer

This project is for educational and interview preparation purposes only. It is not intended for clinical diagnosis or medical decision-making.

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open `breast_cancer_detection.ipynb` in Jupyter Notebook.
4. Ensure the dataset path is correct.
5. Run the notebook cells in order.