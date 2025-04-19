# 🐖 Pig Growth Modeling – Smart Farming Analytics

This project focuses on predicting pig weight using longitudinal agricultural data. We applied several statistical models (LME, GAM, GAMM) to understand the impact of covariates such as age, chest size, and species.

## 📌 Objectives

- Predict pig growth over time with interpretable models
- Identify key predictors using statistical inference
- Evaluate performance and residual behavior

## 🛠 Tools & Libraries

- **Language**: R  
- **Libraries**: `nlme`, `mgcv`, `ggplot2`, `dplyr`

## 📈 Models Used

- **LME (Linear Mixed Effects)** – for repeated measures structure  
- **GAM (Generalized Additive Models)** – for nonlinear trends  
- **GAMM** – combines both random effects and nonlinear patterns

## 🔍 Results Summary

- Age and chest circumference were the most influential predictors  
- GAMM provided the best balance between fit and interpretability  
- Residual diagnostics confirm model stability

## 📁 Structure

- `data/` : cleaned dataset  
- `scripts/` : R scripts for model fitting and evaluation  
- `figures/` : plots and diagnostics  
- `report/` : summary PDF or notebook (optional)

👤 – ENSIIE, 2025
