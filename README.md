# Stock-Trading-Project
Abstract : 
Predicting stock market prices has been an area of interest ever since mathematical models started rolling out with each and every improvements getting us closer to an accuracy that very much allows us to perform high latency trading with minimal human intervention. Our work uses LSTM based prediction model which gives us the future stock prices and a MPC based model that gives the decisions that need to performed with the help of the predicted values. Recurrent neural networks (RNNs) are a powerful model for processing sequential data. Long Short-Term Memory (LSTM) is one of the most successful RNNs architectures.They are able to grasp data dynamically over time with high prediction accuracy. The MPC model then uses this predicted stock price and decides on the best decisions that will lead to maximum profit.

Introduction :
Stock market price prediction has been a topic of interest for many years among the academia and the financial industry. The main motive behind this is to be able to make the most profitable trades while minimizing losses on a long term basis. The prices themselves fluctuate due to external factors that are difficult to model using machine learning techniques alone. Instead of treating it as a prediction task, it can be treated as a model predictive control (MPC) system where the plant model is a trained neural network that predicts the next value given the previous values and the system generates a buy/sell/hold signal based on the predicted value. This signal is sent back into the system.

Bibliography :
Shirzad Malekpour, James A. Primbs and B. Ross Barmish, On Stock Trading Using a PI Controller in an Idealized Market: The Robust Positive Expectation Property, 52nd IEEE Conference on Decision and Control December 10-13, 2013. Florence, Italy, pp. 1210-1216.

R. C. Merton, Continuous-Time Finance, Macroeconomics and Finance Series, John Wiley and S ons, 1992.

R. C. Merton, "Optimum Consumption and Portfolio Rules in a Continuous-Time Model," Joural of Economic Theor, vol. 3,pp. 373-413,1971.

Omer Berat Sezer, A. Murat Ozbayoglu, Erdogan Dogdu, "An Artificial Neural Network-based Stock Trading System Using Technical Analysis and Big Data Framework", ACM SE '17 Proceedings of the SouthEast Conference, pp. 223-226, 2017. 
