# Giloo Creator Tools 介紹頁

給釜山影展用的一頁式介紹，中英切換，五個工具。

- 正式網址：https://giloo-ai-marketing.github.io/creator-tools-site/
- 原型 POC：https://giloo-ai-marketing.github.io/creator-tools-poc/

## 結構

單一 `index.html`，沒有建置流程。截圖放在 `shots/`。

語言切換用 `#p[data-lang]` 加 CSS 顯示隱藏，預設英文，會記住選擇並偵測瀏覽器語言。

## 表單

照 Netlify Forms 規格寫（`data-netlify`、honeypot、`form-name`）。
GitHub Pages 上按送出只會顯示成功畫面，**收不到 email**。
要真的收，部署到 Netlify，並在後台手動開啟表單偵測。
