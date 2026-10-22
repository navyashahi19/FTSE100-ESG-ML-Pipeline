# FTSE 100 ESG & Machine Learning Pipeline

### Beyond Ratings: Can Machine Learning Unlock the True Value of ESG in Predicting FTSE 100 Returns?

**MSc Dissertation | International Corporate Finance and Banking | University of Glasgow**

**Python · Financial Analytics · Econometrics · Machine Learning · Model Interpretability · ESG · Portfolio Analytics**

## About the Project

Can machine learning uncover useful ESG signals that traditional sustainability ratings might overlook?

This question inspired my MSc dissertation, which explored whether Environmental, Social and Governance (ESG) information could help predict FTSE 100 stock returns.

Using **875 firm-year observations across 99 FTSE 100 companies**, I combined traditional econometric techniques with machine-learning models to investigate predictive relationships, identify influential ESG characteristics, and explore their potential relevance to investment decisions.

The analysis was developed using **Python and Jupyter Notebook**, with financial and ESG data sourced from LSEG Workspace.

## Key Findings

- **XGBoost delivered the strongest average out-of-sample performance**, achieving an R² of **0.036** and RMSE of **30.63**. The modest explanatory power highlights the challenges of predicting financial returns, even with advanced machine-learning techniques.

- **Individual ESG characteristics provided meaningful model insights.** Human Rights Policy, Product Responsibility, and Data Privacy Policy were among the important ESG contributors to predictions, suggesting that looking beyond composite ESG ratings may be valuable.

- **Exploratory portfolio results were encouraging.** An XGBoost-based portfolio achieved a Sharpe ratio of **2.09**, compared with **1.71** for an equally weighted benchmark. However, the backtest covered only six annual observations, so these results should be interpreted cautiously.

## Methodology

| Area | Techniques |
|---|---|
| Data preparation | pandas, NumPy, openpyxl |
| Econometrics | OLS, LASSO |
| Machine learning | Random Forest, Gradient Boosting, XGBoost |
| Model validation | Walk-forward cross-validation |
| Model interpretation | SHAP |
| Investment analysis | Portfolio backtesting and robustness testing |
| Visualisation | Matplotlib |

The workflow covers data cleaning, feature preparation, model training, out-of-sample evaluation, and interpretation of model predictions.

## Repository Structure

```text
FTSE100-ESG-ML-Pipeline/
├── FTSE100_ESG_ML_Pipeline.ipynb
├── README.md
├── data/
│   └── Data.xlsx
├── expected_outputs/
└── saved_model_outputs/
```

- **Notebook:** Main dissertation analysis and modelling pipeline.
- **data/:** Source financial and ESG dataset.
- **expected_outputs/:** Reference results from the analysis.
- **saved_model_outputs/:** Saved XGBoost and SHAP outputs.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/navyashahi19/FTSE100-ESG-ML-Pipeline.git
cd FTSE100-ESG-ML-Pipeline
```

Install the dependencies:

```bash
pip install pandas numpy scipy scikit-learn openpyxl matplotlib xgboost shap jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `FTSE100_ESG_ML_Pipeline.ipynb` to explore the research and code.

**Reproducibility note:** The notebook's end-to-end execution is currently being validated, including an update to the Excel data-import process. Previously generated outputs are available for reference.

## Skills Demonstrated

- Financial data analysis and quantitative research
- Python programming and data preprocessing
- Econometric and machine-learning modelling
- Out-of-sample validation and performance evaluation
- Explainable AI using SHAP
- Portfolio analytics and investment research

## Reflections

One of the most valuable lessons from this project was that **more sophisticated models do not necessarily make financial markets easy to predict**.

Although
