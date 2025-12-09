# Energy Demand Forecasting Models

This repository is dedicated to exploring various techniques and models for forecasting **energy demand** in the **ERCOT (Electric Reliability Council of Texas)** region. The goal is to experiment with data-driven approaches, compare model performance, and provide insights for energy load prediction.

## 📂 Repository Structure

- `data/` – Hourly ERCOT load and weather data.
- `notebooks/` – Jupyter notebooks exploring different forecasting models.
- `scripts/` – Python scripts for data preprocessing, visualization, and model implementation.
- `results/` – Model outputs, metrics, and visualizations.

## 📊 Goals

- Explore time series models.
- Experiment with machine learning models.
- Incorporate weather and environmental data for enhanced forecasting accuracy.
- Compare models using RMSE, MAPE, and other relevant metrics.

## ⚙️ Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/YoItsPeter/Energy-Demand-Forecasting-Models.git
   cd Energy-Demand-Forecasting-Models
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Explore notebooks in the `notebooks/` folder to see different modeling approaches.

## 📈 Data

The main dataset includes the following data (2002-2025):
- #### [ERCOT Load Data](https://www.ercot.com/):
    - Historical hourly load (MW) split by weather zone as well as an aggregate ERCOT load.
- #### [Weather Data](https://open-meteo.com/):
    - Temperature (°F)
    - Dew Point (°F)
    - Relative Humidity (%)
    - Cloud Cover (%)
    - Wind Speed (MPH)
    - Precipitation (Inch)
    - Short Wave Radiation (W/m<sup>2</sup>)
    - Sunshine Duration (Seconds)

> Note: The data set is a csv file compressed using gzip

## 📌 Future Work

- To be determined :)

## 📄 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

<div align="center">
⚡ Created by Peter Barengo
</div>
