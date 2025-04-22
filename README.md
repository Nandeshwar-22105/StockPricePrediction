🚗 Tesla Stock Price Prediction Using LSTM
This project uses historical stock price data of Tesla (TSLA) to predict future prices using a deep learning model based on LSTM (Long Short-Term Memory) networks. The predictions are visualized using interactive Plotly charts.

📊 Overview
✅ Scrapes S&P 500 companies from Wikipedia.

✅ Fetches Tesla stock data using yfinance.

✅ Preprocesses data using MinMaxScaler.

✅ Builds and trains an LSTM model on the last 60-day window to predict the next day's price.

✅ Evaluates model performance using RMSE and visualizes actual vs predicted prices.

🧰 Tech Stack
Python

TensorFlow/Keras

yfinance

Plotly

Pandas, NumPy, Scikit-learn

📂 Project Structure
bash
Copy
Edit
📁 Tesla_Stock_Price_Prediction/
├── Untitled1.ipynb        # Main notebook with all the code
├── README.md              # Project overview and instructions
⚙️ How It Works
Data Collection

Fetches TSLA data from Oct 2016 to Oct 2024.

Data Preprocessing

Normalizes data using MinMaxScaler.

Creates sequential data for LSTM input.

Model Architecture

Two stacked LSTM layers with dropout.

Output layer for regression.

Training

Trained with MSE loss and Adam optimizer.

Evaluation & Visualization

Inverse transforms predictions.

Plots predicted vs actual prices using Plotly.

Computes MSE and RMSE.

📈 Results
Model performance is evaluated using Root Mean Squared Error (RMSE).

Interactive Plotly graphs show how close predictions are to real stock prices.

🧪 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/Tesla_Stock_Price_Prediction.git
cd Tesla_Stock_Price_Prediction
Install required libraries:

bash
Copy
Edit
pip install plotly numpy scipy scikit-learn tensorflow yfinance
Open Untitled1.ipynb in Jupyter Notebook or any IDE.

Run all cells step-by-step to see the prediction pipeline.

