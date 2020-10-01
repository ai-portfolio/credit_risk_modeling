# credit_risk_modeling

[![made-with-python](https://img.shields.io/badge/Built%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-sklearn](https://img.shields.io/badge/Built%20with-sklearn-1f425f.svg)](https://scikit-learn.org/)
[![made-with-jupyter](https://img.shields.io/badge/Built%20with-Jupyter-1f425f.svg)](https://jupyter.org/)
[![made-with-vscode](https://img.shields.io/badge/Built%20with-VS%20Code-1f425f.svg)](https://code.visualstudio.com/)
[![made-with-fastapi](https://img.shields.io/badge/Built%20with-FastAPI-1f425f.svg)](https://fastapi.tiangolo.com/)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ai-portfolio/credit_risk_modeling/graphs/commit-activity)

## Objectives

- [ ] Predict the Expected Loss (EL) based on EL = PD X LGD X EAD, where:
    - PD: Probability of Default
    - LGD: Loss Given Default
    - EAD: Exposure at Default
- [ ] Deploy the predictive model as an API using FastAPI by [Sebastián Ramírez](https://fastapi.tiangolo.com/)

## Dataset

- [Kaggle Lending Club Loan Data](https://www.kaggle.com/wendykan/lending-club-loan-data/version/1)

## Modeling Techniques

- [ ] Probability of Default (PD): Logistic regression
- [ ] Loss Given Default (LGD): Beta regression
- [ ] Exposure at Default (EAD): Beta regression

## Dependent Variables

- PD: Flag of whether the borrower defaulted or not (loan_status)
- LGD: How much of the loan was recovered (recoveries)
- EAD: Total exposure at moment of default compared to total exposure in the past (total recovered principal)

## File Structure

```{}
credit_risk_modeling
├── README.md               <- The top-level README for users of this site
├── .gitignore
├── LICENSE
├── main.py                 <- FastAPI script
├── model.py                <- script for the classifier class object
├── requirements.txt        <- file listing all required libraries
└── lib/
    ├── data/               <- data not uploaded to GitHub (excluded in .gitignore)
    |   ├── processed/
    |   └── raw/
    ├── figures/
    ├── models/             <- joblib models for import into API script
    ├── notebooks/          <- Jupyter notebooks for exploratory data analysis
    └── tests/              <- joblib models for import into API script
```

## Process

### 1. Environment Setup

- [x] Create a project folder

```{}
$mkdir credit_risk_modeling
$cd credit_risk_modeling
```

- [x] Create and activate a new virtual environment (using Miniconda installation)

```{}
$conda create --name credit_risk python=3.7
$conda activate credit_risk
```

- [x] Install required python libraries

```{}
(credit_risk) $pip install -r requirements.txt
```

- [x] Install Jupyter Lab and/or Notebook in virtual environment

```{}
(credit_risk) $pip install jupyterlab
(credit_risk) $pip install notebook
(credit_risk) $pip freeze > requirements.txt
```

- [ ] 

### 1. Data Gathering

- [x] For this project, I decided to use [Dask](https://dask.org/) to ingest the data faster
- [x] Data was pulled from [Kaggle](https://www.kaggle.com/wendykan/lending-club-loan-data/version/1)

### 2. Exploratory Data Analysis (EDA)

- [ ] TODO: Add content

### 3. Feature Engineering

- [ ] TODO: Convert continuous to categorical variables for use as a scorecard
- [ ] TODO: Fine classing of categorical variables (equal intervals)
- [ ] TODO: Coarse classing of categorical variables (differing intervals)
- [ ] TODO: Convert categorical variables to dummy variables
