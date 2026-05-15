# Air Quality Forecasting

This project explores air quality prediction using deep learning and time series data from monitoring stations across India.

I used historical pollution data from 2010–2023 along with live air-quality data from the Open-Meteo API to build a forecasting model that predicts pollutant trends.

## What this project does

- Loads and cleans historical air quality data
- Processes time-series pollution measurements
- Fetches live air quality data
- Trains a deep learning model for forecasting
- Visualizes trends and predictions

## Dataset

Dataset used:

Time Series Air Quality Data of India (2010–2023) from :contentReference[oaicite:1]{index=1}

Dataset is not included in this repository.

Kaggle dataset path:

```python
/kaggle/input/datasets/abhisheksjha/time-series-air-quality-data-of-india-2010-2023
```

## Tools used

- :contentReference[oaicite:2]{index=2}
- :contentReference[oaicite:3]{index=3}
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Requests

## Files

```text
dl.ipynb   -> main notebook
```

## Running the project

1. Open the notebook in :contentReference[oaicite:4]{index=4} or locally in Jupyter
2. Add the dataset
3. Enable internet if using live API calls
4. Run all cells

## Future improvements

- Train on multiple cities
- Improve prediction accuracy
- Build a dashboard for live predictions
