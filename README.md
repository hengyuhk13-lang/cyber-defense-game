# 資安攻防戰：他不是一個人

手機直式互動式資安搜查遊戲。新版採用擬真手機桌面、App 視窗與虛構 AI 人物生活照片。

## GitHub Pages

1. 將本資料夾內的所有檔案與 `assets` 資料夾上傳到 GitHub Repository 根目錄。
2. 進入 **Settings → Pages**。
3. Source 選擇 **Deploy from a branch**。
4. Branch 選擇 **main**，資料夾選擇 **/ (root)**。
5. 儲存後等待約 1–3 分鐘。

## 更新現有版本

如果 Repository 已經有舊版，請同時取代：

- `index.html`
- `styles.css`
- `app.js`

並新增整個 `assets` 資料夾。缺少 `assets` 時，人物照片與桌布不會顯示。

## 檔案結構

```text
├── index.html
├── styles.css
├── app.js
└── assets
    ├── city-wallpaper.png
    ├── man-sheet.png
    └── support-sheet.png
```

不需要安裝套件或資料庫。
