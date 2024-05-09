**Project: Cryptocurrency Price Prediction using LSTM**

**Introduction:**
This project aims to predict cryptocurrency prices using Long Short-Term Memory (LSTM) neural networks. The dataset utilized in this project was scraped from blockchain.com, encompassing a comprehensive range of cryptocurrency prices over time. By employing LSTM, a type of recurrent neural network (RNN) capable of capturing long-term dependencies, we sought to develop accurate predictive models for cryptocurrency price movements.

**Dataset Description:**
The dataset comprises historical cryptocurrency price data obtained from blockchain.com. It includes information on various cryptocurrencies such as Bitcoin, Ethereum, Litecoin, and more. Each entry in the dataset contains timestamps along with corresponding cryptocurrency prices, reflecting fluctuations over time. The dataset is meticulously curated and provides a rich resource for training and evaluating predictive models.

**Methodology:**
1. **LSTM Model Development:** LSTM neural networks were chosen due to their ability to effectively capture sequential dependencies in time-series data. The models were trained on the dataset to learn patterns and trends in cryptocurrency prices.
  
2. **Grid Search:** To identify optimal hyperparameters for the LSTM models, a grid search approach was employed. This systematic exploration of hyperparameter combinations allowed us to fine-tune model performance and enhance predictive accuracy.
  
3. **Ablation Study:** Additionally, an ablation study was conducted to analyze the impact of individual components or parameters on model performance. By systematically removing or altering specific elements, we gained insights into their respective contributions to the predictive capabilities of the LSTM models.

**Publication:**
The findings and insights derived from this project were documented in a research paper. The paper presents a detailed analysis of LSTM-based cryptocurrency price prediction, including the methodology employed, experimental results, and implications for the field of cryptocurrency forecasting. It sheds light on the effectiveness of LSTM models in capturing complex patterns inherent in cryptocurrency price movements.

**Conclusion:**
This project demonstrates the application of LSTM neural networks for predicting cryptocurrency prices based on historical data scraped from blockchain.com. Through rigorous experimentation, including grid search and ablation study, we optimized model performance and gained valuable insights into the dynamics of cryptocurrency markets. The accompanying research paper provides a comprehensive overview of our methodology and findings, contributing to the growing body of knowledge in cryptocurrency forecasting.