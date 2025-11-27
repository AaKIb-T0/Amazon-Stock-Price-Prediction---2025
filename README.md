# Amazon-Stock-Price-Prediction---2025



# Amazon (AMZN) Stock Price Predictor  
**Live Demo →** [![Hugging Face Spaces](https://img.shields.io/badge/🤗%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/YOUR_USERNAME/amzn-stock-predictor)  
[![Python](https://img.shields.io/badge/Python-3.10-blue)](https://www.python.org) [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange)](https://www.tensorflow.org) [![Streamlit](https://img.shields.io/badge/Streamlit-1.30-red)](https://streamlit.io)

An interactive **LSTM-based stock price forecasting app** that predicts Amazon (AMZN) closing price for the next 1–30 days using 5+ years of historical data.

Perfect portfolio project for **Data Science / Machine Learning Engineer** roles in 2025.

![demo](https://raw.githubusercontent.com/YOUR_USERNAME/amzn-stock-predictor/main/demo.gif)  
*(Replace the link above with your own screenshot/GIF after deploying!)*

## Features
- Real-time AMZN data from Yahoo Finance (always up-to-date)
- Trained **LSTM neural network** (60-day lookback)
- Predict next 1–30 days with one click
- Beautiful interactive charts + forecast table
- Deployed live on Hugging Face Spaces (free & public)

## Live App
Try it now: https://huggingface.co/spaces/YOUR_USERNAME/amzn-stock-predictor  
(Just replace `YOUR_USERNAME` with your actual HF username after deploying)

## Tech Stack
- **Python**  
- **TensorFlow / Keras** → LSTM model  
- **yfinance** → Live stock data  
- **Streamlit** → Interactive web app  
- **Pandas, NumPy, Matplotlib, Scikit-learn**  
- Deployed on **Hugging Face Spaces**

## How to Run Locally
```bash
# 1. Clone repo
git clone https://github.com/YOUR_USERNAME/amzn-stock-predictor.git
cd amzn-stock-predictor

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
streamlit run app.py
