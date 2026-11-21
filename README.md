# 提醒喵 RemindCat 官網

提醒喵（RemindCat）App 的介紹網頁，用 GitHub Pages 公開，網址 https://remindcat.pocketjoystudio.com/ （網域在 Cloudflare，pocketjoystudio.com 是工作室共用網域，這裡只用 remindcat 子網域；CNAME 檔不要刪）。這個 repo 只有網頁檔案（HTML、CSS、圖片），沒有 App 或伺服器的程式。

| 網址 | 語言 |
|---|---|
| `/` | 繁體中文（第一次來會照瀏覽器語言轉到日文、泰文或英文版） |
| `/en/` | English |
| `/ja/` | 日本語 |
| `/th/` | ไทย |

- 樣式都在 `assets/style.css`；沒有外部字型、沒有追蹤碼、不需要 build。
- 隱私權政策、使用條款連到提醒喵伺服器上的頁面（`/privacy`、`/terms`）。
- **App 上架後**：每個 `index.html` 裡兩個商店按鈕的 `class="store soon"` 改成 `class="store"`、拿掉 `aria-disabled="true"` 和 `<span class="tag">…</span>`，按鈕就能點了；「即將上架」那句（`end_sub`）也要改。
- 數字（價格、次數、人數）要和 App 一致：PRO NT$99／月、NT$790／年；AI 每月 300 次；免費版 10 筆；家人共享 2 人；團體版最多 10 人、旅行團票 NT$290（30 天 200 題、30 則）、年訂 NT$1,490（每月 100 題、15 則）、加購 NT$190（100 題）。App 改了，這裡要一起改。
