

# AchillesV1: AI-Driven Gold Trading with Sentiment & Time-Series Forecasting

🚀 Ready to Predict the Future?

AchillesV1 is an AI-powered trading bot designed to **automate stock market investments**. 
In a **demo account**, this system achieved an **182% return on investment** by leveraging 
**deep learning market predictions** and **sentiment analysis from real-time news**.

This solution can be **expanded to Forex, Indices, and Crypto markets**, enabling automated 
high-frequency trading strategies.

---

### Training Data  
For model training, we used the following dataset:  
🔗 [Ethereum Data to Predict the Gold Market](https://www.kaggle.com/datasets/angelvarela/ethereum-data-to-predict-the-gold-market)

---

## System Architecture  

AchillesV1 combines **three key components** to generate automated trading decisions:  

The Implementation posses three components:

- A Deep Learning model to predict the desired market (in this case gold).
- A Natural Language Processing model to extract the sentiment and probabilities of in-real-time-news.
- Our Trading bot where everything merges. It uses the predictions of the model along with the probabilities & sentiment for automatic trading.

### 🧠 1. LSTM Neural Network for Market Prediction  
AchillesV1 applies an **LSTM model trained on seasonal time frames**:
- **15m, 5m, and 1m** historical data from **Ethereum vs USD**
- Predicts **future price movements** for high-accuracy trading  

📌 **Why Gold?**  
Gold (XAU-USD) was chosen for its **high leverage & predictable trends**, outperforming 
volatile assets like **Bitcoin BTC-USD or GBP-USD**.

---

### 📰 2. Sentiment Analysis with FinBERT  
This component extracts **real-time sentiment** from financial news sources:  

-  [Benzinga](https://www.benzinga.com) (XAU-USD)  
-  [Investing.com](https://www.investing.com) (XAU-USD)  
-  [Financial Times](https://www.ft.com) (General Market News)  
*(Additional sources can be added as needed.)*

🛠 **Why Sentiment Analysis?**  
Market forecasts alone **aren't enough**—news & real-world events drive investor behavior.  
AchillesV1 ensures **real-time market responsiveness** before executing trades.

---

### 🤖 3. Automated Trading Bot  
This component **merges predictions & sentiment analysis** to:

- Execute **buy & sell orders** automatically  
- Implement **risk management strategies**  
- Adjust **position sizing based on volatility**  

At the end of a **one-month experiment**, running **Monday-Friday** (market open days), 
AchillesV1 achieved:  

** 182% return on investment**  

---

##  Key Takeaways  
✅ **Stock markets CAN be predicted**  
✅ **You don’t need to watch charts all day to invest**   

---

##  Coming Soon  
 **A research paper detailing AchillesV1’s methodology & results (182% ROI!)**  
