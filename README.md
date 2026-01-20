# Mine The Model

A time series forecasting project for predicting stock closing prices over the next 100 trading days. This notebook implements multiple forecasting approaches including ARIMA, LSTM, and Prophet models to analyze historical stock data and generate future predictions.

## Project Overview

This project tackles the **Mine The Model 2023** competition challenge, which involves:
- Analyzing historical stock price data (Close, Open, High, Low, Volume)
- Building time series models to forecast future closing prices
- Predicting the next 100 trading days (excluding weekends) for 50 different stocks
- Comparing multiple forecasting approaches (Linear Regression, ARIMA, Prophet, LSTM)

**Key Features:**
- Lag feature engineering for baseline models
- ARIMA with Box-Cox transformation for variance stabilization
- Grid search optimization for ARIMA hyperparameters (p, d, q)
- Auto-ARIMA for automated parameter selection
- Moving average analysis
- Outlier detection and handling (IQR method)
- Train/test split validation with visualization

**Contents**
- `mine-the-model.ipynb` — primary notebook with the project's code and analysis.

**Prerequisites**
- Python 3.8+ and Jupyter (or JupyterLab).
- Recommended: create and use a virtual environment.

**Setup**
1. Clone the repo:

   git clone <your-repo-url>
2. (Optional) Create and activate a virtual environment:

   python -m venv .venv
   source .venv/bin/activate
3. Install dependencies (if you have a `requirements.txt`):

   pip install -r requirements.txt

If there is no `requirements.txt`, open the notebook and install packages shown in the first cells.

**Usage**
1. Start Jupyter Lab or Notebook:

   jupyter lab

2. Open `mine-the-model.ipynb` and run the cells.

**Committing & Pushing to GitHub**
1. Initialize a repo (if not already):

   git init
   git add .
   git commit -m "chore: add project notebook and README"
2. Add GitHub remote and push:

   git remote add origin <git-remote-url>
   git branch -M main
   git push -u origin main

**License**
This repository does not include a license file by default. Add a `LICENSE` if you want to specify reuse terms (e.g., MIT).

**Contact / Notes**
- If you'd like, I can add a `requirements.txt` generated from the notebook or expand this README with more details.
