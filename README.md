藥物圖像辨識+爬蟲
===
# 功能說明
- 使用者可以上傳藥物的圖片或是輸入藥物的名稱，程式會根據圖像辨識的結果去網站查取相關的資訊
- 爬取資訊後可以在資訊頁面查看藥物的資訊以及圖像辨識的結果

# 實作技術
- 在 Kaggle 上使用資料集 finetune yolov11，然後在部屬在本地的linux上
    - 模型 : yolov11 –  yolo11x
    - 資料集 : https://www.kaggle.com/datasets/vencerlanz09/pharmaceutical-drugs-and-vitamins-synthetic-images
    - 爬蟲 : selenium
    - 爬蟲的網站 : https://verification.fda.gov.ph/drug_productslist.php
    - 展示頁面 : gradio

