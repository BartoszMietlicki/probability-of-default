# Probability of Default (PD) Modeling — Synthetic Credit Risk Dataset

This project builds an end-to-end baseline for **Probability of Default (PD)** prediction using a **fully synthetic** credit risk dataset.  
The goal is to compare multiple modeling approaches and select the best-performing model based on robust evaluation metrics.

## What’s inside
- Data loading and quick exploratory analysis (EDA)
- Basic preprocessing and feature handling
- Training and evaluation of multiple models (e.g., linear / tree-based / boosting-style approaches)
- Model comparison using classification metrics and validation strategy
- Final model selection and short conclusions

## Data
The dataset used here is **synthetic** and provided in Parquet format:
- `data/pd_train.parquet`
- `data/pd_test.parquet`

## How to run
1. Clone the repository.
2. Install dependencies (at minimum: `pandas`, plus the libraries used by the selected models).
3. Run the main script / notebook:
   - `probability_of_default.py`
