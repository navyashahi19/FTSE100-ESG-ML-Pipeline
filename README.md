# FTSE 100 ESG & Machine Learning Pipeline

**MSc Dissertation | International Corporate Finance and Banking | University of Glasgow**

**Python | Financial Analytics | Machine Learning | Econometrics | Explainable AI**

## Project Overview

This project investigates the relationship between Environmental, Social and Governance (ESG) performance and financial characteristics of FTSE 100 companies.

Using financial and ESG data from **LSEG Workspace**, the research combines traditional econometric techniques with machine-learning models to explore predictive relationships, evaluate model performance, and interpret the contribution of ESG indicators.

The analysis was developed in **Python using Jupyter Notebook** as part of my MSc dissertation.

## Research Objectives

- Examine relationships between ESG indicators and financial outcomes.
- Compare econometric and machine-learning approaches.
- Evaluate predictive performance using time-aware validation.
- Interpret model predictions through explainable AI.
- Explore the financial relevance of model outputs through portfolio backtesting.

## Methodology

| Component | Methods |
|---|---|
| Data preparation | pandas, NumPy, openpyxl |
| Econometrics | OLS Regression, LASSO |
| Machine learning | Random Forest, Gradient Boosting, XGBoost |
| Model validation | Walk-forward cross-validation |
| Explainable AI | SHAP |
| Financial analysis | Portfolio backtesting and robustness testing |
| Visualisation | Matplotlib |

The workflow covers data cleaning, feature preparation, model training, performance evaluation, and interpretation.

## Dataset

**Source:** LSEG Workspace  
**Coverage:** FTSE 100 companies

The dataset includes ESG scores, environmental, social and governance pillar scores, company financial measures, stock-return information, and sector classifications.

Data availability and reporting periods vary across companies.

## Repository Structure

```text
FTSE100-ESG-ML-Pipeline/
│
├── FTSE100_ESG_ML_Pipeline.ipynb
├── README.md
├── data/
│   └── Data.xlsx
├── expected_outputs/
└── saved_colab_outputs/
```

- **Notebook:** Complete research and modelling workflow.
- **data/:** Source Excel dataset.
- **expected_outputs/:** Reference analysis results.
- **saved_colab_outputs/:** Saved XGBoost and SHAP outputs.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/navyashahi19/FTSE100-ESG-ML-Pipeline.git
cd FTSE100-ESG-ML-Pipeline
```

Install the required packages:

```bash
pip install pandas numpy scipy scikit-learn openpyxl matplotlib xgboost shap jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `FTSE100_ESG_ML_Pipeline.ipynb` to explore the analysis.

**Execution status:** The complete notebook is undergoing reproducibility validation, including an update to the Excel data-import process. Previously generated results are available in the repository for reference.

## Skills Demonstrated

- Financial data analysis and quantitative research
- Python programming and data preprocessing
- Econometric modelling and statistical analysis
- Machine-learning model development and evaluation
- Time-series-aware validation
- Explainable AI and feature interpretation
- Portfolio analytics and investment research

## Limitations

ESG scores are dependent on provider methodologies, and financial relationships may vary across market conditions. Predictive associations do not establish causality, and historical backtesting does not guarantee future investment performance.

## Author

**Navya Shahi**  
MSc International Corporate Finance and Banking  
University of Glasgow

---

*Academic research project. Not financial or investment advice.*

*Data sourced from LSEG Workspace. Redistribution and reuse are subject to applicable licensing permissions.*
