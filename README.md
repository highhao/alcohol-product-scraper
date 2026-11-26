# 酒類商品資料擷取

## 專案情境

不同網站提供靜態或動態商品頁面；抓取流程分別處理來源，再將商品資料整理成共用欄位格式。

## 架構摘要

抽象抓取介面 → 靜態／動態來源抓取器 → 共用商品資料格式。

![靜態與動態來源擷取流程](docs/assets/workflow.svg)

## 後續優化建議

以固定 HTML 樣本測試來源解析結果，並記錄回應狀態與欄位缺漏，方便追查頁面結構變更。

English: A scraper design for static and dynamic product pages with a shared output schema.
