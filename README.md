# Google Stock Price Prediction using LSTM

This project predicts Google stock prices using a Recurrent Neural Network (RNN) with a Long Short-Term Memory (LSTM) model. The model is trained on historical stock data and then used to predict future stock prices.

## 🚀 Features
- Uses LSTM for time-series forecasting
- Predicts Google's stock price based on past trends
- Visualizes actual vs. predicted stock prices
- Scales data for better model accuracy

## 📂 Project Structure
```
├── google_stock_price_model.h5  # Trained LSTM model
├── Google_Stock_Price_Train.csv  # Training data
├── Google_Stock_Price_Test.csv   # Test data
├── predict_google_stock.py       # Prediction script
├── Predicted_Google_Stock_Price.csv # Output predictions
├── README.md                     # Project documentation
```

## 📌 Requirements
Install the required dependencies using:
```sh
pip install numpy pandas matplotlib scikit-learn tensorflow
```

## 🔧 Usage
1. Clone the repository:
```sh
git clone https://github.com/vaibhav208/google-stock-prediction.git
cd google-stock-prediction
```
2. Run the prediction script:
```sh
python predict_google_stock.py
```
3. View the predictions in `Predicted_Google_Stock_Price.csv` and the visualization plot.

## 📊 Results
The script will generate a plot comparing actual and predicted stock prices.

## 🤖 Model Details
- Uses 60 previous stock prices as input to predict the next stock price.
- Trained on Google stock data.
- Utilizes MinMaxScaler for feature scaling.
