# Customer Churn Prediction

A machine learning project that predicts whether a Telco customer is likely to leave their subscription (`Churn`). The analysis and workflow are documented in [`code.ipynb`](code.ipynb).

## What the project does

- Explores customer and subscription data with visualizations.
- Prepares the data and encodes categorical features.
- Uses SMOTE to balance the training data.
- Compares Decision Tree, Random Forest, and XGBoost classifiers.
- Evaluates a Random Forest model and saves it for example predictions.

## Run it

From the project directory, install the notebook dependencies:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost jupyter
```

Open `code.ipynb` in Jupyter or VS Code and run the cells from top to bottom. The notebook reads `data/WA_Fn-UseC_-Telco-Customer-Churn.csv` and creates `encoders.pkl` and `customer_churn_model.pkl` in the project directory.

## Project files

- `code.ipynb` - exploration, training, evaluation, and prediction example.
- `data/WA_Fn-UseC_-Telco-Customer-Churn.csv` - input dataset.
- `encoders.pkl` and `customer_churn_model.pkl` - generated encoders and trained model.
