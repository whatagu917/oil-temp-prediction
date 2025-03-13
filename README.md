Oil Temperature Prediction

#プロジェクト概要#
電力トランスフォーマーのオイル温度データを使用して、未来のオイル温度を予測するプロジェクト。
機械学習モデルを活用し、異常検知やメンテナンス最適化を目指します。

データ: ETDataset（電力トランスフォーマーのオイル温度データ）
目的: 異常検知、保守計画の最適化
使用モデル: XGBoost, ランダムフォレスト, 線形回帰

環境構築

1. リポジトリのクローンとセットアップ
   git clone https://github.com/whatagu917/oil-temp-prediction.git
   cd oil-temp-prediction
   pip install -r requirements.txt

2. データの前処理
   python scripts/preprocess.py
   
3. モデルの学習
   python scripts/model.ipynb

