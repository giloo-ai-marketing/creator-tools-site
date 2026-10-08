# Giloo Creator Tools 介紹頁

給釜山影展用的一頁式介紹，中英切換，五個工具。

- 正式網址：https://giloo-ai-marketing.github.io/creator-tools-site/
- 原型 POC：https://giloo-ai-marketing.github.io/creator-tools-poc/

## 結構

- `index.html`：中英切換的產品介紹頁
- `workspace.html`：第二層工作區／對話流程，以及聊天成品卡與按需開啟的報告預覽
- `festival-kit.html`：英文文案與字幕翻譯的複合工作流程，以及含總覽／文案／字幕分頁的送件包預覽
- `shots/`：介紹頁使用的產品截圖

網站沒有建置流程，可直接用瀏覽器開啟，或啟動任意靜態檔案伺服器預覽。

語言切換用 `#p[data-lang]` 加 CSS 顯示隱藏，預設英文，會記住選擇並偵測瀏覽器語言。

## 表單

照 Netlify Forms 規格寫（`data-netlify`、honeypot、`form-name`）。
GitHub Pages 上按送出只會顯示成功畫面，**收不到 email**。
要真的收，部署到 Netlify，並在後台手動開啟表單偵測。
