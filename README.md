# Comparative-and-Hybrid-Analysis-of-Statistical-Machine-Learning-and-Deep-Learning-Models
Research-Paper
Financial Time-Series Forecasting using ML & DL 📌 Overview This project presents a comparative analysis of statistical, machine learning, and deep learning models for stock price forecasting. It evaluates multiple models on real-world stock data and proposes a hybrid approach to improve prediction performance.

🚀 Models Implemented

Statistical Model

ARIMA

Machine Learning Models

Random Forest

Support Vector Regression (SVR)

Gradient Boosting

XGBoost

Deep Learning Models

LSTM (Long Short-Term Memory)

GRU (Gated Recurrent Unit)

Hybrid Model (Proposed)

ARIMA + LSTM + XGBoost

📊 Dataset

Source: Yahoo Finance

Duration: 2019 – 2024

Stocks Used:

Reliance Industries

Tata Consultancy Services (TCS)

HDFC Bank

Features:

Open, High, Low, Close

Target: Closing Price

⚙️ Methodology

Data preprocessing with forward fill

Normalization using Min-Max Scaling

Feature engineering using Sliding Window (size = 10)

Train-test split: 80% training / 20% testing

Evaluation metric: RMSE

📈 Results Summary ModelPerformanceXGBoost⭐ BestRandom ForestVery GoodGRUGoodLSTMModerateARIMALimited (linear only)SVRWeak 👉 XGBoost consistently achieved the lowest RMSE across all datasets.

🧠 Key Insights

Ensemble methods outperform traditional and deep learning models

GRU performs better than LSTM on moderate datasets

ARIMA struggles with nonlinear financial data

Hybrid models have strong potential for improvement

🔮 Future Work

Implement full hybrid model experimentally

Add external features (news, sentiment, macroeconomic data)

Explore Transformer-based models

Use additional metrics (MAE, MAPE, R²)

🛠️ Tech Stack

Python

NumPy, Pandas

Scikit-learn

TensorFlow / Keras

XGBoost

Statsmodels

📄 Research Paper Title: Comparative and Hybrid Analysis of Statistical, Machine Learning, and Deep Learning Models for Financial Time-Series Forecasting

👨‍💻 Authors

Devashish Singh Thapa

Aditya Singh

⭐ Contribute Feel free to fork this repo, raise issues, or submit pull requests!

📬 Contact

📧 sdeva9881@gmail.com
📧 singhaditya.in26@gmail.com
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


▶️ How to Run the Project
🔧 Prerequisites

Make sure you have:

Python 3.8+ pip installed Git installed 
📥 Step 1: Clone the Repository git clone https://github.com/your-username/your-repo-name.git cd your-repo-name 📦 Step 2: Install Dependencies pip install -r requirements.txt

If requirements.txt is not available, install manually:

pip install numpy pandas matplotlib scikit-learn tensorflow xgboost statsmodels yfinance

📊 Step 3: Run the Project

▶️ Option 1: Run Main Script python main.py 
▶️ Option 2: Run Jupyter Notebook jupyter notebook

Then open the .ipynb file and run all cells.

⚙️ What the Code Does Fetches stock data using Yahoo Finance Preprocesses data (normalization + sliding window) Trains multiple models (ARIMA, ML, DL) Evaluates performance using RMSE Outputs predictions and comparison results
📁 Project Structure ├── data/ # Dataset (optional or generated) ├── models/ # Model implementations ├── notebooks/ # Jupyter notebooks ├── main.py # Main execution file ├── requirements.txt # Dependencies └── README.md
⚠️ Common Issues TensorFlow not installing → use Python 3.8–3.10 ARIMA errors → ensure statsmodels is installed No data fetched → check internet connection ✅ Expected Output RMSE scores for each model Model comparison table Predicted vs actual stock price plots

