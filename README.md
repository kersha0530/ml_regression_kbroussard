# ml_regression_kbroussard
# Regression Analysis: Predicting Medical Costs
# Author: Kbrousssard
# Date: April 16, 2925

## 📁 Repository Overview
This project applies linear and ensemble regression techniques to predict insurance charges using the Medical Cost dataset.

## 🔍 Dataset
- Source: [Kaggle - Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Stored in the `data` folder.

## 📓 Notebook
- [View the notebook](https://github.com/kersha0530/ml_regression_kbroussard/blob/main/regression_kbroussard.ipynb)

## 🤝 Peer Review
- [View peer review](https://github.com/kersha0530/ml_regression_kbroussard/blob/main/peer_review.md)

## ⚙️ Setup Instructions
1. Clone the repo: `git clone https://github.com/kersha0530/ml_regression_kbroussard.git`
2. Create virtual environment: `python -m venv .venv`
3. Activate it:
   - Windows: `.venv\Scripts\activate`
   - Mac/Linux: `source .venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Launch notebook: `jupyter notebook`

## ✅ Project Highlights
- Multiple regression models evaluated.
- Feature scaling, pipelines, and hyperparameter tuning applied.
- Final model performance explained using R², MAE, and RMSE.

## 🔍 Key Findings

- **Top Predictors**: Smoking status, age, and BMI were the most significant predictors of medical costs.
- **Strong Performance**: Linear Regression and Polynomial Regression performed well, with R² scores reaching up to 0.79.
- **Feature Importance**: Random Forest and Linear Regression coefficient analysis showed consistent patterns, validating the importance of the chosen features.
- **Effective Engineering**: Creating interaction features (e.g., smoker × BMI) and scaling improved model accuracy and generalization.
- **Challenges Overcome**: Feature encoding and proper splitting were critical for avoiding skewed predictions.
- **Future Ideas**: I’d explore additional interaction terms and try regularization techniques like Ridge or Lasso Regression to reduce overfitting.

