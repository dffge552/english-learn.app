# 📚 全方位英文訓練平台 — 含 AI 助教

> 一款專為台灣學測（GSAT）設計的英文學習平台，整合 7000 單字庫、AI 寫作批改、錯題本與翻譯練習，幫助學生高效備考。

🔗 **線上體驗**：[english-write-trainer.netlify.app](https://english-write-trainer.netlify.app/)

## 🏆 平台亮點

> ✨ **經實測，AI 可穩定生成學測 17-20 分的高分英文作文！**  
> 不只是批改，更能「示範怎麼寫」，是學生自學與教師備課的最佳幫手。

## ✨ 特色功能

### 📖 單字測驗模式
- 內建 **大考中心 7000 單字** + **76 萬字完整辭典**
- 支援 **出英文選中文** / **出中文選英文** 雙向測驗
- 可依 **Level 1～6** 篩選練習範圍
- 內建 **快速模式（本地 AI）** 與 **智能模式（Groq / Gemini）**

### 🤖 AI 助教（單字學習）
- 即時造句、用法說明、例句生成
- 支援 **Groq（Llama 3.3）** 與 **Google Gemini** 雙 AI 引擎
- 對話記憶功能，可連續提問

### 📕 錯題本練習
- 自動收錄答錯單字
- 支援 **單字複習** 與 **錯題重測**
- 最多儲存 1000 筆，自動清除舊記錄

### ✍️ 英文寫作模式（含 AI 評分）
- 六大題型：主題式、漫畫、統計圖表、單圖、信函、雙圖比較
- **✨ 穩定生成學測高分範文（17-20分）**，可作為學習模板
- **AI 自動生成範文**（支援 Groq / Gemini）
- **AI 寫作助教**：文法檢查、結構分析、詞彙提升建議
- 依照 **學測 20 分評分標準** 給分（內容、組織、文法、字彙、體例）
- 支援 **拍照識別題目與作文**（OCR.space / Tesseract.js）

### 🌐 翻譯練習模式
- 中譯英練習，支援 **50 字內短句**
- **AI 精準翻譯**（Groq / Gemini）
- **AI 批改**：依照 4 分制評分，附標準答案與改進建議
- 支援 **拍照 / 貼圖識別題目與翻譯**

### 📷 拍照識別功能
- 辨識 **寫作題目、學生作文、翻譯題目、手寫翻譯**
- 支援 **OCR.space（雲端）** 與 **Tesseract.js（離線）** 雙模式
- 自動壓縮圖片、語言偵測（中 / 英）

### 📊 學習統計
- 累計答題數、總分、正確率
- 統計資料儲存於瀏覽器（localStorage）

## 🧠 AI 模式說明

| 模式 | 說明 | 是否需要 API Key |
|------|------|------------------|
| ⚡ 快速模式 | 本地 AI，即時回應，支援造句 / 用法 / 例句 | 否 |
| 🧠 智能模式 | Groq（Llama 3.3），更準確的回應 | ✅ 需要 [Groq API Key](https://console.groq.com/) |
| 💎 Gemini 模式 | Google Gemini 2.5 Flash-Lite，免費且快速 | ✅ 需要 [Gemini API Key](https://aistudio.google.com/) |

> 💡 寫作與翻譯功能僅支援 **智能模式** 或 **Gemini 模式**

## 🛠️ 使用技術

- **前端**：HTML5 / CSS3 / JavaScript (ES6+)
- **AI 服務**：Groq API（Llama 3.3）、Google Gemini API
- **OCR 服務**：OCR.space API、Tesseract.js（離線）
- **部署**：Netlify
- **授權**：MIT License

## 🚀 快速開始

### 1️⃣ 線上使用（免安裝）
直接訪問：[https://english-write-trainer.netlify.app/](https://english-write-trainer.netlify.app/)

### 2️⃣ 本地執行
```bash
git clone https://github.com/你的帳號/english-writing-platform.git
cd english-writing-platform
# 使用任意 HTTP 伺服器執行
npx http-server .
# 或使用 VS Code Live Server
