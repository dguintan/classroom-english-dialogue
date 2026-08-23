# 教室英語十回合對話練習 PWA v1.3

## GitHub Pages 部署
1. 將 index.html、manifest.json、service-worker.js 與 icons 資料夾全部上傳到同一個 GitHub Repository 的根目錄。
2. 到 Settings → Pages。
3. Source 選 Deploy from a branch。
4. Branch 選 main，資料夾選 /(root)，儲存。
5. 等待 GitHub Pages 產生 HTTPS 網址。

## iPad / iPhone 安裝
1. 用 Safari 開啟 GitHub Pages HTTPS 網址。
2. 點分享圖示。
3. 選「加入主畫面」。
4. 後續可從主畫面像 App 一樣開啟。

## 注意
- 直接從「檔案」App 開 index.html，不會啟用完整 PWA。
- Service Worker 需要 HTTPS（localhost 開發環境除外）。
- 語音辨識仍受 Safari / iPadOS 的瀏覽器支援與權限設定影響。
