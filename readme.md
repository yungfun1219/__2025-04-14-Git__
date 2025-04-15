# Python 環境建置

## 建置 Anaconda 開發環境
1. 下載 Anaconda: [Anaconda 官網](https://www.anaconda.com/)
2. 安裝步驟：
   - Next → I Agree → 選擇 All Users → Next
   - 勾選 Add Anaconda to the system PATH environment variable → Install

## Anaconda Prompt 管理模組
- 開啟 Anaconda Prompt 以系統管理者身份執行
- 常用指令：
  - 查詢模組列表：`pip list` 或 `conda list`
  - 查詢更新列表：`pip list --outdated` 或 `conda list --outdated`
  - 更新模組：`pip install -U 模組名稱` 或 `conda install -U 模組名稱`
  - 安裝模組：`pip install 模組名稱` 或 `conda install 模組名稱`
  - 指定版本安裝：`pip install 模組名稱==1.17.0`
  - 移除模組：`pip uninstall 模組名稱` 或 `conda uninstall 模組名稱`
  - 查詢模組詳細資料：`pip show 模組名稱`

## Spyder 編譯器
- 調整外觀：`Tools / Preferences → Appearance` 設定
- 程式除錯：
  - 錯誤標示：金探號或紅色 XX
  - 執行：`F5`
  - 設定中斷點：`F12`

## Jupyter Notebook 編譯器
- 開啟網址：`localhost:8888/`
- 常用快捷鍵：
  - `Run` 或 `Shift + Enter`：執行並新增 cell
  - `Ctrl + Enter`：執行但不新增 cell
  - 使用 Markdown 語法作筆記

## Python 語法

### 基本語法
- 變數定義：
  ```python
  變數名稱 = 變數值
