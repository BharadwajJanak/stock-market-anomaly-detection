# Stock Market Anomaly Detection
This project detects unusual price and volume movements in major US stocks using statistical techniques.

## Stocks Analyzed
- AAPL
- MSFT
- GOOG
- TSLA
- NFLX

## Features
- Moving Averages (20, 50)
- RSI Indicator
- Z-score based anomaly detection
- Price & Volume anomaly visualization
- Risk score calculation

## Tech Stack
- Python
- yFinance
- Pandas, NumPy
- SciPy
- Matplotlib, Seaborn

## Output
- Anomaly highlighted price & volume charts
- Risk ranking across stocks

## How to Run
```bash
pip install -r requirements.txt
python anomaly_detection.py
