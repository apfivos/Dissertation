Hello, If you are reading this before commiting some time and make this repo beautifull then:
All the info about risk free rate, sp500 tickers that have been used are available at the repo and you need to download...

About the volatility surface that has been imported, unfortunately i cannot upload even the parquet file because I do not own the rights you need to download mannualy from wrds. 
In order to replicate my query you need to choose the volatility surface with tickers from the txt sp500_tickers_all_2000_2023.txt dates to expiration >=30 and <=730  and choose these variables: delta,impl_volatility, impl_strike, impl_premium, cp_flag, tikcer, index_flag, secid as dates you should choose from 01-01-2000 till 31-12-2022 then run the file vol_filtering.

In order to run the files you should run first the file data_cleaning_and_pca and afterwards the cnn_node_analysis
