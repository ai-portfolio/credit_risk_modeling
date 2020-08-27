[![made-with-python](https://img.shields.io/badge/Built%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-sklearn](https://img.shields.io/badge/Built%20with-sklearn-1f425f.svg)](https://scikit-learn.org/)
[![made-with-jupyter](https://img.shields.io/badge/Built%20with-Jupyter-1f425f.svg)](https://jupyter.org/)
[![made-with-vscode](https://img.shields.io/badge/Built%20with-VS%20Code-1f425f.svg)](https://code.visualstudio.com/)
[![made-with-fastapi](https://img.shields.io/badge/Built%20with-FastAPI-1f425f.svg)](https://fastapi.tiangolo.com/)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ai-portfolio/credit_risk_modeling/graphs/commit-activity)

# credit_risk_modeling

## Objectives

- [ ] Predict the Expected Loss (EL) based on EL = PD X LGD X EAD, where: 
    - PD: Probability of Default
    - LGD: Loss Given Default
    - EAD: Exposure at Default 
- [ ] Deploy the predictive model as an API using FastAPI by [Sebastián Ramírez](https://fastapi.tiangolo.com/)

## Dataset

- [Kaggle Lending Club Loan Data]()

## Modeling Techniques

- [ ] Probability of Default (PD): Logistic regression
- [ ] Loss Given Default (LGD): Beta regression
- [ ] Exposure at Default (EAD): Beta regression

## Dependent Variables

- PD: Flag of whether the borrower defaulted or not (loan_status)
- LGD: How much of the loan was recovered (recoveries)
- EAD: Total exposure at moment of default compared to total exposure in the past (total recovered principal)

## Process

### 1. Data Gathering

- [ ] TODO: Add content

### 2. Exploratory Data Analysis (EDA)

- [ ] TODO: Add content

### 3. Feature Engineering

- [ ] TODO: Convert continuous to categorical variables for use as a scorecard
- [ ] TODO: Fine classing of categorical variables (equal intervals)
- [ ] TODO: Coarse classing of categorical variables (differing intervals)
- [ ] TODO: Convert categorical variables to dummy variables
