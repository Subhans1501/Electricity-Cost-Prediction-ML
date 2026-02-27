# # Electricity Cost Prediction Engine
### # Supervised Learning | Linear Regression Analysis

This project implements a predictive model to estimate electricity costs (in USD) for various site locations based on structural characteristics and consumption metrics. The model demonstrates high predictive accuracy, effectively explaining 92% of the variance in utility costs.

---

# # Key Implementation Details

## # Data Engineering & Preprocessing
* **Feature Selection**: Utilized features including site area, water consumption, recycling rates, and resident count to predict costs.
* **Categorical Encoding**: Implemented **One-Hot Encoding** for categorical features like `structure type` (Industrial, Mixed-use, Residential).
* **Validation Strategy**: Utilized a `train_test_split` with 20% of data reserved for testing to ensure robust evaluation.

## # Model Performance
The model was evaluated using standard regression metrics, showing strong predictive power:
* **R-squared (R²)**: **0.92**
* **Mean Absolute Error (MAE)**: **245.65**


## # Sample Prediction Analysis
For a sample industrial site (1,447 site area, 1,000 water consumption):
* **Predicted Electricity Cost**: **2,655.23 USD**
* **Actual Electricity Cost**: **2,027.00 USD**

---

# # Technical Toolbox
* **Language**: Python 3
* **Libraries**: Pandas, Scikit-learn (LinearRegression, Metrics)
* **Infrastructure**: Kaggle Notebook / Jupyter

---

# # Developer Information
* **Developer**: Muhammad Subhan Shahid
* **Affiliation**: FAST-NUCES