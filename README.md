
# Solar Energy Prediction 🌞

![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This project predicts **daily solar energy output** using machine learning.  
It includes data preprocessing, feature engineering, and models like **Random Forest** and **XGBoost**, along with next-day prediction functionality.

---

## Project Structure
```

SolarEnergyPrediction/
│
├─ SolarEnergy_Prediction.ipynb   # Main Colab notebook
├─ README.md                      # Project description
├─ requirements.txt               # Python dependencies
├─ .gitignore                     # Ignored files
└─ sample_data/
└─ Plant_1.csv              # Sample dataset (small subset)

```

---

## Features
- Multi-site solar energy data processing
- Feature engineering: lag features, date features
- Random Forest regression with overfitting fixes
- Optional XGBoost for comparison
- Next-day prediction function with interactive input
- Visualizations: residual plots, feature importance

---

## Dataset
- **Full dataset** is from [Kaggle Solar Energy Dataset](https://www.kaggle.com/).  
- For testing, a **small sample** (`Plant_1.csv`) is included in `sample_data/`.  
- To use the full dataset, download it from Kaggle and upload it to Google Drive:  
```

/Drive/solar_data/

````

---

## Usage
1. Open `SolarEnergy_Prediction.ipynb` in **Google Colab**.  
2. Mount Google Drive and load the dataset:

```python
from google.colab import drive
drive.mount('/content/drive')
````

3. Run all notebook cells.
4. Use the **next-day prediction function** to predict solar energy for a given site.

---

## Installation

Install all required Python libraries:

```bash
pip install -r requirements.txt
```

---

## License

MIT License

---

