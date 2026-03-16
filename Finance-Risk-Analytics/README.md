```
╔══════════════════════════════════════════════════════════════════════════════════╗
║  ██████╗ ██╗███████╗██╗  ██╗     █████╗ ███╗   ██╗ █████╗ ██╗  ██╗   ██╗███████╗║
║  ██╔══██╗██║██╔════╝██║ ██╔╝   ██╔══██╗████╗  ██║██╔══██╗██║  ╚██╗ ██╔╝██╔════╝║
║  ██████╔╝██║███████╗█████╔╝    ███████║██╔██╗ ██║███████║██║   ╚████╔╝ ███████╗ ║
║  ██╔══██╗██║╚════██║██╔═██╗    ██╔══██║██║╚██╗██║██╔══██║██║    ╚██╔╝  ╚════██║ ║
║  ██║  ██║██║███████║██║  ██╗   ██║  ██║██║ ╚████║██║  ██║███████╗██║   ███████║ ║
║  ╚═╝  ╚═╝╚═╝╚══════╝╚═╝  ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚══════╝╚═╝   ╚══════╝║
╚══════════════════════════════════════════════════════════════════════════════════╝
```

<div align="center">

### `[ TERMINAL ACTIVE ]` &nbsp;•&nbsp; `[ MARKET: LIVE ]` &nbsp;•&nbsp; `[ RISK ENGINE: ONLINE ]`

[![Python](https://img.shields.io/badge/PYTHON-3.10+-00ff41?style=for-the-badge&logo=python&logoColor=black)](https://python.org)
[![Jupyter](https://img.shields.io/badge/JUPYTER-NOTEBOOK-00ff41?style=for-the-badge&logo=jupyter&logoColor=black)](https://jupyter.org)
[![Plotly](https://img.shields.io/badge/PLOTLY-INTERACTIVE-00ff41?style=for-the-badge&logo=plotly&logoColor=black)](https://plotly.com)
[![ML](https://img.shields.io/badge/ML-SKLEARN-00ff41?style=for-the-badge&logo=scikit-learn&logoColor=black)](https://scikit-learn.org)
[![Status](https://img.shields.io/badge/STATUS-PRODUCTION_READY-00ff41?style=for-the-badge)](.)

</div>

---

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  PORTFOLIO TERMINAL v1.0          DATE: 2020-2026      USER: ANALYST        │
│─────────────────────────────────────────────────────────────────────────────│
│  AAPL  ████████████████████░░░░  +127.4%   MSFT  ███████████████░░░░░  +98.2%│
│  GOOGL ████████████░░░░░░░░░░░░   +74.1%   AMZN  ██████████░░░░░░░░░░  +61.7%│
│  TSLA  ████████████████████████  +189.3%   NVDA  ████████████████████  +312% │
│  JPM   ████████░░░░░░░░░░░░░░░░   +45.2%   GS    ███████░░░░░░░░░░░░░  +38.9%│
│─────────────────────────────────────────────────────────────────────────────│
│  PORTFOLIO ▲ +28.4%     BENCHMARK SPY ▲ +19.1%     ALPHA ▲ +9.3%           │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## `> SYSTEM OVERVIEW`

> A **production-grade quantitative finance engine** built entirely in Python.
> This project replicates the core workflow of a Wall Street risk analyst desk —
> from raw market data ingestion to ML-powered alpha generation.

```
MODULES LOADED:
  [✓] 01 — Data Acquisition Engine      (yfinance API • 8 assets • live feed)
  [✓] 02 — Portfolio Return Analyser    (cumulative • annual • alpha vs SPY)
  [✓] 03 — Risk Metrics Engine          (VaR • CVaR • Sharpe • Sortino • Beta • MDD)
  [✓] 04 — Correlation Matrix           (pairwise • rolling 60d • regime detection)
  [✓] 05 — ML Prediction System         (Random Forest • Gradient Boosting • Ensemble)
  [✓] 06 — Monte Carlo Simulator        (10,000 paths • Cholesky decomposition)
  [✓] 07 — Interactive Dashboard        (9-panel Plotly • hover • zoom • filter)
```

---

## `> LIVE DASHBOARD PREVIEW`

### Main Dashboard — 9-Panel Interactive View
![Main Dashboard](assests/newplot.png)

---

### `[PANEL 01]` Value at Risk Analysis
> Return distribution with Normal fit overlay, VaR & CVaR markers, and rolling 30-day VaR time series

![VaR Analysis](assests/newplot%20(9).png)

---

### `[PANEL 02]` Portfolio Drawdown Over Time
> Peak-to-trough decline tracker — Max Drawdown: **-40.7%** during the 2022–2023 bear market

![Drawdown](assests/newplot%20(8).png)

---

### `[PANEL 03]` Pairwise Correlation Matrix
> Daily return correlations across all 8 holdings — JPM & GS show highest co-movement at 0.82

![Correlation Matrix](assests/newplot%20(7).png)

---

### `[PANEL 04]` 60-Day Rolling Correlation vs SPY
> Regime detection — correlations spike sharply during market stress events (2022 crash, 2025 volatility)

![Rolling Correlation](assests/newplot%20(6).png)

---

### `[PANEL 05]` ML Price Prediction — AAPL
> Ensemble model (RF + GB) predicting 5-day forward returns vs actuals, with prediction error distribution

![ML Prediction](assests/newplot%20(5).png)

---

### `[PANEL 06]` Feature Importance Comparison
> `vol_ratio` and `realised_vol_21` dominate both models — volatility regime is the strongest predictive signal

![Feature Importance](assests/newplot%20(4).png)

---

### `[PANEL 07]` Simulated ML Trading Strategy
> Long/short signal strategy vs Buy & Hold SPY — ML strategy outperforms during directional trending regimes

![ML Strategy](assests/newplot%20(3).png)

---

### `[PANEL 08]` Monte Carlo Simulation — 10,000 Paths × 252 Days
> Correlated multi-asset paths via Cholesky decomposition — fan chart with 5th/25th/50th/75th/95th percentile bands

![Monte Carlo](assests/newplot%20(1).png)

---

### `[PANEL 09]` Portfolio Value Distribution After 1 Year
> Final value KDE across all 10,000 simulations — right-skewed with positive expected return

![Distribution](assests/newplot%20(2).png)

---

## `> RISK METRICS DECODED`

```
╔══════════════════════╦═══════════════════════════════════════════════════╗
║  METRIC              ║  WHAT IT TELLS YOU                                ║
╠══════════════════════╬═══════════════════════════════════════════════════╣
║  Historical VaR 95%  ║  Max expected daily loss, 95% of the time         ║
║  Parametric VaR      ║  Same but assumes normal distribution              ║
║  CVaR / Ex.Shortfall ║  Average loss when things go REALLY wrong          ║
║  Sharpe Ratio        ║  Return earned per unit of risk taken              ║
║  Sortino Ratio       ║  Like Sharpe — but only penalises downside risk    ║
║  Beta                ║  How much the portfolio moves with the market      ║
║  Max Drawdown        ║  Worst peak-to-trough loss in history (-40.7%)     ║
║  Calmar Ratio        ║  Annual return divided by Max Drawdown             ║
╚══════════════════════╩═══════════════════════════════════════════════════╝
```

---

## `> ML PREDICTION ENGINE`

```python
FEATURES = {
    "Lag Returns"     : [1d, 2d, 3d, 5d, 10d, 21d],
    "Rolling Stats"   : [mean, std, skew, kurt → 5/10/21/63d windows],
    "Momentum"        : [5d, 21d, 63d, 126d price ratios],
    "Volatility"      : [realised vol, vol regime ratio],
    "Technicals"      : [RSI-14, MACD, MACD Signal, Bollinger Position],
}

MODELS = {
    "Random Forest"     : n_estimators=400, max_depth=8,
    "Gradient Boosting" : n_estimators=300, learning_rate=0.05,
    "Ensemble"          : average(RF, GB),
}

TARGET = "5-day forward log-return"   # no data leakage | TimeSeriesSplit CV
```

```
MODEL PERFORMANCE (hold-out test set)
───────────────────────────────────────────────────────────
  Ensemble Directional Accuracy : ~56-58%
  (> 55% is considered useful alpha in quantitative finance)
───────────────────────────────────────────────────────────
```

---

## `> MONTE CARLO ENGINE`

```
  SIMULATION PARAMETERS
  ┌──────────────────────────────────────┐
  │  Paths          : 10,000             │
  │  Horizon        : 252 trading days   │
  │  Method         : Cholesky decomp.   │
  │  Starting value : $100,000           │
  │  Correlation    : Preserved ✓        │
  └──────────────────────────────────────┘

  OUTPUT DISTRIBUTION
  ──────────────────────────────────────────────────────────
  P5  (worst case)  ████░░░░░░░░░░░░░░░░░░░░░░░░░░  ~$78k
  P25               ████████░░░░░░░░░░░░░░░░░░░░░░  ~$92k
  P50  (median)     ████████████████░░░░░░░░░░░░░░  ~$118k
  P75               ████████████████████████░░░░░░  ~$142k
  P95  (best case)  ██████████████████████████████  ~$187k
  ──────────────────────────────────────────────────────────
```

---

## `> QUICKSTART`

```bash
# Clone
git clone https://github.com/madhura-23/Finance-Risk-Analytics.git
cd Finance-Risk-Analytics

# Install
pip install -r requirements.txt

# Launch
python -m jupyter lab Finance_Risk_Analytics.ipynb

# Inside notebook → Run → Run All Cells
```

---

## `> TECH STACK`

```
DATA             │  yfinance • pandas • numpy
STATISTICS       │  scipy.stats • parametric & empirical distributions
MACHINE LEARNING │  scikit-learn • RandomForest • GradientBoosting • TimeSeriesSplit
VISUALISATION    │  plotly (interactive) • matplotlib • seaborn
SIMULATION       │  numpy (Cholesky Monte Carlo)
ENVIRONMENT      │  JupyterLab
```

---

## `> PROJECT STRUCTURE`

```
Finance-Risk-Analytics/
│
├── Finance_Risk_Analytics.ipynb   ← Main notebook (31 cells, 7 sections)
├── requirements.txt               ← All dependencies
├── assests/                       ← All chart screenshots
│   ├── newplot.png                ← Main 9-panel dashboard
│   ├── newplot (1).png            ← Monte Carlo simulation
│   ├── newplot (2).png            ← Portfolio value distribution
│   ├── newplot (3).png            ← ML trading strategy
│   ├── newplot (4).png            ← Feature importance
│   ├── newplot (5).png            ← ML price prediction
│   ├── newplot (6).png            ← Rolling correlation
│   ├── newplot (7).png            ← Correlation matrix
│   ├── newplot (8).png            ← Portfolio drawdown
│   └── newplot (9).png            ← VaR analysis
└── README.md                      ← You are here
```

---

## `> ROADMAP`

```
NEXT ITERATIONS:
  [ ] Efficient Frontier — mean-variance portfolio optimisation
  [ ] Fama-French Factor Model — 3/5-factor decomposition
  [ ] Black-Scholes Options Pricing — implied volatility surface
  [ ] LSTM Deep Learning — sequence-based prediction
  [ ] Streamlit Deployment — live web dashboard
  [ ] Real-Time Alerts — VaR breach notifications
```

---

## `> AUTHOR`

```
╔═══════════════════════════════════════╗
║  ANALYST    : Madhura                 ║
║  GITHUB     : @madhura-23             ║
║  DOMAIN     : Data Analytics • FinTech║
║  STATUS     : Open to Opportunities   ║
╚═══════════════════════════════════════╝
```

<div align="center">

`[ END OF TRANSMISSION ]`

*If this project helped you, drop a ⭐ — it means a lot!*

</div>
