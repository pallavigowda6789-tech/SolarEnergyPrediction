
# ☀️ Solar Energy Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-RandomForest-orange)
![License](https://img.shields.io/badge/License-MIT-green)

This project predicts daily solar energy output (Power Generation) using machine learning techniques.  
It covers end-to-end processes — from data preprocessing and feature engineering to model training, evaluation, and next-day power prediction.

---

## 📂 Project Structure



SolarEnergyPrediction
|
├─ SolarEnergy_Prediction.ipynb   
├─ README.md                     
├─ requirements.txt              
├─ .gitignore                     
└─ sample_data/




## 🚀 Features

- 🔹 Multi-site solar data preprocessing (date/time merging, cleaning)
- 🔹 Feature Engineering:
  - Time-based features (hour, day, month, etc.)  
  - Lag & rolling mean features for time series modeling  
  - Cyclical encoding for temporal patterns
- 🔹Modeling Approaches: 
  - RandomForestRegressor (primary model)  
  - XGBoostRegressor (for performance comparison)
- 🔹 Model Evaluation: MAE, RMSE, MAPE, and R² Score
- 🔹 Next-Day Power Prediction: Interactive user input for forecasting
- 🔹 Visualization Tools:  
  - Feature importance plot  
  - Residual and correlation analysis  

---

## 🧠 Dataset

- The dataset is based on the [Kaggle Solar Energy Dataset](https://www.kaggle.com/).  
- A smaller sample (Plant_1.csv, Plant_2.csv, Weather-1 , Weather_2) is provided in sample_data for testing.
- To use the full dataset, download it from Kaggle and place it in your Google Drive:




## ⚙️ Usage

1. Open the notebook SolarEnergy_Prediction.ipynb in Google Colab.  
2. Mount Google Drive to access the dataset:

python
from google.colab import drive
drive.mount('/content/drive')


3. Run all cells sequentially.
4. Use the final function to perform next-day power output predictions interactively.

---

## 📊 Model Performance Summary

| Metric                |    Target   |     Achieved    |          Result          |
| :---------------------| :---------: | :-------------: | :----------------------: |
| MAE                   |     0.04    |       0.03      |           ✅ MET         |
| RMSE                  |     0.09    |       0.11      | ⚠️ Slightly Above Target |
| MAPE                  |    7.20%    |      0.82%      |        ✅ Excellent      |
| R² Score (Train/Test) | 0.99 / 0.99 | ✅Excellent Fit|                           |

> The Random Forest model achieved an R² score of 0.9999, explaining nearly all variance in solar power output.
> Minimal difference between training and test performance indicates strong generalization and no overfitting.

---

## 🧮 Installation

Install all required dependencies:

bash
pip install -r requirements.txt


If running locally, ensure you have:

* Python ≥ 3.10
* Jupyter Notebook or Google Colab
* Required libraries: pandas, numpy, matplotlib, scikit-learn, etc.

---

## 📈 Future Enhancements

* Incorporate real-world weather data APIs for live predictions
* Add LSTM/Prophet models for advanced time series forecasting
* Build a web dashboard (using Streamlit or Flask) for interactive analysis

---

## 📜 License

This project is licensed under the MIT License — you’re free to use, pull request , and distribute it.

---

### 🌟 Author

Developed by Pallavi G S 
📧 For the internship Project at Edunet Foundation in association with Shell 

---

```
