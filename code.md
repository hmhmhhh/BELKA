# モデル

* XGBoostを使っている https://www.kaggle.com/code/ricopue/leashbio-xgb-ecfp-10m-sample-rows/notebook  
  * 特徴量はVarianceThresholdで特徴量選択を実施
  * bindのみを目的変数とするのではなく、各DNAごとに目的変数を設定して予測を実施
  * scale_pos_weight を設定して、テストデータ全体の陽性の割合を引数に入れている

* 1dCNN https://www.kaggle.com/code/ahmedelfazouan/belka-1dcnn-starter-with-all-data
  * この精度がかなり良い印象
  * AVGPOOLを取るべきらしい

* chemBERTa https://www.kaggle.com/code/tetsuya3510/leash-bio-chemberta-baseline (要確認)

* GraphNN
  *  https://www.kaggle.com/code/hengck23/lb0-602-graph-nn-example これが精度よさそう
  * https://www.kaggle.com/code/agastyapulapaka/leash-tutorial-molecular-graphs-and-gnns

* AUTOML
  * https://www.kaggle.com/code/motono0223/leash-bio-automl-baseline
  * 実行するとあまり精度でず....



# 前処理
*Tokenize https://www.kaggle.com/code/horikitasaku/0-589-tokenize-in-terms-of-chemical-principles/notebook　？？
