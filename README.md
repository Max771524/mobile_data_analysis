**Mobile Phone Data Analysis 數據分析專案**

主程式:mobile_data_analysis.ipynb

## 專案簡介

  - 資料來源：Kaggle 手機產品資料

  - 主要分析方向：探索價格、規格與評價的關係


## 資料載入與初步觀察


  - 使用 pandas 載入資料

  - 檢查資料筆數與欄位

  - 使用 .info()、.describe()、.head() 等函式初步檢查內容

## 資料清理與處理

  - 處理缺失值（缺失欄位與筆數）


## 探索性資料分析

  - 整體價格、評價、spec 分數的分布

  - 哪些變數可能與評價/spec 分數高度相關

## 問題分析

  - 針對提出的問題進行分析與視覺化

  ** 散佈圖觀察關係

## 使用 SQL 查詢分析

  - 建立 SQLite 資料庫並寫入 pandas 資料表

  - 使用 sqlite3 + pandas.read_sql() 查詢：

  - 不同價格區間平均評價


## 資料視覺化

  - 使用 matplotlib / seaborn 呈現分析結果

## 結論與發現

  - 總結從分析中得出的洞察
