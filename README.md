# LUNÉ：GitHub Pages 版本

1. 將本壓縮檔解壓縮，把 index.html、contact.html、assets 資料夾及 .nojekyll 上傳到你的 GitHub 儲存庫根目錄。
2. 儲存庫 Settings → Pages → Deploy from a branch，選擇 main 與 /(root)，按 Save。
3. 用 GitHub Pages 產生的 HTTPS 網址開啟網站。

index.html 是完整網站，contact.html 是獨立聯絡表單。照片已包含在 assets，請保持資料夾名稱。

## 聯絡表單
表單已接上你提供的 https://formspree.io/f/xnppzozg 。
客戶填寫姓名、電話、Email、聯絡內容後，資料送至這個 Formspree 表單。
GitHub Pages 提供網頁，實際信件通知由 Formspree 處理。
請在 Formspree 後台確認收件 Email 已驗證、Email Notifications 已啟用，且方案仍有可用額度。
程式不需要 Gmail 密碼或公開 API 密鑰。
成功提示代表 Formspree 接受提交，不保證信件已送達收件匣。
JavaScript 寄送失敗會保留輸入內容；可選「改用寄送頁面」以標準 POST 完成服務端確認。

已檢查欄位與程式流程；沒有自動向你的信箱發送測試訊息。
