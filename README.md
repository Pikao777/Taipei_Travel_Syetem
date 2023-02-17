# Taipei_Travel_Syetem
台北市旅遊規劃系統

# 實作流程
* Python爬蟲爬取Google Maps資訊
  * 餐廳/景點基本資訊 （景點定義為參考政府資料觀光平台-觀光資訊資料庫 https://data.gov.tw/dataset/7777 )
  * 餐廳/景點評論
* Python資料清整
  * 透過 Pandas、numpy 套件實現
* 資料視覺化
  * matplotlib / Seaborn / Plotly 套件繪圖
  * Tableau 製作互動式圖表
* 互動式地圖
  * Leaflet + OpenStreetMap 繪製旅遊地圖
* 自然語言處理( NLP ) - 訓練星等分類器( 1 - 5 星 )
  * 透過 Huggingface 所開源的 Transformers 配置 NLP 訓練任務
  * Fine-tune RoBERTa 預訓練模型 ( uer/roberta-base-finetuned-jd-full-chinese )
  * Dataset: Google maps 評論進行標記
* 網頁：
  * HTML / CSS / JavaScript 建構網頁
  * Python Web 框架： Django / Flask 雙版本
  * 網站部屬：AWS / GCP 雲端平台
