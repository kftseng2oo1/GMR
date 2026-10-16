# 早安卡片 · 產生器（GOOD MORNING）

做 LINE 早安圖：選背景、套祝福語、調字型顏色，可用 AI 生成祝福語、清除原圖文字，還能匯出有聲動畫影片。

**線上使用**：https://kftseng2oo1.github.io/GMR/

## 主要功能
- 內建主題背景（旭日東昇、花語春風、海天一色、禪意蓮池…），也可上傳自己的照片（相簿存在本機）
- 祝福語分類：早安問候、平安祝福、勵志等，或「✨ AI 幫我生成祝福語」
- 字型（明朝、圓體、宋體、黑體）、顏色、直排／橫排、位置可調
- **✨ AI 清除圖片文字**：AI 偵測照片上的字，自動或手動框選後修補
- **🎬 有聲影片**：文字逐句動畫配上語音朗讀，錄成影片
- 📥 儲存圖片、📤 分享到 LINE

## 技術與依賴
- 單檔 HTML PWA（`index.html` 內含全部 HTML/CSS/JS），`manifest.json` + `sw.js` 提供安裝到主畫面與離線快取。
- AI 與語音：`arcar.kftseng2oo1.workers.dev`（Claude `claude-sonnet-4-20250514`、`/tts`）
- Canvas 繪圖、`MediaRecorder` 錄影、Web Audio、Web Share

## 相關
- 新版為 `morning-card-v3.html`（LINE 早安圖片 App），這個 repo 是較早的版本
