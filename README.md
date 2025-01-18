# lstm_stock_prediction

データ分析用に
Pandas,Matplotlib,numpy,pandas_taのライブラリをインストールして下さい

pandas_ta.momentum import momImportError: cannot import name 'NaN' from 'numpy'
というエラーがでる場合は以下の
.conda\envs\”環境名”\Lib\site-packages\pandas_ta\momentum\squeeze_pro.py
from numpy import NaN as npNaN
を
from numpy import nan as npNaN
に変更してください

LSTM用は以下をインストールして下さい
scikit-learn,tensorflow

同じフォルダに"stock_price.csv"を置いて実行すれば、動作します。

