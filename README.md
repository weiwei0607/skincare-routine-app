# 🧴 Skincare Routine Builder — 保養流程助手

> 幫你設計個人化保養流程，避開成分衝突

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-E34F26?logo=html5" />
  <img src="https://img.shields.io/badge/CSS-3-1572B6?logo=css3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## ✨ 功能

- **🧪 成分庫** — 內建常見保養品成分資料（A醇、維他命C、玻尿酸、酸類等）
- **⚠️ 衝突檢測** — 自動檢測成分間的配伍禁忌（如 A醇+酸類）
- **☀️🌙 早晚分流** — 區分早/晚/早晚皆可使用的成分
- **📋 流程管理** — 新增、刪除保養品，建立個人化流程
- **🏷️ 預設產品** — 內建常見產品快速選擇
- **🤖 AI 分析** — 輸入文字描述或上傳產品照片，由 Gemini AI 自動識別成分與建議使用順序（含 30 分鐘快取）
- **⏳ 效期追蹤** — 記錄開封日期與 PAO（開封後使用期限），自動計算到期倒數
- **🔁 使用頻率** — 支援每天／每週 2-3 次／每週 1 次標記
- **📤 匯出分享** — 一鍵下載個人保養流程清單
- **💾 本地儲存** — 資料儲存在 localStorage

---

## 🚀 使用方式

純靜態 HTML，無需建置：

```bash
cd skincare-routine-app
open index.html
```

> **AI 分析功能**：需自備 [Gemini API Key](https://aistudio.google.com/apikey)，於頁面右上角 ⚙️ 設定。Key 僅保存在當次瀏覽器工作階段（session），不會寫入 localStorage。

---

## 📁 專案結構

```
skincare-routine-app/
└── index.html          # 單一檔案完整應用
```

---

## 📝 License

MIT License © 2026
