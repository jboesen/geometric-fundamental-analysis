 - Model architecture in ``geometric-fundamental-analysis/diffpool_helpers/model/encoder.py``
 - Data cleaning under ``cleaning_*.ipynb``
   1. ``cleaning_json.ipynb``: imports json-formatted stock data [https://www.kaggle.com/datasets/finnhub/reported-financials](downloaded from Kaggle) and exports dictionary of dataframes
   2. ``cleaning_prices.ipynb``: imports price data from [hd.com/financial-apis/bulk-api-eod-splits-dividends/](EODHD API), normalizes it, and exports into dictionary
   3. ``cleaning_graphs.ipynb``: takes exports from the previous two files and combines into test and train graph datasets
 - Benchmark model (LSTM + PCA) in ``benchmark.ipynb``
 - Training model in ``train.ipynb``
 - Evaluation on test dataset in ``evaluation.ipynb``
