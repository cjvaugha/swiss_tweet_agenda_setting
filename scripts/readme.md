
The files in this directory are the two main scripts that I wrote to perform the tasks.

Classify_tweets.py is a Google Colab Jupyter notebook which reads in the training data and builds a text-classification model using the FastText n-gram model. Specific algorithmic information is unknown. Average precision and recall are consistently about 0.94.

Generate_graphs_analyze.py is a Google Colab Jupyter notebook which reads in the classified data and graphs the data as time series and then tests for Granger's Causality, Johannsen's Cointegration, Augmented Dickey-Fuller and then a VAR(p,d,q) of lag order 1.
