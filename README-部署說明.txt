MotiPad 聯絡區跳轉修正

本更新以 2026-10-30 讀取的線上首頁為基準，只補上每張圖片的原始 width/height，讓瀏覽器在圖片載入前預留高度。保留九種語言原有文案、連結與版型。

部署：
1. 解壓縮 ZIP。
2. 開啟 GitHub 儲存庫 Ezio1983/motipad-website 的最外層。
3. Add file → Upload files。將本資料夾內的 index.html 和九個語言資料夾一起拖入，不要拖入包住它們的外層資料夾，也不必上傳本說明。
4. Commit changes。等待 Pages 部署完成。
5. 用無痕視窗開啟原支援網址，檢查是否穩定停在聯絡區。

App Store Connect 的支援 URL 不必修改，例如：
https://ezio1983.github.io/motipad-website/en/index.html#contact

驗證：十個線上首頁均讀取成功、每頁 contact 唯一、所有圖片有原始尺寸，且與線上版本的差異僅限 width/height。未完成瀏覽器實測，也未部署到 GitHub。
