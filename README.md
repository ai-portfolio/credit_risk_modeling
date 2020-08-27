# credit_risk_modeling

## Objectives

1. Predict the Expected Loss (EL) based on EL = PD X LGD X EAD, where: 
    - PD: Probability of Default
    - LGD: Loss Given Default
    - EAD: Exposure at Default 
2. Deploy the predictive model as an API using FastAPI by [Sebastián Ramírez](https://fastapi.tiangolo.com/)

## Dataset

- [Kaggle Lending Club Loan Data]()

## Modeling Techniques

- Probability of Default (PD): Logistic regression
- Loss Given Default (LGD): Beta regression
- Exposure at Default (EAD): Beta regression

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
