# モデル

* XGBoostを使っている https://www.kaggle.com/code/ricopue/leashbio-xgb-ecfp-10m-sample-rows/notebook  
  * 特徴量はVarianceThresholdで特徴量選択を実施
  * bindのみを目的変数とするのではなく、各DNAごとに目的変数を設定して予測を実施
  * scale_pos_weight を設定して、テストデータ全体の陽性の割合を引数に入れている
