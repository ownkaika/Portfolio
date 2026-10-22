# MIC AI 語音鍵盤

> 把語音辨識直接放進輸入法，讓使用者不用切換 App 就能輸入文字。

**領域**：Android / AI　｜　**專案狀態**：持續改善

[← 回作品集首頁](../README.md)

## 這是什麼作品？

這是我為了讓使用者在聊天、搜尋或筆記時直接說話輸入，而開發的 Android AI 鍵盤。不必另外打開錄音 App，辨識後的文字會嘗試直接回填到輸入框。

### 主要特色

鍵盤錄音、Gemini 語音轉文字、複製與回填；回填穩定性仍持續改善。

### 技術重點

Android IME、InputConnection、Vercel API 與 Gemini 轉錄。

> 下方兩張圖直接顯示在本頁，無須點開 SVG 原始碼。

## 01｜應用操作流程

從使用者角度，看一次主要操作如何完成。

![MIC AI 語音鍵盤 的應用操作流程](../assets/diagrams/mic-app.svg)

## 02｜技術架構流程

從資料、模組與服務的角度理解專案。這是**高層次架構示意**，不是自動產生的完整程式碼呼叫圖。

![MIC AI 語音鍵盤 的技術架構流程](../assets/diagrams/mic-tech.svg)

### 使用或接觸的技術

- Android IME
- Gemini API
- Vercel
- 錄音狀態

### 資料與驗證說明

依 Mic README 中的轉錄路徑、IME 與回填實作整理。 圖中只呈現代表性流程，不等同所有功能已完成或通過實機驗收。

原始碼儲存庫 `ownkaika/Mic` 保持私人，不需公開給外部讀者。

---

[← 返回作品集目錄](../README.md)
