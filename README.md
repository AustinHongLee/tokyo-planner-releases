# 東京隨行

在地圖上挑東京的美食、購物、景點與街區，安排每日時間及費用。

**[下載最新 Windows 可攜版](https://github.com/AustinHongLee/tokyo-planner-releases/releases/latest)**

在 Release 的 **Assets** 選 `TokyoPlanner-Windows-版本.zip`。不要下載 GitHub 自動產生的 `Source code` 壓縮檔。

## 第一次使用

1. 將 ZIP 完整解壓縮，保留整個資料夾。
2. 雙擊 `TokyoPlanner.exe` 或 `開啟東京隨行.bat`。
3. 瀏覽器會開啟本機網址；地圖需要網路。不需 GitHub 帳號、Node.js 或管理員權限。

不要直接開啟 HTML 當作完整地圖版。程式只在本機提供網頁，地圖由瀏覽器正常載入。

## 更新

1.5.2 起，正常啟動程式會在背景檢查 GitHub 正式版。從 **「⋯ → 版本與更新」** 先備份行程 JSON，再按 **「下載更新並重啟」**。

更新會驗證 SHA-256、保留原資料夾與連接埠設定，並備份舊程式；下載失敗仍可使用目前版本。它會自動檢查，安裝及重啟則由使用者按鈕決定。

**第一次請手動下載 1.5.2 以上正式版，包含使用過 1.4.x、1.5.0／1.5.1 的使用者。** 1.5.0／1.5.1 是已被取代的發版測試版。先匯出 JSON，從系統匣結束舊程式，再完整解壓新版。若換資料夾或網址，請匯入備份 JSON。草稿存在各自瀏覽器，不是多人即時同步；清除瀏覽器資料也會影響草稿。

## Release 資產

| 檔案 | 用途 |
| --- | --- |
| `TokyoPlanner-Windows-版本.zip` | 第一次下載、手動安裝 |
| `TokyoPlanner-update.zip` | 更新器使用的程式包 |
| `tokyo-planner-update.json` | 版本、大小及 SHA-256 更新清單 |
| `SHA256SUMS.txt` | 手動驗證下載檔案 |

此倉庫僅用於程式下載與更新。下載包含 exe、可檢視的網頁 JavaScript／地點資料及說明，不含私人開發倉庫、C# 原始碼、Git 紀錄、使用者草稿或登入權杖。程式目前未作 Windows Authenticode 簽章。

評分與價格資料有查閱日期及來源；它們是規劃參考，不是即時評分、價格或訂位保證。地圖與第三方資源的授權隨下載包提供。
