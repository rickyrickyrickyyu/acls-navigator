# ACLS 2025 Navigator v33

> 🫀 即時 ACLS（Advanced Cardiovascular Life Support）急救流程導航工具，基於 2025 AHA/台灣混合指引。

[![GitHub Pages](https://img.shields.io/badge/Demo-Live-brightgreen?style=flat-square&logo=github)](https://rickyrickyrickyyu.github.io/acls-navigator/)

## 🚀 線上使用

**👉 [https://rickyrickyrickyyu.github.io/acls-navigator/](https://rickyrickyrickyyu.github.io/acls-navigator/)**

支援電腦、平板、手機（自動適配螢幕大小）。

## 📋 功能

### 心搏停止（Pulseless）模組
- **VF / pVT** — 電擊建議流程（200J），自動追蹤電擊次數
- **PEA / Asystole** — 不可電擊心律 CPR 流程
- 2 分鐘 CPR 計時器 + 自動節律檢查提醒
- Epinephrine / Amiodarone / Lidocaine 藥物管理與計時
- ROSC（恢復自主循環）後照護流程

### 非心搏停止模組
- **Bradycardia（心搏過緩）** — Atropine、TCP、Dopamine、Epinephrine drip
- **Tachycardia（心搏過速）** — Narrow/Wide QRS 分流、Adenosine 階梯、Cardioversion

### 通用功能
- ⏱️ 全程計時器（精確到秒）
- 📋 即時事件記錄（含時間戳）
- 📝 結案報告自動生成（Chronological / SOAP 格式）
- 📋 一鍵複製紀錄
- 🌙/☀️ 深色/淺色模式切換
- ↩️ 返回上一步 + Undo 功能
- 🔄 節律轉換（任意模組間切換）

## 🛠️ 技術細節

| 項目 | 說明 |
|------|------|
| 架構 | 單一 HTML 檔案（Zero Dependencies） |
| 前端 | Vanilla HTML + CSS + JavaScript |
| 部署 | GitHub Pages（靜態託管） |
| 響應式 | 6 個 CSS Media Query 斷點 |
| 支援裝置 | 手機（≥320px）、平板、桌面、大螢幕 |

### 響應式斷點

| 斷點 | 目標裝置 |
|------|---------|
| ≤ 360px | 超小螢幕手機（iPhone SE 等） |
| 361–480px | 一般手機 |
| 481–768px | 平板 |
| ≥ 769px | 桌面電腦 |
| ≥ 1200px | 大螢幕 |
| landscape + ≤500px 高 | 手機橫屏 |

## 📦 本地開發

不需要任何建置工具，直接用瀏覽器開啟即可：

```bash
# Clone
git clone https://github.com/rickyrickyrickyyu/acls-navigator.git

# 直接開啟
open index.html
```

## 📄 授權

本專案僅供 **醫療教育與模擬訓練** 使用。

> ⚠️ **免責聲明**：本工具不構成醫療建議。實際急救處置請依據最新臨床指引、機構規範及專業醫療判斷。

## 📚 參考指引

- [AHA ACLS Guidelines 2025](https://www.heart.org/)
- 台灣急診醫學會 ACLS 課程教材
