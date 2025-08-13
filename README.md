# -NIFTY-50-Prediction
Nifty 50 Forecast.This project leverages 20 years of historical Nifty 50 data to forecast market trends using deep learning. Two powerful recurrent neural network architectures — Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) — were implemented to model time-series price behavior.

To enhance signal accuracy and trend detection, we integrated Exponential Moving Averages (EMA-50 and EMA-100) as technical indicators alongside raw price data.

🔍 Highlights:
✅ Dataset: 20 years of Nifty 50 daily data (Open, High, Low, Close, Volume)

🧠 Models: LSTM and GRU for sequential forecasting

📊 Indicators: EMA-50 and EMA-100 for trend smoothing

⚡ Results: GRU achieved faster convergence; LSTM showed better long-term prediction accuracy

This project showcases the potential of deep learning in financial forecasting, combining traditional technical analysis with modern AI techniques.


📈 Exploratory Data Analysis


Close Price with MA50 & MA100
<img width="1385" height="633" alt="Screenshot 2025-08-04 030100" src="https://github.com/user-attachments/assets/2a956773-c67b-4399-b6e2-d14dd39610b8" />

Here, both MA50 (orange) and MA100 (brown) are plotted. Crossovers between these lines can indicate potential bullish or bearish signals.

Average Yearly Close Price
<img width="1084" height="703" alt="Screenshot 2025-08-04 030124" src="https://github.com/user-attachments/assets/fbf279b1-1afb-43c8-a726-2f878c5f01c8" />


A bar chart showing the average annual closing price of Nifty 50 from 2010 to 2023. The steady upward trend reflects long-term market growth.

🧠 Models and Predictions
GRU Model Predictions
<img width="1373" height="623" alt="Screenshot 2025-08-04 030235" src="https://github.com/user-attachments/assets/093ce86c-8ad0-48e8-869a-dcab568e7f7a" />

This chart compares actual closing prices (blue) with GRU-predicted values for training (red) and test (green) datasets. The model closely follows real price movements, showing good predictive accuracy.

LSTM Model Predictions
<img width="1723" height="639" alt="Screenshot 2025-08-13 203414" src="https://github.com/user-attachments/assets/ef04e0a2-824c-4062-bc36-c0dde0524d12" />


The LSTM model’s predictions (orange for forecast, red for training) also align closely with actual prices. It captures long-term dependencies and provides smoother forecasts than GRU.

📉 Training and Validation Loss
<img width="760" height="577" alt="Screenshot 2025-08-13 203436" src="https://github.com/user-attachments/assets/61bfad5c-6f1b-4e96-ba77-d2eee82a8f5c" />

Training and validation loss curves for the deep learning models. The rapid decline and stability indicate fast convergence with minimal overfitting.
