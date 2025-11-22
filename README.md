# 💥 Prediction of LPG Blast Wave Pressure using Machine Learning - Group 5

This project focuses on developing machine learning models to accurately **predict the maximum blast wave overpressure** resulting from a Liquefied Petroleum Gas (LPG) explosion. This predictive capability is crucial for risk assessment and safety engineering in industrial and residential settings.

---

## 🚀 Key Features

* **Blast Wave Prediction:** Utilizes advanced regression models to predict overpressure based on input parameters (e.g., charge mass, distance).
* **Model Comparison:** Implements and compares the performance of a **Linear Regression Model** and a **Random Forest Regressor** baseline model against a highly optimized **XGBoost Regressor** final model.
* **Performance Metrics:** Achieved a high predictive accuracy, with the final XGBoost model reaching an **$R^2$ value of $0.86$**.
* **Model Explainability (SHAP):** Includes a comprehensive **SHAP (SHapley Additive exPlanations)** analysis to interpret feature importance and model decision-making. 

---

## 🛠️ Technology Stack

This project was developed entirely in **Python** within the **Google Colab** environment, leveraging key libraries for data processing, machine learning, and visualization.

| Category | Libraries Used |
| :--- | :--- |
| **Machine Learning** | `scikit-learn` (Linear Regression, RF, Utilities), `XGBoost`, `shap` |
| **Data Processing** | `pandas`, `numpy`, `OneHotEncoder`, `StandardScaler` |
| **Modeling & Analysis** | `statsmodels`, `scipy` (for statistical tests) |
| **Visualization** | `matplotlib.pyplot`, `seaborn` |
| **Model Optimization** | `RandomizedSearchCV` |

---
## 📝 Current Status & Future Work

| Status | Notes |
| :--- | :--- |
| **Model Performance** | XGBoost Final Model **$R^2 = 0.86$** |
| **Data** | The current analysis indicates a **need for additional data** to further improve the generalization and stability of the XGBoost and Random Forest models. |


```bash
