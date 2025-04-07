# 📈 AI Stock Bot

An AI-powered financial assistant that blends features of Robinhood, Bloomberg Terminal, and ChatGPT — all in one Streamlit app. Supports multi-country stocks, charting, analytics, LLM summaries, alerts, and exports.

## 🌍 Features

- 🌐 **Multi-country Support**: India 🇮🇳, USA 🇺🇸, Germany 🇩🇪, France 🇫🇷, UK 🇬🇧, Hong Kong 🇭🇰
- 🤖 **AI Q&A & News**: Gemini LLM + SerpAPI for smart insights and news summaries
- 📊 **Charts**: Price history with Matplotlib
- 📈 **Financial Data**: PE ratio, ROE, earnings calendar, and more
- 💾 **Export**: Download CSV or PDF reports
- 🚨 **Price Alerts**: Set real-time price alerts
- 🧠 **Coming Soon**: Portfolio tracking, technical indicators, stock screener, trading bot lab

## 🔧 Tech Stack

- `Streamlit` for the UI
- `yfinance` for stock data
- `matplotlib` for charting
- `LangChain` + `Gemini Pro` for natural language Q&A
- `SerpAPI` for live news
- `fpdf` for PDF exports

## 🛠 Setup

```bash
git clone https://github.com/your-username/ai-stock-bot.git
cd ai-stock-bot
pip install -r requirements.txt
streamlit run app.py
