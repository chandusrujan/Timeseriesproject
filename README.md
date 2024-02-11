
## README - Solar Radiation Prediction Project

### Project Overview
This project focuses on forecasting solar radiation using historical data, which is crucial for optimizing the use of solar energy. By accurately predicting solar radiation, we aim to enhance solar panel efficiency and facilitate better energy management strategies.

### Objectives
- To analyze historical solar radiation data along with related environmental conditions.
- To apply time series forecasting models to predict future solar radiation levels.
- To contribute towards the efficient use of solar energy by providing accurate forecasts.

### Datasets
The project utilizes the "SolarPrediction.csv" dataset, containing 32,686 entries with the following parameters: UNIXTime, Data, Time, Radiation, Temperature, Pressure, Humidity, WindDirection(Degrees), Speed, TimeSunRise, and TimeSunSet. This dataset records solar radiation and various weather conditions, serving as the basis for our predictive analysis.

### Methodology
- **Literature Survey**: Reviewed existing methods and models for solar radiation prediction, including ARIMA, SARIMA, and Holt-Winters.
- **Data Preprocessing**: Cleaned and prepared the dataset for analysis, including handling missing values and normalizing data.
- **Model Development**: Developed and tested time series forecasting models using the Python libraries Pandas, NumPy, Matplotlib, and PyTZ.
- **Analysis**: Analyzed the models' performance and compared their accuracy in predicting solar radiation.

### Software and Libraries
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, PyTZ
- ARIMA, SARIMA, Holt-Winters (for time series forecasting)

### How to Run the Analysis
1. **Setup Environment**: Ensure you have Python 3.x installed along with the necessary libraries mentioned above.
2. **Load Notebook**: Open the "radiation-time-serie-predictions.ipynb" Jupyter notebook.
3. **Run Cells**: Execute the cells sequentially to load the dataset, preprocess the data, develop the forecasting models, and analyze the results.

### Files Description
- `TIMESERIES FINAL.pdf`: Comprehensive report detailing the project's background, methodology, and findings.
- `Time series.pdf`: Additional documentation on time series analysis concepts and definitions.
- `radiation-time-serie-predictions.ipynb`: Jupyter notebook containing the code for data analysis and model development.
- `SolarPrediction.csv`: Dataset used for model training and prediction.

### Conclusion
This project demonstrates the potential of time series analysis in predicting solar radiation levels, which is vital for optimizing solar energy use. Through rigorous analysis and model development, we can provide accurate forecasts that support sustainable energy solutions.
