# Smylte

**Save social media posts, library & downloader**

把有用的社交平台貼文留在自己的裝置，需要時再搜尋找回。搜尋已儲存的文字及圖片內已辨識的文字，下載支援的相片和影片，或製作分享圖片。

**[從 Chrome Web Store 安裝](https://chromewebstore.google.com/detail/smylte-save-social-media/eebefbknmfpjmhggmcapmljjilmkoebg)** · [產品網站](https://yaka310.com/projects/post-library/) · [使用指南](https://yaka310.com/projects/post-library/guides/) · [English](README.md)

這個公開 repository 只提供**產品資料、更新及使用支援**。Smylte 是閉源軟件，這裡不提供應用程式原始碼或安裝套件。

## 主要功能

- 把支援的貼文存入本機收藏庫，離線查看已成功儲存的內容。
- 搜尋正文、已儲存且支援的回覆及圖片內已辨識的文字；選用的「用意思搜尋」亦在本機執行。
- 使用分類、標籤、篩選、相關貼文及選用提醒整理收藏。
- 只下載支援的相片或影片，不新增收藏記錄。
- 將已儲存的貼文及你明確選取的文字留言製成最多 10 張 PNG 分享圖片。
- 使用完整備份及還原，保留或搬移收藏庫及可用的媒體。

**原帖刪除後，成功儲存的內容仍可查看，前提是你保留本機副本。** 只有連結或縮圖不代表已下載影片；重要內容請另作備份。

## 功能截圖

以下截圖來自已上架的 **v0.55.15**，貼文、作者及圖片全部是模擬內容，沒有使用任何真實收藏。下載示範使用本機測試回應，不代表某篇真實貼文一定能夠下載。

**集中查看已儲存的貼文**

![Smylte 收藏庫，使用模擬貼文](assets/screenshots/library-v0.55.15.png)

**用關鍵字找回已儲存的內容**

![Smylte 關鍵字搜尋，使用模擬內容](assets/screenshots/search-v0.55.15.png)

**只下載媒體，不新增收藏記錄**

![Smylte 媒體下載流程，使用模擬本機回應](assets/screenshots/downloads-v0.55.15.png)

[了解這些示範的範圍](SCREENSHOTS.md)

## 支援來源

| 平台 | 支援範圍 |
| --- | --- |
| Threads | 收藏清單、指定公開帳號中可載入的原創貼文，以及支援的單一貼文或回覆連結。 |
| Instagram | 收藏清單、指定公開帳號，以及支援的單一貼文或 Reel 連結。 |
| Facebook | 收藏清單中當次已載入且受支援的項目，以及支援的單一文字／相片貼文、多圖貼文、直接相片和 Reel。 |
| X | 書籤、喜歡的貼文記錄，以及支援的單一貼文連結；不複製引用貼文媒體或回覆內文。 |
| Patreon（beta） | 你有權讀取的單一貼文、創作者頁面及支援的收藏集。 |
| Pinterest | 單一 Pin 中支援的相片或影片；**只提供下載，不會把 Pin 加入收藏庫。** |

亦可加入電腦上的圖片。實際支援取決於你的存取權限及網站當次載入的內容。工具不會繞過登入、私人內容或存取限制，亦不保證取得所有影片、留言或完整帳號歷史。詳情見[六個平台的指南](README.md#supported-sources)及[功能限制](SUPPORT.md#limits-to-keep-in-mind)。

## 開始使用

1. 從 Chrome Web Store 安裝 Smylte，開啟收藏庫。
2. 使用 **Add posts / Download**，選擇來源，或貼上支援的單一貼文連結，再選擇儲存或下載。
3. 如操作需要登入，請在同一個瀏覽器設定檔登入相應平台。
4. 查看完成狀態；部分完成、取消及未確認的結果，不等於下載完成。

介面支援英文、繁體中文、簡體中文、俄文（Testing）、日文及韓文。

## 私隱及 AI

收藏庫儲存、圖片文字辨識及意思搜尋在本機處理。不需要另開 Smylte 帳號，亦沒有開發者分析追蹤或轉送收藏內容的伺服器。

AI 分類屬選用功能。開啟後，相關的已選文字、作者帳號、已辨識圖片文字及分類名稱，會使用你自己的 API 金鑰直接傳送至 Google Gemini；供應商可能設有使用限制或收費。不使用 AI 金鑰，仍可儲存內容、使用關鍵字搜尋及手動整理。詳見[私隱說明](PRIVACY.md)。

## 更新及支援

- 2026 年 10 月 24 日核對的商店版本為 **v0.55.15**；目前供應版本請以 [Chrome Web Store](https://chromewebstore.google.com/detail/smylte-save-social-media/eebefbknmfpjmhggmcapmljjilmkoebg) 為準。
- **v0.55.16 仍在開發中**，與已上架版本分開列於[更新記錄](UPDATES.md)。
- [常見問題及疑難排解](SUPPORT.md) · [回報問題或建議功能](https://github.com/bu56co-del/smylte/issues/new/choose) · [網站更新](https://yaka310.com/updates/)

前稱 Post Library。這是非官方工具，與支援的平台沒有隸屬或背書關係。請只儲存或下載你有權保留和使用的內容。
