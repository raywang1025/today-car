# 今日車車 Today's Car

給小小車迷的每日一車：每天自動輪播一台世界各地的特殊車輛（消防車 🚒 → 救護車 🚑 → 警車 🚓 依日輪替），附小孩聽得懂的介紹和一個親子討論問題。

- 網站：https://raywang1025.github.io/today-car/
- 單一 HTML 檔，無後端；以台北時間按日期自動切換，網址永遠同一個
- 照片來自 Wikimedia Commons（各圖授權標示於頁尾）
- 測試用：`?d=N` 可預覽第 N 天的車

## 新增車輛

編輯 `index.html` 裡的 `VEHICLES` 陣列，照現有格式加一筆即可（cat 支援 `fire` / `amb` / `police`，之後要加挖土機等新類別時在 `CATS` 加一項）。
