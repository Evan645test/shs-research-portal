# 高中小論文研究與投稿入口

此資料夾是可直接部署的靜態網站。`index.html` 提供「得獎作品」與「繳交檢查」兩個分頁。所有作品連結均指向原始網站，本站不託管學生作品 PDF。

## 部署到 GitHub Pages

將本資料夾中的 `index.html` 與 `.nojekyll` 放在專用儲存庫的預設分支根目錄，然後在儲存庫的 Settings → Pages 中選擇 Deploy from a branch、預設分支、`/(root)`，儲存後等待 GitHub 提供網站網址。

GitHub 個人帳號的一般 Pages 網站可被網路上的任何人瀏覽；儲存庫設為私人並不會自動限制 Pages 網站的訪客。若需要僅限指定成員，須改用支援存取控制的託管服務，或具備 GitHub Enterprise Cloud 的組織專案網站。

## 檔案與更新

網站不依賴第三方 JavaScript 或 CSS 套件。更新索引時，請先更新專案內的資料，再重新產生或複製 `index.html`。請勿將 `得獎作品/`、`科展作品/` 中的 PDF 或其他私人資料加入公開儲存庫。
