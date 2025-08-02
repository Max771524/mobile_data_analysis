\*\***Mobile Phone Data Analysis 數據分析專案**\*\*



\## 專案簡介



&nbsp;  - 資料來源：Kaggle 手機產品資料



&nbsp;  - 主要分析方向：探索價格、規格與評價的關係



&nbsp;  - 預期回答的問題：



&nbsp;   \* 哪個價格區間的評價比較好？



&nbsp;   \* 哪些零件（CPU、RAM、電池、螢幕、相機）對 spec\_score 影響最大？

&nbsp;   

\## 資料載入與初步觀察

&nbsp;  

&nbsp;  - 使用 pandas 載入資料



&nbsp;  - 檢查資料筆數與欄位



&nbsp;  - 使用 .info()、.describe()、.head() 等函式初步檢查內容



\## 資料清理與處理



&nbsp;  - 處理缺失值（缺失欄位與筆數）



&nbsp;  - 資料類型轉換



&nbsp;  - 建立新的欄位（如：價格區間、數值標準化等）



\## 探索性資料分析



&nbsp;  - 整體價格、評價、spec 分數的分布



&nbsp;  - 哪些變數可能與評價/spec 分數高度相關



\## 問題分析



&nbsp;  - 針對提出的問題進行分析與視覺化：



&nbsp;   \* Q1：哪個價格區間的評價比較高？



&nbsp;    \*\* 繪製箱型圖 / 長條圖 比較平均評價



&nbsp;   \* Q2：哪些規格（ram、battery、camera、display）對 spec\_score 有明顯影響？



&nbsp;    \*\* 散佈圖觀察關係



\## 使用 SQL 查詢分析



&nbsp;  - 建立 SQLite 資料庫並寫入 pandas 資料表



&nbsp;  - 使用 sqlite3 + pandas.read\_sql() 查詢：



&nbsp;  - 不同價格區間平均評價



&nbsp;  - 排名前 10 高 spec\_score 的手機



\## 資料視覺化



&nbsp;  - 使用 matplotlib / seaborn 呈現分析結果



\## 結論與發現



&nbsp;  - 總結從分析中得出的洞察



&nbsp;   \* 中高價手機評價較好



&nbsp;   \* RAM 和電池容量與 spec\_score 高度相關



