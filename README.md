# Bike Sharing Data Analysis

An exploratory analysis of bike rental demand using a Jupyter Notebook and the Kaggle Bike Sharing Demand dataset.

## Project Overview

This project studies how time, weather, and calendar conditions relate to bike rental volume. It focuses on reproducible data inspection, cleaning, visualization, and interpretation rather than machine-learning model training.

## Dataset

The included CSV contains 10,886 hourly records with fields such as `datetime`, `season`, `holiday`, `workingday`, `weather`, `temp`, `atemp`, `humidity`, `windspeed`, `casual`, `registered`, and `count`. The notebook identifies the source as the Kaggle Bike Sharing Demand dataset.

## Analysis Questions

- How does rental demand vary by hour, weekday, month, and season?
- How do working days and holidays affect demand?
- How are temperature, humidity, wind speed, and weather conditions associated with rentals?
- How do registered and casual users differ over time?

## Methods and Outputs

The notebook uses Pandas and NumPy for data loading and preparation, and Matplotlib for exploratory charts. The PDF is an exported analysis report containing the executed results and visualizations.

## Project Structure

```text
.
├── bike_analysis.ipynb       # Executable analysis notebook
├── share bike.csv            # Input dataset
├── bike_analysis.pdf         # Exported report
└── 运行代码说明.txt          # Local execution notes
```

## Quick Start

```powershell
python -m pip install pandas numpy matplotlib jupyter
jupyter notebook bike_analysis.ipynb
```

Keep `bike_analysis.ipynb` and `share bike.csv` in the same directory because the notebook reads the CSV with a relative path.

## Limitations

This is exploratory analysis of a historical public dataset. The project does not train a predictive model, establish causal relationships, or represent a production demand-forecasting system.

## Data and Privacy

The project uses public/synthetic course-analysis data and contains no private credentials or customer data.
