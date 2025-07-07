# cowrie-honeypot-analysis


## 專案簡介
本專案透過部署 Cowrie SSH 蜜罐，模擬一台易受攻擊的伺服器，並蒐集來自攻擊者的連線行為與登入紀錄。接著利用 Python 對 JSON log 進行分析，觀察密碼爆破、使用的工具、連線頻率等特徵。

## 主要功能
- 記錄所有 SSH 登入嘗試與指令輸入
- 分析常見帳號密碼組合
- 分析登入來源 IP 和工具（如 hydra）
- 可視化攻擊趨勢

## 使用工具
- [Cowrie](https://github.com/cowrie/cowrie)
- Python
- Git/GitHub

## 使用方式
1. 安裝並啟動 Cowrie
2. 收集 log（cowrie.json）
3. 執行 log 解析腳本
4. 產出統計報表或視覺化圖表


