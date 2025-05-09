# AchillesV1 AI Driven Gold Trading with Sentiment Price Prediction

Ready to Predict the Future?

AchillesV1 is a AI driven implementation to invest in the stock market. This implemtation had a return on investment of 182% in a demo account. The trades were automatically placed by a trading bot designed to support the predictions of our predictions made by AchillesV1. This implementation can be expanded to more markets, such as Forex, Indices and Crypto. The bot sends high frequency trades in a demo account and is build to make profit even when you're sleeping!!

**For training we used the following DataFrame:
https://www.kaggle.com/datasets/angelvarela/ethereum-data-to-predict-the-gold-market/

The Implementation posses three components. 
A Deep Learning model to predict the desired market (in this case gold).
A Natural Language Processing model to extract the sentiment and probabilities of in-real-time-news.
And our Trading bot where everything merges. It uses the predictions of the model along with the probabilities & sentiment for automatic trading.


----->> First Component: (AchillesV1) LSTM Neural Network trained on seasonal Times Frames 15 Minutes, 5 Minutes and 1 Minute data of Ethereum vs USD, The purpose of this model is to predit the future of the desired symbol to predict. We decided to predict gold thanks to its leverage and predictability in comparison to other markets such as Bitcoin BTCUSD or Pound Sterling vs. US Dollar GBPUSD

----->>Second Component: FinBERT Sentiment Analysis to scratch and estimate the news in 3 different WebSites:

-https://www.benzinga.com (XAU-USD)

-https://www.investing.com (XAU-USD)

-https://www.ft.com (General Market News)

-(You can add more news websites if desired)

The purpose of this component is to have a real life test of the sentiment market with actual events. Because predictions are not 100% real we need a component to show us how the market is moving in real life. The Probabilities and Sentiments will be extracted in real time directly from the three websites before mentioned and will be used with a trading logic in our trading bot for automatic trading strategies.

----->> Third Component: Trading bot for Automatic Trading: The purpose of this component is to use the last two components for automatic trading. Using the predictions and sentiments to place orders meanwhile assessing risk management adding volatility factors such as positional sizing and many more. 

At the end of the experiment of one month with the bot running from monday to friday (open market days) we achieved a 182% return on investment with our strategy. Demostrating 1: The stock market CAN be predicted. 2: You don't need to look at charts all day to invest. 

Please note the incoming paper about this implementation with a 182% return (soon)




# AchillesV1: AI-Driven Gold Trading with Sentiment & Time-Series Forecasting

🚀 Ready to Predict the Future?

AchillesV1 is an AI-powered trading bot designed to **automate stock market investments**. 
In a **demo account**, this system achieved an **182% return on investment** by leveraging 
**deep learning market predictions** and **sentiment analysis from real-time news**.

This solution can be **expanded to Forex, Indices, and Crypto markets**, enabling automated 
high-frequency trading strategies.

---

##Training Data  
For model training, we used the following dataset:  
🔗 [Ethereum Data to Predict the Gold Market](https://www.kaggle.com/datasets/angelvarela/ethereum-data-to-predict-the-gold-market)

---

## System Architecture  

AchillesV1 combines **three key components** to generate automated trading decisions:  

The Implementation posses three components:

- A Deep Learning model to predict the desired market (in this case gold).
- A Natural Language Processing model to extract the sentiment and probabilities of in-real-time-news.
- Our Trading bot where everything merges. It uses the predictions of the model along with the probabilities & sentiment for automatic trading.

### 1. LSTM Neural Network for Market Prediction  
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

✅ Execute **buy & sell orders** automatically  
✅ Implement **risk management strategies**  
✅ Adjust **position sizing based on volatility**  

At the end of a **one-month experiment**, running **Monday-Friday** (market open days), 
AchillesV1 achieved:  

** 182% return on investment**  

---

##  Key Takeaways  
✅ **Stock markets CAN be predicted** 🧠  
✅ **You don’t need to watch charts all day to invest** 📊  

---

##  Coming Soon  
 **A research paper detailing AchillesV1’s methodology & results (182% ROI!)**  
