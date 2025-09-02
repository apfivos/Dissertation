Hello, If you are reading this before commiting some time and make this repo beautifull then:
All the info about risk free rate, sp500 tickers that have been used are available at the repo and you need to download...

About the volatility surface that has been imported, unfortunately i cannot upload even the parquet file because I do not own the rights you need to download mannualy from wrds. 
In order to replicate my query you need to choose the volatility surface with tickers from the txt sp500_tickers_all_2000_2023.txt dates to expiration >=30 and <=730  and choose these variables: delta,impl_volatility, impl_strike, impl_premium, cp_flag, tikcer, index_flag then in order to import it as an input you need to create a column named "month" that will be used for the link between options and vol surface, the column should have the format as follows: 01-"month that the option was issued"-"uear that the option was issued"
