# Linguistic feature analysis tool using LSTM with Attention  
# ファイル構成  
* main.ipynb:分析ツール本体  
* LSTM:LSTM等のクラスファイル  
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
# 使用方法
1. main.ipynbを開く。
2. 3つ目のセルにて、入力データファイルを指定し、ハイパラメータを調整。
3. 1つめのセルから順に実行
# Note  
* 入力データを含むファイルパスは、自身の環境に合わせて修正が必要
* GPUモードを利用しない場合、config.pyを開き、GPU = TrueをFalseに変更する。
