# Heart Disease Risk: Statistical Modeling Analysis

## Overview

This project analyzes demographic and clinical predictors of heart disease using inferential statistical methods. The objective is to identify which patient characteristics are significantly associated with heart disease and quantify the strength of those relationships.

The dataset contains 918 patient observations with demographic and cardiovascular indicators, including age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, exercise-induced angina, and heart disease diagnosis.

## Research Questions

1. Do demographic characteristics differ significantly between individuals with and without heart disease?
2. Are certain groups at significantly higher risk of developing heart disease?
3. Which clinical markers show the strongest statistical association with heart disease?

## Methods

This analysis incorporates multiple core statistical techniques:

- Exploratory Data Analysis (EDA)
- Summary statistics and visualization
- Independent t-tests (mean comparisons)
- Two-proportion z-tests
- Confidence interval estimation
- Bootstrapping for validation of results
- Formal hypothesis testing framework

Bootstrapping was applied to validate parametric results and assess robustness beyond normality assumptions.

## Key Findings

- Individuals with heart disease are, on average, several years older than those without heart disease.
- Males exhibit a significantly higher prevalence of heart disease compared to females.
- Elevated fasting blood sugar (>120 mg/dL) is strongly associated with heart disease.
- Exercise-induced angina and asymptomatic chest pain patterns show statistically significant differences in disease prevalence.

These findings align with established cardiovascular risk research and reinforce the role of demographic and metabolic risk factors in heart disease outcomes.

## Limitations

- Observational dataset limits causal inference.
- Sample contains disproportionate representation of males.
- Limited socioeconomic and lifestyle variables.
- Some missing values required imputation.

## Future Work

- Multivariate logistic regression modeling
- Interaction effect analysis
- Predictive risk modeling
- Incorporation of additional behavioral variables
