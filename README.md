# 寶石傳說 · Gem Legend

一款純 HTML + JavaScript 製作的寶石三消遊戲，無需任何後端，直接用瀏覽器開啟即可。

## 功能
- 🎯 單人闖關模式（8 關，含分數目標 & 寶石收集目標）
- 🎮 雙人即時對戰（需透過 claude.ai Artifact 執行以使用 room/db 功能）
- 💥 五連炸彈機制
- 🎵 純程式生成背景音樂 & 音效（Web Audio API）
- 🎊 勝利彩花動畫

## 部署到 GitHub Pages
1. 把 `index.html` 推上 GitHub repository
2. 到 Settings → Pages → Source 選 main branch
3. 網址格式為 `https://<你的帳號>.github.io/<repo名稱>/`

## 注意
雙人對戰功能使用 claude.ai 的 `room` 和 `db` capabilities，
需在 claude.ai Artifact 環境內才能使用。
若部署到 GitHub Pages，僅單人模式可正常運作。

## 技術
- 純 HTML5 / CSS3 / Vanilla JS，零依賴
- Web Audio API（程式合成音效）
- CSS Grid 棋盤佈局
- SVG 寶石圖形
