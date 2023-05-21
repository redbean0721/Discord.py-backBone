[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

[![Python 3.6](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/release/python-3108/)

## :zap: Introduction 簡介

### **Python Discord BackBone**

一個基本的Python Discord機器人

<br>

## :inbox_tray: Installation 安裝指南
> 運行環境 建議 `Python 3.10` / `Pycord 2.3.3` 以上(含) or  `Docker v4.18.0` 以上(含)

使用內建Python
1. 下載並解壓整個專案
2. 安裝 `Python 3.10`
3. 在 Discord.py-backBone 資料夾運行 `pip install -r requirements.txt`
3. 將 `example.env` 重新命名為 `.env` 並將機器人TOKEN填入
4. 運行 `python src/main.py`

<br>

## :nut_and_bolt: Folder structure 資料夾結構
```
/ # 根目錄
------------------------------------
- .env # 機器人TOKEN
- .gitignore # 忽略的檔案
- Dockerfile # Docker鏡像創建文件
- README.md # 說明文件
- requirements.txt # 設定檔
- version.json # 機器人版本

/src # 程式碼放置處
------------------------------------
- main.py # bot 啟動主程式