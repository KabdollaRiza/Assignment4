🔮 AI Crypto Assistant

An AI-powered Streamlit application that provides real-time cryptocurrency market data, news, and AI-driven insights. It fetches data from Binance, CoinMarketCap, and CryptoPanic, then uses a locally running Ollama LLM (like LLaMA2) to generate a short, readable summary.

## 🚀 Features

- ✅ Real-time **price** and **market cap** from Binance and CoinMarketCap  
- ✅ Latest **crypto news** from CryptoPanic  
- ✅ Intelligent **AI-generated summaries** using Ollama + LLaMA2  
- ✅ Fast performance with caching (`@st.cache_data`)  
- ✅ Clean and responsive UI built with Streamlit

## 📦 Requirements

streamlit==1.32.0 
python-dotenv==1.0.0
requests==2.31.0
ollama==0.1.6


## 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-crypto-assistant.git
cd ai-crypto-assistant

# Create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
