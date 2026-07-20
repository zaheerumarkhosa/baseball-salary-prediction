# Baseball Player Salary Prediction

A machine learning project comparing Ridge and Lasso regression techniques for predicting professional baseball player salaries.

## Project Overview

This project demonstrates the application of regularized regression models on a real-world dataset. The goal is to predict player salary based on performance metrics and other features.

**Key Techniques:**
- Linear Regression
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)
- Feature Scaling & Normalization
- Categorical Encoding
- Train-Test Split

## Dataset

- **Total Records:** 322 players
- **Features:** 19 (includes statistics like AtBat, Hits, Runs, RBI, etc.)
- **Target Variable:** Salary
- **Missing Values:** Handled through removal

## Model Performance

| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | 313.239567899406   | 
| Ridge Regression  | 288.62308325272807 | 
| Lasso Regression  | 387.3533739552414  | 

## Key Learnings

### Ridge vs Lasso
- **Ridge Regression:** Shrinks all coefficients proportionally; keeps all features
- **Lasso Regression:** Can eliminate features entirely by setting coefficients to zero; performs feature selection
- **When to use Ridge:** When you believe all features are relevant
- **When to use Lasso:** When you suspect some features are not important

### Why Scaling Matters
Regularized models are sensitive to feature magnitude. StandardScaler ensures all features contribute equally to the regularization penalty.

## Files

- `Multiple Linear_Regression_Ridge_Lasso_Hitters` - Main analysis script
- `README.md` - This file
- `requirements.txt` - Python dependencies

## Installation

```bash
# Clone the repository
git clone <repo_url>

# Install dependencies
pip install -r requirements.txt

# Run the analysis
python baseball_salary_prediction.py
```

## Requirements

```
pandas>=1.0
numpy>=1.19
scikit-learn>=0.24
matplotlib>=3.3
```

## Author

Zaheer Umar- Data Science Student | Statistics Enthusiast

I'm learning machine learning & AI. This project is part of my DataCamp Associate Data Scientist in Python course.

**Connect with me:**
- LinkedIn:([https://linkedin.com/in/yourprofile](https://www.linkedin.com/in/zaheer-u-80743714a/))
- Email: zaheerumarkhosa@gmail.com

## Future Improvements

- [ ] Cross-validation for better model evaluation
- [ ] Hyperparameter tuning (GridSearchCV)
- [ ] Polynomial features exploration
- [ ] Visualizations: Feature importance, prediction vs actual
- [ ] Try other models (ElasticNet, Random Forest)

## License

This project is open source and available under the MIT License.

---


