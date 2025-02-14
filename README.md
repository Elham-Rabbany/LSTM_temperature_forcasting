# Temperature Forecasting Using LSTM

## Project Overview

This project focuses on forecasting monthly temperatures for Germany using LSTM-based models. The dataset is sourced from the **Copernicus Climate Data Store (CDS)** and includes historical temperature records from **1940 to 2023**. The study initially analyzes a specific region and then extends to the **entire country** to observe broader trends. Future temperature projections are generated using deep learning models.

## Key Features

- **Data Source:** ERA5 Climate Indicators (Copernicus CDS)
- **Prediction Models:** LSTM
- **Temporal coverage​:** 1940-2023 / Monthly​
- **Variables:** Mean temperature ​
- **Tools Used:** Python, TensorFlow, Keras, Matplotlib, Geopandas

## Project Structure

```
📂 data/                    # Add files via upload
📜 LSTM_temp_forcast.ipynb  # Update LSTM_temp_forcast.ipynb
📜 Presentation01.pptx       # Add files via upload
📜 README.md                # Update README.md
```

## How It Works

1. **Data Preparation:**

   - Historical temperature data from ERA5 is loaded and preprocessed.
   - Data is split into training and testing sets.

2. **Model Architecture:**

   - LSTM layers are used to learn temperature trends.
   - First LSTM layer: 256 units, second LSTM layer: 128 units.
   - A Dense layer outputs a single predicted value.

3. **Training & Evaluation:**

   - Model is trained on historical data.
   - Evaluated using R² score (0.93) for accuracy.

4. **Prediction & Visualization:**

   - Model forecasts temperature for 2026.
   - Results are visualized using Matplotlib & Geopandas.

## Results

✅ **Initial analysis conducted on a specific region before extending to the entire country**
✅ **Gradual temperature increase over time**
✅ **Regional warming differences show that the model has learned local temperature variations**
✅ **Seasonal Temperature Fluctuations Captured Well**
✅ **LSTM Model Effectively Learns Patterns**

## Future Work

- **Improve long-term trend forecasts** by incorporating additional features.
- **Experiment with hybrid models (e.g., CNN-LSTM, Transformer models).**
- **Explore advanced forecasting techniques to enhance accuracy.**

## Data Source

**Source:** [Copernicus Climate Data Store](https://cds.climate.copernicus.eu/datasets/sis-ecde-climate-indicators?tab=overview)

