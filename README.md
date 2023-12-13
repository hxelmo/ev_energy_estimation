# EV energy estimation

## これは電気自動車（EV）のエアコンのエネルギー消費を予測するプロジェクトです。プロジェクトにはコード部分のみが展示されており、データは含まれていません。
## 各ファイルのタスク目的について：
### Data collection
get_data_from_db.ipynb  
データベースからの一部の天気データと実際のEVのエネルギー消費データを取得します  
google_api_ele  
Google Maps Elevation APIを使用して、道路の標高データを取得します  

### Data preprocessing
Prepare_dataset.ipynb    
データを初期的に統合・整理し、機械学習モデルの訓練に適用できるデータ構造に変換します  
Process_and_analyze_data.ipynb    
整理されたデータセットに対して、さらなる分析と処理を行います。たとえば、異常値の検出と除外など  

### Predictive model
いくつかの機械学習アルゴリズムをテストしました。結果から見ると、ランダムフォレストが最も適しているようです  
