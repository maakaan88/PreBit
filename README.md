# PreBit - a multimodal model to predict Bitcoin price movement using Twitter and FinBERT

This is the repo accompanying the paper: ["A multimodal model with Twitter FinBERT embeddings for extreme price movement prediction of Bitcoin"](https://arxiv.org/abs/2206.00648)

Zou, Y., & Herremans, D. (2022). A multimodal model with Twitter FinBERT embeddings for extreme price movement prediction of Bitcoin. arXiv preprint arXiv:2206.00648.

Abstract: 
Bitcoin, with its ever-growing popularity, has demonstrated extreme price volatility since its origin. This volatility, together with its decentralised nature, make Bitcoin highly subjective to speculative trading as compared to more traditional assets. In this paper, we propose a multimodal model for predicting extreme price fluctuations. This model takes as input a variety of correlated assets, technical indicators, as well as Twitter content. In an in-depth study, we explore whether social media discussions from the general public on Bitcoin have predictive power for extreme price movements. A dataset of 5,000 tweets per day containing the keyword 'Bitcoin' was collected from 2015 to 2021. This dataset, called PreBit, is made available online. In our hybrid model, we use sentence-level FinBERT embeddings, pretrained on financial lexicons, so as to capture the full contents of the tweets and feed it to the model in an understandable way. By combining these embeddings with a Convolutional Neural Network, we built a predictive model for significant market movements. The final multimodal ensemble model includes this NLP model together with a model based on candlestick data, technical indicators and correlated asset prices. In an ablation study, we explore the contribution of the individual modalities. Finally, we propose and backtest a trading strategy based on the predictions of our models with varying prediction threshold and show that it can used to build a profitable trading strategy with a reduced risk over a `hold' or moving average strategy.

Full dataset [available on Kaggle](https://www.kaggle.com/datasets/zyz5557585/prebit-multimodal-dataset-for-bitcoin-price). 

