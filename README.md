# 📅 課表 | 網頁切版

本專案為原生 HTML Table 切版練習，深入實作複雜的儲存格合併邏輯，結合CSS3定位與漸層技巧達成視覺還原。

## 📝 實作重點

- **儲存格合併**：運用 `rowspan="15"` 與 `colspan="5"` 結構，處理縱向教師名單與橫向跨日固定作息，維持網頁語意架構完整。
- **純 CSS 線性漸層斜線**：捨棄背景圖片，利用 `linear-gradient` 繪製對角線，並搭配 `position: absolute` 定位文字，重現課表左上角「星期/時間」分割。
- **網頁佈局與文字優化**：啟用 `table-layout: fixed` 鎖定欄寬，並巧用 `letter-spacing` 與 `padding-left` 修正字距，讓橫向合併文字呈現絕對視覺居中。

## 🛠 使用技術

- **HTML5**：`<table>`, `<colgroup>`, `rowspan`, `colspan` 語意化結構
- **CSS3**：線性漸層（Linear Gradient）、絕對/相對定位、字距控制（Letter Spacing）
