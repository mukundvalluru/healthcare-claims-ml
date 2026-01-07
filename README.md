# Healthcare Utilization Prediction Using Machine Learning

## Overview
This project applies machine learning techniques to healthcare claims data
to predict patient utilization, measured as expected days of hospitalization.
The goal is to support data-driven healthcare risk assessment and resource
planning through predictive analytics.

---

## Problem Statement
Healthcare providers and payers must anticipate patient utilization to
effectively manage costs, capacity, and quality of care. Traditional
rule-based approaches often fail to capture the complexity of patient
behavior and clinical history.

This project addresses the question:
- Can historical claims data be used to accurately predict future
  hospitalization utilization at the patient level?

---

## Data
The dataset consists of healthcare claims records with information related to:
- Patient demographics
- Diagnosis and procedure indicators
- Treatment history and utilization patterns

**Data Confidentiality Notice**  
The dataset used in this project is confidential and cannot be shared publicly.
As a result:
- Raw data files are not included in this repository
- All feature engineering, modeling logic, and evaluation methodology are shown
- Results presented were produced using the confidential dataset

The analysis is reproducible using an equivalent healthcare claims dataset
with a similar schema.

---

## Methodology

### Feature Engineering
- Aggregation of claims history at the patient level
- Encoding of categorical medical variables
- Handling sparsity common in healthcare data
- Transformation of utilization metrics

### Modeling Approach
Multiple models were evaluated to predict hospitalization utilization:
- Linear regression baselines
- Tree-based models
- Neural networks with L2 (ridge) regularization

Model selection focused on balancing predictive performance and
generalization.

### Evaluation
- Error-based metrics for regression performance
- Comparison across model families
- Assessment of overfitting and stability

---

## Results (Highlights)
- Neural network models achieved lower prediction error compared to baselines
- Regularization improved generalization on unseen data
- Engineered utilization and diagnosis features were strong predictors
  of hospitalization risk

---

## Key Learnings
- Feature engineering is critical for extracting signal from claims data
- Regularization is necessary due to high dimensionality and sparsity
- Machine learning models can meaningfully support healthcare resource
  planning and risk stratification

---

