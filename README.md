# Kaggle Competition: House Prices - Advanced Regression Techniques

This repository contains my work on the [Kaggle House Prices competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).  
It documents the complete workflow from data exploration to model building, along with the lessons learned during the process.

---

## 📆 Timeline

### 2025-08-30
- Repository initialized
- Loaded `train.csv` dataset in Kaggle Notebook
- Basic exploration: `.shape`, `.head()`

### 2025-08-31
- Conducted initial EDA
  - Inspected dataset structure with `.info()`, `.describe()`
  - Identified missing values (`PoolQC`, `MiscFeature`, `Alley`, `Fence`)
- Started documenting findings in Obsidian Vault, auto-synced to GitHub

---

## 📊 Project Workflow

1. **Exploratory Data Analysis (EDA)**
   - Data overview (`train.shape`, `info`, `describe`)
   - Missing value analysis
   - Distribution check of target variable (`SalePrice`)

2. **Data Preprocessing** (upcoming)
   - Handling missing values
   - Encoding categorical features
   - Feature scaling

3. **Modeling** (upcoming)
   - Baseline: Linear Regression, RandomForest
   - Cross-validation setup
   - Hyperparameter tuning with GridSearchCV / Optuna

4. **Evaluation & Submission** (upcoming)
   - Kaggle submission pipeline
   - Performance comparison and improvement log

---

## 🛠️ Tech Stack
- **Python**: Pandas, NumPy, Scikit-learn
- **Kaggle Notebooks**
- **GitHub**: version control
- **Obsidian**: experiment logs and notes (auto-sync with GitHub)

---

## 🎯 Goal
- Reproduce a full machine learning workflow for tabular data
- Build a reliable baseline and improve through feature engineering & tuning
- Document not only the results, but also the decision-making process
