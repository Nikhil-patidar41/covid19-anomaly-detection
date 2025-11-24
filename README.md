# COVID-19 Anomaly Detection & Analysis

COVID-19 time series anomaly detection &amp; analysis — google colab with exploration, preprocessing, modeling and visualization

---

## Files in this repository
- `covid19_anomaly_detection.ipynb` — Main Jupyter Notebook (exploration, preprocessing, modeling, visualization).  
  *(Upload your local file from `/mnt/data/COVID_19_AN_p.ipynb` and rename it to this filename.)*
- `requirements.txt` — Python dependencies for reproducing the notebook.
- `data/` — (optional) folder for raw and processed datasets (not included).
- `README.md` — This file.
- `LICENSE` — (optional) license file (MIT recommended for code/examples).

---

## Quick start

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/covid19-anomaly-detection.git
cd covid19-anomaly-detection
Data loading — instructions to load COVID-19 time-series (cases, deaths, etc.).

Exploratory Data Analysis (EDA) — visualizations and summary statistics to understand trends.

Preprocessing — cleaning, resampling, handling missing values, feature engineering (lags, rolling stats).

Modeling — anomaly detection / forecasting approaches (e.g., ARIMA, isolation forest, simple ML models, or baseline heuristics).

Evaluation — metrics and visual checks to verify anomalies and model performance.

Results & visualization — plots highlighting detected anomalies and key observations.

See requirements.txt for full list. Core libraries used:

Python 3.8+

pandas, numpy

matplotlib, seaborn, plotly (optional)

scikit-learn

statsmodels (optional for ARIMA)

google colab
