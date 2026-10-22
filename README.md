# FTSE 100 ESG and Machine Learning Pipeline

## Project Overview

This repository contains the Python analysis pipeline developed for my MSc dissertation in International Corporate Finance and Banking at the University of Glasgow.

The project investigates the relationship between Environmental, Social and Governance (ESG) factors and the financial performance of FTSE 100 companies using statistical analysis and machine learning.

## Research Methods

The analysis includes:

- ESG and financial data cleaning and preparation
- Panel dataset construction
- Ordinary Least Squares (OLS) regression
- LASSO regression
- Random Forest
- Gradient Boosting and XGBoost
- Walk-forward cross-validation
- Portfolio backtesting
- Robustness and statistical significance testing
- SHAP-based model interpretation

## Repository Structure

```text
FTSE100-ESG-ML-Pipeline/
├── FTSE100_ESG_ML_Pipeline.ipynb
├── README.md
├── data/
│   └── Data.xlsx
├── saved_colab_outputs/
└── expected_outputs/
```

## Technologies Used

Python, Jupyter Notebook, pandas, NumPy, SciPy, scikit-learn, XGBoost, SHAP, Matplotlib and openpyxl.

## How to Run

1. Clone or download the repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy scipy scikit-learn openpyxl matplotlib xgboost shap
```

3. Open `FTSE100_ESG_ML_Pipeline.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook cells sequentially.
5. Compare the generated results against the files in `expected_outputs/`.

The `saved_colab_outputs/` folder contains previously generated XGBoost and SHAP results used by the notebook.

## Data Source

The research uses ESG and financial information obtained from LSEG Workspace. Data and derived outputs are subject to applicable licensing and redistribution permissions.

## Author

Navya Shahi  
MSc International Corporate Finance and Banking  
University of Glasgow

## Purpose

This repository documents the research methodology, machine learning implementation and reproducibility workflow developed for the dissertation.
