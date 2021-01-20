# financial-forecasting

<p align="center">
  <img src="https://github.com/byunsy/financial-forecasting/blob/main/images/forecast2.gif" alt="image"/>
</p>

## Description

Financial-forecasting is a jupyter notebook that effectively utilizes both LSTM (Long Short-term Memory) and CNN (Convolutional Neural Network) to accurately predict a stock's closing price based a time-window of 20 business days. Firstly, I have used the FinanceDataReader package to conveniently scrape specific stock market data and constructed a neural network model that combined a mixture of LSTM and CNN models. I then used over 6,000 data points (4,800 for training and 1,200 for testing) to create a financial forecasting model given a specific stock item. To process large sets of data points efficiently, I decided to use Google Colab, which allowed me to utilize its GPUs and memory space.

The general process for the notebook was:

1. Import all necessary packages
2. Attain stock market dataset from FinanceDataReader
3. Data Exploration and Visualizations
4. Data Preprocessing
5. Creating a LSTM/CNN model
6. Compiling the LSTM/CNN model
7. Training the CNN model
8. Model Prediction

## Usage

Every detailed step was recorded in the notebook and can easily be followed there.

## Figures and Charts

Data Visualization
![](images/forecast2_graph2.png)

Model Prediction
![](images/forecast_graph.gif)
