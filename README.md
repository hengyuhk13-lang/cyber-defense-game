# 資安攻防戰：他不是一個人

一款手機直式的互動式資安搜查遊戲。玩家扮演陳安晴，查看 LINE、Instagram、Gmail、檔案與備忘錄，從資料中找出網路男友「周宇辰」的真實身分。

## 直接預覽

下載專案後，直接用瀏覽器開啟 `index.html` 即可。

## 上傳到 GitHub

1. 在 GitHub 建立新的 Repository。
2. 將這個資料夾內的所有檔案上傳到 Repository 根目錄。
3. 確認預設分支名稱為 `main`。
4. 打開 Repository 的 **Settings → Pages**。
5. 在 **Build and deployment** 的 Source 選擇 **GitHub Actions**。
6. 等待上方 **Actions** 頁面的部署流程完成。
7. 回到 **Settings → Pages**，即可取得公開遊戲網址。

網站會在每次推送到 `main` 分支後自動更新。

## 專案檔案

- `index.html`：網站入口與基本資訊
- `styles.css`：畫面與手機版樣式
- `app.js`：遊戲內容、題目與互動邏輯
- `.github/workflows/pages.yml`：GitHub Pages 自動部署

## 修改內容

- 修改對話、題目或答案：編輯 `app.js`
- 修改顏色、版面或動畫：編輯 `styles.css`
- 修改網頁標題與描述：編輯 `index.html`

本專案不需要安裝套件，也不需要後端資料庫。
