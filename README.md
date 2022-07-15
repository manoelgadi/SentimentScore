# SentimentScore

Repository of the supervised retraining of FinBERT using the Few-Shot Learning strategy with CryptoLin dataset.
SentimentScore development is part of the GDELT CRYPTOCURRENCY CURATED EVENT DATABASE project by Manoel Gadi and Miguel-Angel Sicilia.

For sentiment score, a set of pre-trainned algorithms were compared, with the final retraining of FinBERT algorithm using few-shot learning strategy (FSL) with the 

The data set chosen for the FSL strategy was CryptoLin,  a manually annotated cryptocurrency news event data set with discrete values representing negative, neutral and positive news respectively. CryptoLin was extracted from https://coinmarketcal.com/en/news containing 2683 news from July 2018 to January 2022 with 1236 positive news, 1134 neutral news and 313 negative news. The data was used for retraining FinBERT classification model to assess if a news is positive, neutral or negative. After hyper-parameter optimization, the best set of parameters obtained can be seen in results. Data was split into 2147 news for training and 536 news for test data. The retrained FinBERT achieved the following metrics per class.
