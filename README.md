Stock Price Prediction 

A secure and interactive web application built with Streamlit, PyTorch, and LSTM networks to predict stock prices using historical data. Includes a user login system with password encryption and aesthetic custom styling.

🚀 Features:

📊 Stock Price Prediction using LSTM (Long Short-Term Memory)

🔐 Secure Login System with bcrypt password hashing

📁 Dynamic CSV loading from /stocks folder

🎨 Stylish, animated UI with custom CSS

📈 Evaluation metrics: MAE, RMSE, R²

🧠 PyTorch-based LSTM Model

📦 Built with Python, Streamlit, PyTorch, Pandas, NumPy, and Matplotlib

__________________________________________________________________________________________________________________________________________________________________________________________________________________________________

The Folder Structure:

project/
│
├── project.py                    ( Main Streamlit application)
├── stocks/                   # Folder with CSV files (one per company)
│   └── example.csv          (Format: ['Date', 'Open', 'High', 'Low', 'Close', ...])
├── README.md             


________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


How It Works :

1 User logs in using a secure sidebar login form.

2 The app lists available company CSVs in the stocks/ directory.

3 On selecting a company, the app:

4 Loads historical closing prices.

5 Scales the data using MinMaxScaler.

6 Prepares sequences for LSTM training.

7 A PyTorch-based LSTM model is trained and evaluated.

8 Predictions and metrics are visualized on-screen.

__________________________________________________________________________________________________________________________________________________________________________________________________________________________________


Dependencies
Install required Python libraries with:

pip install :
streamlit 
torch 
pandas 
numpy 
matplotlib 
scikit-learn 
bcrypt





