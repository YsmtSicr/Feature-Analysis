# Linguistic feature analysis tool using LSTM with Attention  
# ファイル構成  
* main.ipynb:分析ツール本体  
* LSTM:LSTM等のパッケージ  
  * attention_layer.py
  * attention_seq2seq.py
  * base_model.py
  * config.py
  * functions.py
  * layers.py
  * np.py
  * optimizer.py
  * peeky_seq2seq.py
  * seq2seq.py
  * time_layers.py
  * trainer.py
  * util.py
* README.md:
# 環境  
google colabratoryにて動作を確認
# 必要ライブラリ  
* matplotlib  
* numpy  
* cupy(GPUモード使用時)
* os
# Note  
* 入力データを含むファイルパスは、自身の環境に合わせて修正が必要
