# Fiisual_2nd-Round
2nd Round interview files for Fiisual

# Goodinfo 股市資料爬蟲與資料庫建置專案

本專案負責從 [Goodinfo! 台灣股市資訊網](https://goodinfo.tw) 擷取個股資訊，並將其標準化後存入本地資料庫。支援的資料類型包括：
- 公司基本資料
- 個股日行情資料（日 K 線）

## 📁 專案結構說明
project-root/
├── environment.yml # Conda 環境設定檔
├── main.py # 主程式（執行爬蟲與寫入資料庫）
├── utils/ # 資料處理與爬蟲輔助模組
├── data/ # 可選：範例輸出或測試資料
├── output/ # 可選：儲存資料庫檔案（如 SQLite）
└── README.md # 本文件

## ⚙️ 安裝與啟動說明

### 1. 建立 Conda 環境

請先安裝 Anaconda 或 Miniconda，然後於終端機輸入：

```bash
conda env create -f environment.yml
conda activate /Users/liumeow/Documents/工作/fiisu_test/env
```

2. 執行主程式

