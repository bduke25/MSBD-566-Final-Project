# MSBD-566-Final-Project
# Predicting Adverse Birth Outcomes

MSBD 566 Final Project by Brandi Duke and Jerchelle Jean-Poix

## What this project does
We use machine learning to predict three outcomes from mothers' demographics, behaviors, and prenatal care: low birth weight, preterm birth, and both together. We use CDC 2024 U.S. birth data and compare three models: Logistic Regression, Random Forest, and XGBoost.

## Where to get the data
The data file is too big for GitHub. Download the 2024 U.S. natality file (natality2024us.csv) from the NBER natality data page and save it in your Google Drive.

## How to run the code
1. Open the notebook file in this repository in Google Colab.
2. Install the packages listed in requirements.txt.
3. Click Runtime, then Restart and run all.

The notebook runs in order from top to bottom: setup, data loading, cleaning, exploratory analysis, model training, evaluation, and SHAP interpretation.

## Notes
The random seed is fixed at 42, so results should be the same each time. See our manuscript for limitations.
