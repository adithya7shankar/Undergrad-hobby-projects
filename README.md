# Undergrad-hobby-projects

## ARIMA Model for Stock Price Forecasting
### Overview
This project demonstrates the use of the ARIMA (AutoRegressive Integrated Moving Average) model to forecast stock prices. The notebook walks through the entire process, from data loading and preprocessing to model training and evaluation.

###Requirements
To run this notebook, you will need the following Python packages:

- pandas
- numpy
- matplotlib
- statsmodels
- pmdarima
- scikit-learn
You can install the required packages using the following command:

```bash
pip install pandas numpy matplotlib statsmodels pmdarima scikit-learn
```
### Files
ARIMA_model.ipynb: The main Jupyter notebook containing the code for the project.
### Data
The dataset used in this project is a CSV file containing historical stock prices for ICICI Bank (ICICIBANK.NS). The data includes columns such as 'Date', 'Open', 'High', 'Low', 'Close', 'Adj Close', and 'Volume'.

### Project Steps
1. Data Loading: The dataset is loaded using pandas and any missing values are dropped.

2. Exploratory Data Analysis (EDA): The 'Adj Close' prices are plotted to visualize the time series.

3. Stationarity Test: The Augmented Dickey-Fuller (ADF) test is performed to check the stationarity of the time series.

4. Model Selection: The auto_arima function from the pmdarima package is used to automatically select the best ARIMA model parameters.

5. Model Training: The ARIMA model is trained on the training data.

6. Prediction: The model is used to predict stock prices, and the predictions are plotted alongside the actual values.

7.Evaluation: The model's performance is evaluated using Root Mean Squared Error (RMSE).

### Results
The ARIMA model is able to generate forecasts that are reasonably close to the actual stock prices. The RMSE metric provides a quantitative measure of the model's accuracy.

### How to Run
- Clone or download this repository.
- Open the ARIMA_model.ipynb notebook in Jupyter or Google Colab.
- Run the cells in order to execute the entire workflow.

### Conclusion
This project serves as a basic introduction to time series forecasting using the ARIMA model. It can be further extended by experimenting with different ARIMA parameters, incorporating other time series models, or applying the model to different datasets.
