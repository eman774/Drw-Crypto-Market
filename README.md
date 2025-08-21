# DRW Crypto Market Prediction

This repository contains my notebook for the **[DRW Crypto Market Prediction Competition on Kaggle](https://www.kaggle.com/competitions/drw-crypto-market-prediction)**.  
The project focuses on building an advanced machine learning pipeline for predicting cryptocurrency market trends using **XGBoost** and **LightGBM**.

---

## 📌 Project Overview

The cryptocurrency market is known for its volatility and unpredictability.  
In this project, I aimed to analyze the competition dataset, perform thorough preprocessing, and build gradient boosting models to capture hidden market patterns.  

The notebook demonstrates:
- Efficient **data loading and memory optimization**  
- Handling missing and infinite values  
- Feature selection using **SelectKBest (f_regression)**  
- Data visualization and target distribution analysis  
- Model training using **XGBoost** and **LightGBM**  
- Evaluation with **RMSE** and training time comparison  
- Feature importance analysis  
- Final **Kaggle submission file** generation  

---

## 📊 Dataset

The dataset was provided by Kaggle as part of the competition and consists of:  
- **Train parquet file**: Market features + target label  
- **Test parquet file**: Market features for prediction  
- **Sample submission**: Required format for Kaggle submission  

---

## ⚙️ Project Structure

- drw-crypto-market/

│── drw-crypto-market.ipynb

│── README.md 


---

## 🛠️ Installation & Requirements

To run this project, you need **Python 3.8+** with the following dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm

```
---
## 🚀 Usage

Clone the repository:
```bash
git clone https://github.com/your-username/drw-crypto-market.git
cd drw-crypto-market

```

Open and run the notebook:
```bash
jupyter notebook drw-crypto-market.ipynb

```

---

## 📈 Models & Evaluation

### The notebook compares two state-of-the-art boosting algorithms:

- XGBoost (gpu_hist tree method)

- LightGBM

### Metrics:

- Root Mean Squared Error (RMSE)

- Training Time (seconds)

- Results are visualized through:

- Bar plots for RMSE and training time

- RMSE over boosting rounds

- Top 20 feature importances for both XGBoost and LightGBM

---

## 🔮 Results

- Both XGBoost and LightGBM achieved strong predictive performance on the validation set.

- LightGBM was slightly faster, while XGBoost provided competitive RMSE.

- Feature importance analysis revealed the most influential predictors.

- Final predictions were saved in submission.csv and submitted to Kaggle.

 ---
 
## 📌 Future Work

- Hyperparameter tuning using GridSearchCV or Optuna

- Ensemble learning (stacking/blending XGBoost and LightGBM)

- Incorporating deep learning approaches (e.g., LSTM/GRU) for time-series modeling

- Adding domain-specific features to improve accuracy

---

## 👤 Author

### Eman Hisham

### Kaggle Notebook: **[DRW Crypto Market]([https://www.kaggle.com/competitions/drw-crypto-market-prediction](https://www.kaggle.com/code/emanhishamismail/drw-crypto-market))**

