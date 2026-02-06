# Credit-Default-Risk-Prediction
This project builds an end-to-end machine learning model to predict loan default risk using historical lending data.
The focus goes beyond accuracy to include:
- Proper data preparation and leakage prevention
- Thoughtful handling of class imbalance
- Model evaluation using ROC-AUC, precision, recall, and confusion matrices
- Decision threshold tuning to reflect business trade-offs
- Model explainability using SHAP to understand key drivers of default risk
A Logistic Regression model was used as a baseline, followed by a Random Forest model achieving a ROC-AUC of ~0.72.
The project is designed to simulate how credit risk models support real lending decisions, not just predictions.

Tools: Python, Pandas, NumPy, Scikit-learn, SHAP, Matplotlib, Seaborn
