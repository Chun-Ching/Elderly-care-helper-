# Elderly-care-helper

## 銀髮照護小幫手
本系統使用 Arduino 與 Android Studio 來開發，可分成幾
個部分，有壓力感測、溫度感測、一氧化碳以及氣體偵測感測
器，之後將感測器安裝在照明設備的燈座中，會透過 WI-FI 的
方式將感測器偵測到的數據整合至由 Firebase+ThingSpeak 所
結合的雲端伺服器中再由 WI-FI 傳送至安卓手機 APP 中，可以
查看即時數據和歷史數據圖表，當發現偵測到的數據超過預設
值時，會傳送推播通知至使用者的手機 APP，可即時監控長者狀
況。

1. 藉由軟硬體的整合，將物聯網的技術應用在居家照護系統上
2. 居家照護系統結合日常生活設備
3. 即時掌握銀髮族狀況
4. 改善照護人力缺口大，減緩人力不足問題
