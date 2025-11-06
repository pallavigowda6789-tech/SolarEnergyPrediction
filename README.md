# Solar Energy Prediction

This project predicts daily solar energy output using machine learning.  
It includes data preprocessing, feature engineering, Random Forest and XGBoost models, and a next-day prediction function.

## Project Structure

## Features
- Multi-site solar energy data processing
- Feature engineering: lag features, date features
- Random Forest regression with overfitting fixes
- Optional XGBoost for comparison
- Next-day prediction function with interactive inputs
- Visualizations: residual plots, feature importance

## Usage
1. Upload the dataset to Google Drive: `/MyDrive/solar_data/`
2. Open `SolarEnergy_Prediction.ipynb` in Google Colab
3. Mount Google Drive and run all cells
4. Predict next-day solar energy using the interactive input

## Dependencies
Install required packages:
```bash
pip install -r requirements.txt
