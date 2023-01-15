# Stock-Price-Prediction using LSTM

The project is made on Jupyter Notebook and VS Code. 

The prediction is done on closing prices from the data acquired through the python's yfinance module that allows the user to collect stock information of companies without any cost. 

The data is from 01/2010 to 12/2022. It is divided into 70% training and 30% testing data set. 

The model is trained on 100 steps to predict the value of 101st day. 

Feature scaling is done using MinMaxScaler from sklearn.preprocessing with feature range of ( 0 , 1 )

The model type is Sequential. The layer type is LSTM.

The model is compiled with Adam optimizer with loss set to Mean Squared Error (MSE). 
The model is fit with 50 epochs.

After model completion, test data is prepared and predictions are made. After scaling up the result, Original Vs Predicted Price graph is plotted using Matplotlib.pyplot. 

For showing our project to the others, we decide to use Streamlit that is a Python's open source framework and made a Web App from it. 

<h2> How to run the Web App </h2>

The code for the streamlit web app is stored in 
