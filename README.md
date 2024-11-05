# Insurance Cost Predictor with Explainable AI

This project builds an **Insurance Cost Predictor** using XGBoost and employs explainable AI techniques, specifically SHAP (SHapley Additive exPlanations), to make model predictions 
interpretable and transparent.

## Project Overview

The goal of this project is to predict insurance charges based on demographic and lifestyle factors such as age, BMI, smoking status, and region. By using SHAP, the model provides 
insights into how each feature contributes to individual predictions, enhancing transparency and trust in model decisions.

## Features

- **Data Preprocessing**: Categorical encoding, handling nulls, and feature engineering to prepare the data.
- **Model Training**: Using XGBoost to create a predictive model for insurance costs.
- **Explainability with SHAP**:
  - **Bar Plot**: Shows global feature importance, ranking features based on their impact on predictions.
  - **Waterfall Plot**: Displays individual prediction explanations, detailing how each feature influences the outcome.
  - **Dependence Plot**: Visualizes the interaction of key features with predictions, highlighting non-linear relationships.

## Technologies Used

- Python
- XGBoost
- SHAP for explainability
- Pandas, Matplotlib for data handling and visualization

## Getting Started

### Prerequisites

To run this project, you need:
- Python 3.6 or higher
- Jupyter Notebook (optional)
- Required libraries: `xgboost`, `shap`, `pandas`, `matplotlib`

Install the required libraries with:

```bash
pip install xgboost shap pandas matplotlib
```


### Usage
insurance-cost-predictor-with-explainable-ai-shap.ipynb: Jupyter Notebook for running the project step-by-step.
