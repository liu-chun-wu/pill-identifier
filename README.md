# 💊 Pill Identifier

一個整合圖像辨識與網頁爬蟲的藥物查詢系統。使用者可以上傳藥物圖片或輸入藥名，系統會辨識藥品後，自動爬取相關資訊並回傳給使用者。

---

## 📌 功能說明

- 📷 **圖像上傳辨識**：使用者可上傳藥物圖片，系統會利用訓練好的 YOLOv11 模型進行辨識。
- 🔍 **藥名查詢**：使用者亦可直接輸入藥品名稱查詢。
- 🌐 **爬取藥品資訊**：根據辨識結果，自動到官方網站爬取對應藥物的詳細資料。
- 📋 **資訊展示頁面**：透過 Gradio 前端展示辨識結果與爬取的藥品資訊。

---

## 🛠️ 使用技術

| 類別       | 技術與工具 |
|------------|-------------|
| 🧠 模型     | YOLOv11 (`yolov11x`) |
| 🖼️ 資料集   | [Pharmaceutical Drugs & Vitamins - Synthetic Images](https://www.kaggle.com/datasets/vencerlanz09/pharmaceutical-drugs-and-vitamins-synthetic-images) |
| 🕷️ 爬蟲     | Selenium |
| 🔗 爬蟲目標網站 | [Philippine FDA Drug List](https://verification.fda.gov.ph/drug_productslist.php) |
| 💻 展示介面 | Gradio |
| 🐧 部署環境 | Linux（本地部署） |

