# 待辦清單 Web App

![GitHub Copilot 實戰工作坊完成徽章](https://img.shields.io/badge/GitHub_Copilot_%E5%AF%A6%E6%88%B0%E5%B7%A5%E4%BD%9C%E5%9D%8A-%E5%B7%B2%E5%AE%8C%E6%88%90-1F883D?style=for-the-badge&logo=githubcopilot&logoColor=white)

這是一個在 GitHub Copilot 實戰工作坊中完成的待辦清單 Web App。專案從基本的待辦事項管理開始，逐步加入深色模式、篩選功能、MCP 設定與可重複執行的 issue 修正流程，作為練習 AI 輔助開發與 Git 工作流程的成果。

## 線上展示

[GitHub Pages](https://<你的帳號>.github.io/<你的repo名稱>/)

> 請將上方網址替換成實際的 GitHub Pages 網址。

## 功能

- 新增待辦事項。
- 勾選待辦事項為已完成或未完成。
- 刪除單筆待辦事項。
- 顯示整體未完成待辦數量。
- 使用「全部」、「未完成」與「已完成」篩選清單。
- 篩選結果為空時顯示對應提示文字。
- 在淺色與深色模式之間切換。
- 使用者未手動選擇主題時，跟隨作業系統的 `prefers-color-scheme` 設定。
- 使用 `localStorage` 保存待辦資料與主題偏好。
- 以 `aria-label`、`aria-pressed` 與原生按鈕操作支援基本鍵盤與輔助科技操作。

## 技術

- 使用純 HTML、CSS 與原生 JavaScript。
- 不使用前端框架、第三方套件或外部 CDN。
- 使用 CSS 變數管理淺色與深色主題配色。
- 使用瀏覽器 `localStorage` 保存待辦資料與主題偏好。
- 使用 `prefers-color-scheme` 偵測作業系統的深淺色偏好。

## 開發方式

- 使用 GitHub Copilot Agent Mode，依照逐步需求建立與擴充待辦清單 App。
- 透過 MCP 連接 Microsoft Learn 與 GitHub，查詢官方文件並讀取 repository issue。
- 使用 `.github/copilot-instructions.md` 定義專案技術限制、程式風格與協作規範。
- 使用 `.github/prompts/fix-issue.prompt.md` 定義從讀取 issue、等待確認、建立分支、修改、驗證到建立 Pull Request 的 agentic workflow。
- 使用 Git 分支、commit、rebase 與 push 管理開發過程。

## 我學到什麼

- 如何用 Agent Mode 將一段需求拆成可執行的開發步驟。
- 如何使用 CSS 變數與 `prefers-color-scheme` 實作可切換的主題。
- 如何透過 MCP 讓 AI 查詢官方文件與 repository 的 issue 資訊。
- 如何用專案 instructions 與 prompt 固定 AI 的協作流程與修改範圍。
- 如何使用 Git 分支、rebase 與 Pull Request 管理功能修正。
