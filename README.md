# Time Series Forecasting with LSTM

This project is about forecasting prices using a neural network model called LSTM (Long Short-Term Memory). The dataset includes monthly price data from 1950 to 2020.

## What is LSTM?

LSTM stands for Long Short-Term Memory. It is a type of Recurrent Neural Network (RNN) that is well-suited for sequence prediction problems. Unlike standard RNNs, LSTMs are capable of learning long-term dependencies and avoiding the vanishing gradient problem. That makes them especially useful for time series forecasting.

## What I did

- Loaded and visualized the historical price data.
- Normalized the values using MinMaxScaler for better training performance.
- Created input-output sequences suitable for LSTM.
- Built an LSTM model using Keras (with Sequential API).
- Trained the model to predict future prices based on past data.
- Evaluated the model using Mean Squared Error (MSE).
- Plotted actual vs. predicted values to visualize performance.

## Tools and Libraries

- Python
- Pandas and NumPy for data handling
- Matplotlib for visualization
- Scikit-learn for preprocessing
- TensorFlow/Keras for building the neural network

## Notes

This is a basic LSTM model for educational and exploratory purposes. It can be improved by using more features, tuning the hyperparameters, or testing with other architectures like GRU or bidirectional LSTMs.
