# Stock Price Prediction App

This is a Stock Prediction App that uses historical stock price data to train a Long Short-Term Memory (LSTM) neural network model and make predictions on future stock prices. The app fetches stock data using the Yahoo Finance API and utilizes the TensorFlow and Keras libraries for building and training the model.

## Prerequisites

To run this application, you need to have the following dependencies installed:

Python 3.6+
numpy
matplotlib
pandas
pandas_datareader
datetime
yfinance
scikit-learn
tensorflow

You can install the dependencies using pip:
```bash
pip install numpy matplotlib pandas pandas_datareader yfinance scikit-learn tensorflow
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/b0shy/Stock_Price_Prediction_App.git
```

2. Change to the project directory:
```bash
cd Stock_Price_Prediction_App
```

3. Change the stock ticker on line 13 to the stock of your choosing:
```python
company = 'META'
```

4. Change the number of prediction days on line 24 to the prediction days of your choosing:
```python
prediction_days = 200
```

5. Run the main.py file:
```bash
python main.py
```

6. The app will fetch the stock data, train the LSTM model, and generate predictions for future stock prices. The predictions will be plotted along with the actual prices in a graph.

7. After the graph is displayed, you can observe the predicted stock prices (green line) and the actual stock prices (black line). The graph will help you visualize the performance of the prediction model.

## Disclaimer

The predictions made by the Stock Prediction App are for informational purposes only and should not be considered financial advice. The accuracy of the predictions depends on various factors and market conditions. Always do your own research and consult with a qualified financial advisor before making any investment decisions based on the predictions.

## MIT License

Copyright (c) [2023] [Bashar Shabani]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
