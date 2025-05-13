# Materials-ML-Predictor
# Bulk Modulus Prediction Using Machine Learning

This project trains a machine learning model to predict the **bulk modulus** of inorganic crystalline materials based on their chemical composition.

The model uses data from the **Materials Project** and features extracted via **Magpie descriptors** (using `matminer`).

---

- Predicts the bulk modulus of materials using ML regressors
- Trained on real DFT-derived elastic tensor data
- Applies Random Forest and Gradient Boosting regressors
- Evaluates model performance using RMSE and R²
- Visualizes results with scatter plots and feature importance charts
  
```
materials-ml-predictor/
├── notebooks/
│   └── bulk_modulus_prediction.ipynb     # Full ML pipeline notebook                            
├── requirements.txt                      # Dependencies
├── README.md                             # This file
└── LICENSE                               # Open source license
```
---
Technologies Used
- Python
- Scikit-learn
- Matminer
- Pymatgen
- Magpie descriptors
- Jupyter Notebook

---

You can adapt this notebook to:
- Predict other material properties (e.g., hardness, conductivity)
- Train on your own experimental data
- Integrate other ML models

---
  
[alpha4s](https://github.com/alpha4s)

