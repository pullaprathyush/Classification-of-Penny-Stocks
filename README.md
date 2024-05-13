## Predicting Penny Stocks
Project Overview :
 This project involves the analysis and modeling of stock data using
 machine learning. The project is divided into two main files: one for data
 collection and the other for building and evaluating machine learning
 models.
 
 1. Data Collection (Yfinance Data Retrieval)
 The data collection process involves obtaining stock data for 495 stocks
 using the Yfinance library. To reduce the hassle of running the data
 retrieval code each time, the data has been pre-downloaded and saved
 as a CSV file. Additionally, a detailed PDF document is provided,
 containing the code and outputs of each cell in the data collection file.

  Data Retrieval Code File: data_collection.ipynb
  
  Data CSV File: stock_data.csv

 2. Machine Learning Models (LR- Linear Regression)
 The machine learning part focuses on building and evaluating models
 using the stock data obtained. The code is organized in a Colab
 notebook named LR.ipynb. To run this notebook successfully, follow the
 instructions below:

 Download the Dataset CSV File:
 Use the provided stock_data.csv file obtained from the data collection
 process.
 
 Upload Dataset to Google Drive:
 Upload the stock_data.csv file to your Google Drive.
 
 Mount the LR Colab File to Google Drive:
 Open the LR.ipynb file using Google Colab and mount it to your Google
 Drive to access the dataset.
 
Update Dataset Path in LR Code:
 In the Colab notebook, locate the line where the dataset is loaded
 (pd.read_csv('path_to_dataset.csv')) and update it with the correct path
 to the stock_data.csv file in your Google Drive.
 
 Run Each Cell:
 Execute each cell in the notebook to perform the necessary data
 preprocessing, model training, and evaluation.
 
 Additional Notes:
 Make sure to have the required libraries and dependencies installed
 before running the code.
 
