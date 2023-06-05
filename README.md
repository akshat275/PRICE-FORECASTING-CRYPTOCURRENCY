# PRICE-FORECASTING-CRYPTOCURRENCY
The main goal is to forecast cryptocurrency price using AI algorithm like GRU, LSTM and bi-LSTM.

# 1 Introduction
Cryptocurrency research is facilitated by advancements in financial technology. Bitcoin, the most prominent cryptocurrency, relies on Blockchain and presents forecasting challenges due to volatility. This project compares LSTM, BiLSTM, and GRU RNN algorithms for Bitcoin price prediction. RNNs encounter limitations with large datasets, causing vanishing or exploding gradients. Specialized RNN architectures with gate mechanisms address this issue. Results demonstrate that GRU outperforms LSTM and bi-LSTM in predicting various cryptocurrencies. Model performance is evaluated using MSE, RMSE, and MAPE. This research underscores the reliability of AI algorithms for cryptocurrency forecasting, highlighting GRU as the preferred choice over LSTM and bi-LSTM models

# 2 Tools and Technology 
Programming Language: Python 
IDE: Google Colab 
Python libraries: pandas, numpy, matplotlib, tensorflow, keras, and math 
Neural Network: RNN (Recurrent Neural Network) Neural Network Models: Long Short-Term Memory (LSTM), Bidirectional Long Short Term Memory (BiLSTM), and Gated Recurrent Unit (GRU) 
Performance Metrics: Mean Square Error (MSE), Root Mean Square Error (RMSE), and Mean Absolute Percentage Error (MAPE)

# 3 RNN Models Used.
1.	Long Short-Term Memory (LSTM)
2.	Bi-directional Long Short-Term Memory (Bi-LSTM)
3.	Gated Recurrent Unit (GRU)

# 4 Activation function Used.
1.	Sigmoid activation function
2.	Tanh activation function
3.	ReLU activation function

# 5 Results
1.	This shows the comparison between Combined Prediction and Actual Price Chart
2.	This also shows the Mean Square error(MSE), Root Mean Square error(RMSE), and Mean absolute percentage error(MAPE)

For Sigmoid activation function:
![image](https://github.com/akshat275/PRICE-FORECASTING-CRYPTOCURRENCY/assets/37811907/265bce84-a5f8-45f5-a1fa-63439b5f632a)
![image](https://github.com/akshat275/PRICE-FORECASTING-CRYPTOCURRENCY/assets/37811907/3df90ff0-8deb-4d8e-99c0-dd432246ad38)

For tanh activation function:
![image](https://github.com/akshat275/PRICE-FORECASTING-CRYPTOCURRENCY/assets/37811907/43a5c05e-0377-407f-be68-af1b2496c491)
![image](https://github.com/akshat275/PRICE-FORECASTING-CRYPTOCURRENCY/assets/37811907/c37f490c-2bd3-460b-bd77-698e74b57970)

For ReLU activation function:
![image](https://github.com/akshat275/PRICE-FORECASTING-CRYPTOCURRENCY/assets/37811907/07d97d74-1c90-49fc-b82c-8c04bf1c8888)
![image](https://github.com/akshat275/PRICE-FORECASTING-CRYPTOCURRENCY/assets/37811907/9999327d-3dc2-4089-aa97-799629001459)

# Conclusion
Different models (LSTM, BiLSTM, GRU) were tested for predicting Bitcoin prices. Performance measures showed overall good accuracy. BiLSTM was a better indicator of trends, important for trading. It performed well in forecasting, capturing the trend accurately. However, for overall prediction, GRU performed the best according to the dataset, with the closest match to actual Bitcoin values


 


