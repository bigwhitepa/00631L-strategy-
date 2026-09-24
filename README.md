# 00631L 戰術查詢器

這是一個可部署到 GitHub Pages 的 PWA（Progressive Web App）。

## 最簡單部署方式

1. 到 GitHub 建立一個新的公開 repository，例如：
   `00631L-strategy`
2. 把這個資料夾內的所有檔案上傳到 repository 根目錄：
   - index.html
   - manifest.webmanifest
   - sw.js
   - icon-180.png
   - icon-192.png
   - icon-512.png
   - .nojekyll
3. 進入 repository 的：
   **Settings → Pages**
4. 在 **Build and deployment**：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/(root)`
5. 按 Save。
6. 等 GitHub Pages 產生 HTTPS 網址。

## iPhone 加到主畫面

1. 用 Safari 開啟 GitHub Pages 網址。
2. 點 Safari 的「分享」。
3. 選「加入主畫面」。
4. 名稱可保留「00631L戰術」。
5. 點「加入」。

之後會像獨立 App 一樣從主畫面啟動。

## 資料儲存

交易資料存在該 iPhone Safari / PWA 的 localStorage。
如果清除 Safari 網站資料，資料也可能被清掉，因此建議偶爾使用 App 內的 JSON 匯出功能備份。
