# Week 3 Task: Healthcare Trends and Predictive Modeling

Trend identification and forecasting on a **simulated** monthly hospital admissions series (72 months, no real data, no external datasets).

## Files
| File | Purpose |
|---|---|
| `Predictive_Modeling_Report.docx` | Main deliverable: report |
| `generate_data_week3.py` | Creates the synthetic dataset |
| `data/monthly_admissions.csv` | Simulated monthly data (2019-2024) |
| `forecast_analysis.py` | Decomposition, models, evaluation, 2025 forecast, charts |
| `data/forecast_2025.csv` | 2025 forecast with 95% prediction intervals |
| `charts/` | Five PNG charts |
| `results.json` | Metrics and parameters |

## Models compared (train 2019-2023, test 2024)
Seasonal naive, linear trend, trend + seasonal dummies + disruption indicator (regression), Holt-Winters.

## Run
```
pip install pandas numpy matplotlib
python generate_data_week3.py
python forecast_analysis.py
```
