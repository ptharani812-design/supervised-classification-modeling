# Task 04 — Supervised Classification / Regression Modeling & Tuning

## Deliverables
- `Supervised_Classification_Modeling_Tuning.ipynb` — complete notebook for training, tuning, comparing, evaluating, and saving a champion model.
- `requirements.txt` — Python libraries needed to run the notebook.
- `SUBMISSION_STEPS.md` — steps to run in Google Colab and submit the public notebook/repository link.

## Models and methods
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Gradient Boosting

The notebook includes numeric/categorical preprocessing, missing-value imputation, one-hot encoding, scaling, `GridSearchCV`, `StratifiedKFold`, weighted precision/recall/F1, accuracy, ROC-AUC where possible, a model comparison table, confusion matrix, ROC curve, champion selection, and `joblib` serialization.

## Dataset
Use `customer-churn-training.csv` from your Task 03 project. The CSV is intentionally not included in this package because the earlier data-card notes that permission to publicly share customer data has not been established. Upload the CSV privately to your Colab session before running the notebook.

## Important limitation
The previously supplied dataset has only 12 records. Model scores, cross-validation results, and the selected model may change substantially with a different split. This is an educational demonstration, not a reliable production model. Confirm feature timing, target definition, data provenance, and permission before any real-world use.
