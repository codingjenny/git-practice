# git-practice

這是一個練習 GitHub Pull Request 的範例專案。

## 練習步驟

1. **Fork 或 Clone 專案**  
   請先 fork 本專案到你的 GitHub 帳號或以 git clone 的方式下載到本地。

2. **建立新分支**  
   在本地建立一個新的分支，例如 `add-hsinchu-food`。

3. **同步原始專案內容（可選，如果已經 fork 且原專案有新內容）**  
   ```bash
   git remote add upstream https://github.com/codingjenny/git-practice.git
   git pull upstream main
   ```
   如果你的專案落後於主 repo，可以這樣將原始專案最新進度同步到你本地的 main 分支，避免合併衝突。

4. **編輯美食資料**  
   找到專案中的 `hsinchu-food.txt` 檔案，新增、刪除或修改新竹美食相關內容。

5. **提交並推送更改**  
   把你在分支上的改動 commit 並推送到你的 GitHub repository。

6. **發起 Pull Request (PR)**  
   回到 GitHub 頁面，對主分支（main）提出一個 Pull Request，標題請簡述你新增或修改的美食資訊。可在 PR 描述中補充推薦原因或個人心得。

7. **等待 Review 或合併**  
   請等待 repo maintainer review，你也可以主動請 maintainer 協助審查。

