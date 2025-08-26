# Fraud Detection Case Study

**Purpose**  
Predict and prevent fraudulent transactions while minimizing friction for legitimate users.

## Project Overview
- Business goal: reduce fraud losses and protect trust.
- ML goal: score each transaction with a fraud risk probability and act above a threshold.

## Data
- Columns: step, type, amount, balances, isFraud, isFlaggedFraud
- Included: `data/sample/Fraud_sample_10k.csv` for demo
- Not included: full dataset (place it at `data/raw/Fraud.csv` locally)

## How to Run
```bash
python -m venv .venv && source .venv/bin/activate  # on Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/fraud_detection_case.ipynb
