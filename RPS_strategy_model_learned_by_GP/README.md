# 概要
## Strategy_model
GPが一対の手の系列データ(人・コンピュータのじゃんけんデータ)から学習した戦略モデルを格納する。

## GP_Hand_series_data
GPが学習したモデルが出力した手の系列データを格納する。


# GPの学習方法について
人が出した手の系列と、その人と対戦したプログラムが出した手の系列から学習。

戦略モデルの評価は、人が出した手の系列に対して「あいこ」の回数が多いもの、つまり人の手の系列と同じ手の系列を出力するモデルの獲得を目指したもの。
