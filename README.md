Oil Temperature Prediction

**プロジェクト概要**
電力トランスフォーマーのオイル温度データを使用して、未来のオイル温度を予測するプロジェクト。
機械学習モデルを活用し、異常検知やメンテナンス最適化を目指す。

データ: ETDataset（電力トランスフォーマーのオイル温度データ）
目的: 異常検知、保守計画の最適化
使用モデル: XGBoost, ランダムフォレスト, 線形回帰

**環境構築**

**リポジトリのクローンとセットアップ**
   git clone https://github.com/whatagu917/oil-temp-prediction.git
   cd oil-temp-prediction
   pip install -r requirements.txt

**Jupyter をインストール**
   pip install jupyter

**データの前処理**
   notebooks/ フォルダをクリック
   preprocessing.ipynb を開く
   上部の「セルをすべて実行」ボタンを押して、前処理を完了させる
   preprocessed_data.csv が生成されたら成功
   
**モデルの学習**
   model.ipynb を開く
   上部の「セルをすべて実行」ボタンを押す
　 feature_correlation_after.csv が生成されたら成功

**仮説の検証**
   hypothesis1.ipynb を開く
   上部の「セルをすべて実行」ボタンを押す
   hypothesis2.ipynb を開く
   上部の「セルをすべて実行」ボタンを押す
   final_xgb_model_case2.pkl が生成されたら成功

**使用技術**
   Python, Pandas, Scikit-learn, XGBoost
   Jupyter Notebook
   GitHub Actions（CI/CD）

**ライセンス**
   MIT License
