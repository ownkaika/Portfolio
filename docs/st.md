# ST Telegram 快速分享

> 從任何支援分享的 App，直接將資料存到 Telegram 我的收藏。

**領域**：Android　｜　**專案狀態**：開發作品

[← 回作品集首頁](../README.md)

## 這是什麼作品？

ST 是為習慣使用 Telegram「我的收藏」整理資訊的人設計的 Android 分享工具。我希望看到網頁、文字或圖片時，可以從原本的 App 直接分享並收藏，省去手動切換到 Telegram 的步驟。

### 主要特色與使用情境

接收瀏覽器、相簿等 App 的 Android 分享內容，透過簡潔操作送到 Telegram Saved Messages。

### 技術重點

Android ACTION_SEND、URI 臨時授權、TDLib 及 Telegram 帳號連線。

> **看圖提示**：下方兩張圖已直接顯示在本頁，無須點開 SVG 原始碼。

## 01｜應用操作流程

從使用者角度，看一次主要操作如何完成。

![ST Telegram 快速分享 的應用操作流程](../assets/diagrams/st-app.svg)

## 02｜技術架構流程

從資料、模組與服務的角度理解專案。這是**高層次架構示意**，不是自動產生的完整程式碼呼叫圖。

![ST Telegram 快速分享 的技術架構流程](../assets/diagrams/st-tech.svg)

### 使用或接觸的技術

- Android Intent
- TDLib
- Telegram
- URI 權限

### 資料與驗證說明

依 ST README 的 ACTION_SEND、TDLib 與分享操作整理。 圖中只呈現代表性流程，不等同所有功能已完成或通過實機驗收。

原始碼儲存庫 `ownkaika/ST` 保持私人，不需公開給外部讀者。

---

[← 返回作品集目錄](../README.md)
