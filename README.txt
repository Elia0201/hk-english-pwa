香港求職英語發音練習室｜手機 PWA 版

檔案
- index.html：學習網站
- manifest.webmanifest、sw.js：安裝資訊與離線快取
- icon-192.png、icon-512.png、apple-touch-icon.png：應用程式圖示

安裝／使用
1. 將整個資料夾部署到 HTTPS 網站（例如 GitHub Pages、Cloudflare Pages 或自己的網站）。PWA 安裝與離線快取需要 HTTPS；localhost 可供測試。
2. Android：用 Chrome 開啟網站，點頁面上的「安裝／加入主畫面」，或使用瀏覽器選單。
3. iPhone/iPad：用 Safari 開啟網站，點「分享」→「加入主畫面」。
4. 首次連線載入後，網站頁面與學習資料可離線開啟。瀏覽器朗讀使用裝置內建語音；語音識別需瀏覽器支援，部分裝置／瀏覽器需要網絡連線，iOS 支援因版本而異。

資料保留
- 學習進度仍使用原有 localStorage 鍵 hkMediaEnglishLearnedV1。
- 間隔複習仍使用原有 localStorage 鍵 hkMediaEnglishReviewV1。
- 本版本不會主動清除或重設這些資料。瀏覽器會按網站來源隔離資料；如果原頁面和 PWA 使用不同網址或來源，舊來源的 localStorage 不會自動出現在新來源。保留原頁面即可保留舊資料。

麥克風權限
請在瀏覽器允許麥克風。語音識別結果是文字匹配提示，不代表專業音素評分。