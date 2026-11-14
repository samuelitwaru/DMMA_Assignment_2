# DSC8307 Assignment 2 - Data Mining, Modeling and Analytics

Two independent, self-contained Jupyter notebooks for Assignment 2

## Contents

- `wholesale_customers.ipynb` - Project 1: segments 440 wholesale customers by spending
  behaviour (cluster tendency, K-Means vs Ward vs DBSCAN/HDBSCAN, named segments and
  recommendations) from `data/wholesale-customers.csv`.
- `creditcard_fraud.ipynb` - Project 2: ranks credit-card transactions for fraud investigation
  (statistical outlier baseline, cluster-based and classification-based detectors, evaluated
  against withheld labels) from `data/creditcard.csv.gz`.
- `data/` - copies of the provided datasets. `creditcard.csv`
- `requirements.txt` - project dependencies.

## How to run

```bash
python -m venv .venv
.venv\Scripts\activate        # Windows  (source .venv/bin/activate on macOS/Linux)
pip install -r requirements.txt
jupyter notebook
```

