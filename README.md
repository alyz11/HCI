# Home Credit Default Risk — Credit Risk Modeling

## Files
- `home_credit_default_risk.ipynb`: end-to-end notebook for EDA, cleaning, feature engineering, Logistic Regression, Random Forest, evaluation, threshold analysis, and optional tuning.
- `application_train.zip`: required input data (not included in this project package by default).

## Run in Google Colab
1. Upload `home-credit-default-risk.zip` to the Colab session.
2. Open the notebook and run cells from top to bottom.
3. The notebook expects the ZIP at `/content/home-credit-default-risk.zip` in Colab, or `home-credit-default-risk.zip` in the current directory.
4. Download generated CSV metric/prediction outputs if needed.

## Baseline experiment
- Dataset: 307,511 rows × 122 columns.
- Target prevalence: 8.07% `TARGET=1`.
- Train sample: 50,000 rows from the 80% development partition.
- Holdout: 61,503 rows, stratified.
- Logistic Regression ROC-AUC: 0.748; PR-AUC: 0.231.
- Random Forest ROC-AUC: 0.740; PR-AUC: 0.218.
