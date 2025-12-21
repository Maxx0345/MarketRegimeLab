# Market Regime Detection (HMM & Machine Learning)

This project focuses on **detecting financial market regimes** using **Hidden Markov Models (HMM)** and **Machine Learning techniques** applied to financial market data.

The objective is to identify **latent market regimes** (e.g. calm, volatile, crisis) and use them as inputs for downstream predictive models.

---

## What This Project Does

- Downloads financial market data from **Yahoo Finance**
- Computes economically interpretable features (returns, realized volatility)
- Detects regimes using an **unsupervised Gaussian HMM**
- Uses detected regimes as labels for **supervised ML models**
- Visualizes market regimes directly on price series

---

##  Installation

### Core scientific stack
```bash
pip install pandas numpy scipy scikit-learn matplotlib seaborn
```
Market data
```
pip install yfinance
```
Regime detection
```
pip install hmmlearn
```

If hmmlearn fails to install:
```
pip install --upgrade pip setuptools wheel
pip install hmmlearn
```
Machine Learning (optional)
```
pip install xgboost
```

Deep Learning (optional – LSTM, NN)
```
pip install tensorflow
```

 ### Disclaimer :
For educational and research purposes only.
