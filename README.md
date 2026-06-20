# Online News Popularity Prediction

Predicting the share count of online news articles using regression 
and neural network models - covering the full pipeline from data 
cleaning through model comparison and evaluation.

## What this project covers

The UCI Online News Popularity dataset contains 30K+ articles with 
features like content length, publish day, topic category, keyword 
statistics, and social engagement metrics.

This project builds and compares multiple predictive approaches:
- **Linear regression** - baseline model with feature selection
- **Regularized regression** - Ridge and Lasso to handle 
  multicollinearity across 58 features
- **Artificial Neural Network (ANN)** - feedforward network to 
  capture non-linear relationships
- **Feature importance analysis** - identifying key engagement 
  drivers (sentiment polarity, topic category, publish timing)

## Key findings

- Publish timing and topic category are stronger predictors than 
  content length
- ANN outperforms linear models on non-linear interaction effects
- Log-transforming the share count target substantially improves 
  model fit (right-skewed distribution)

## Tech stack

R (linear models, regularization) · Python (ANN, preprocessing) · 
RMarkdown · Jupyter

## Repository contents

- `Data Cleaning nd Preprocessing.ipynb` - cleaning pipeline, 
  feature engineering, outlier handling
- `Linear Models.Rmd` - regression analysis with model diagnostics
- `Regression Project cleaned.R` — consolidated R analysis script
- `RTSA Project ANN.ipynb` — neural network implementation 
  and comparison
- `Regression Project Report.pdf` - full written report with 
  methodology and results
