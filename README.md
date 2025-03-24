# 🚀 Futuristic Dogecoin Price Predictor 💰

A professional-level ML model with a sleek chatbot interface that predicts Dogecoin closing prices using XGBoost, seamlessly integrated into an interactive Gradio UI.

## 🔥 Project Features

- ✅ **XGBoost ML model:** 99.4% accuracy (R²)
- ✅ **Interactive visualizations:** Dynamic price charts, correlation heatmaps, and feature importance
- ✅ **Real-time prediction UI:** Instant price forecasting through an intuitive Gradio interface

## 📊 Visualizations

![Price Prediction Visualization](https://github.com/user-attachments/assets/880850f0-9f34-4589-9cb4-e270ec092080)
![Feature Correlation Heatmap](https://github.com/user-attachments/assets/a78e18ac-36b8-4a6b-8c76-f9fd1c720e8e)
![Price Trend Analysis](https://github.com/user-attachments/assets/4a52321c-b793-410f-b1e9-c05a808759d0)

## 🛠️ Tech Stack

| Component | Technologies |
|-----------|-------------|
| Data Processing | Pandas, NumPy |
| ML Models | XGBoost, scikit-learn |
| Visualization | Matplotlib, Seaborn, Plotly |
| Interface | Gradio |
| Environment | Google Colab |

## 📈 Model Performance

The XGBoost model achieves impressive metrics:
- **R² Score:** 0.994
- **Mean Absolute Error:** 0.0021
- **Root Mean Squared Error:** 0.0032

## 🤖 Chatbot Interface

The intuitive Gradio interface allows users to:
- Input market indicators and technical parameters
- Receive instant price predictions with confidence intervals
- Visualize prediction results in real-time charts
- Compare predictions against historical performance

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/mayankshekhar/futuristic-dogecoin-predictor.git
cd futuristic-dogecoin-predictor
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebook:
```bash
jupyter notebook notebook/Dogecoin_Price_Prediction.ipynb
```

4. Launch the prediction interface:
```bash
python app.py
```

## 📂 Repository Structure

```
dogecoin-predictor/
├── 📁 data/
│   └── DOGE-USD.csv
├── 📁 model/
│   └── dogecoin_xgb_model.joblib
├── 📁 notebook/
│   └── Dogecoin_Price_Prediction.ipynb
├── app.py
├── README.md
└── requirements.txt
```

## 📌 Future Roadmap

- Implement LSTM and Transformer models for sequence modeling
- Add real-time API integration with CoinGecko and Binance
- Develop a comprehensive web application with additional features
- Incorporate sentiment analysis from social media feeds
- Provide automated trading signals based on prediction thresholds

## 🌟 Acknowledgements

- Historical data provided by Yahoo Finance
- Technical indicators derived from TA-Lib
- Market sentiment analysis powered by VADER

---

Developed with ❤️ by **Mayank Shekhar**

*Disclaimer: This project is for educational purposes only. Cryptocurrency investments carry high risk. Always conduct your own research before making investment decisions.*
