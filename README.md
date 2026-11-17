# GitHub 社群協作工作坊

2026 年 11 月 18 日北科程式設計研究社社課練習專案。

全班共同維護一份社團新手指南網站，練習認領 Issue、提出 Pull Request、互相 Review 與同步成果。

## 開始參與

1. 閱讀 Issues 清單，挑選一個待認領任務。
2. 在 Issue 留言「我想認領這個任務」，由講師確認認領人。
3. Fork 本儲存庫，Clone 自己的 Fork，並為任務建立功能分支。
4. 修改 `index.html`，用瀏覽器開啟檔案並依 Issue 的完成條件驗證。
5. 提交並推送功能分支，向本儲存庫的 `main` 提出 PR。
6. PR 說明包含修改原因、內容與驗證結果，並使用 `Closes #實際編號` 連結認領的 Issue。
7. 檢查另一位同學的 PR，作者回應後由講師合併。
8. 從上游同步 `main`，開啟網站確認已合併的成果。

## 本機操作

```sh
git clone https://github.com/YOUR_ACCOUNT/github-community-261118.git
cd github-community-261118
git remote add upstream https://github.com/NTUT-NPC/github-community-261118.git
git switch -c YOUR_BRANCH
```

將 `YOUR_ACCOUNT` 換成自己的 GitHub 帳號，`YOUR_BRANCH` 換成描述任務的分支名稱。網站採單一 HTML，直接以瀏覽器開啟 `index.html` 即可預覽。

## 協作約定

- 每個 PR 聚焦一個已認領的任務，保留其他人的內容。
- 送出 PR 前，依 Issue 的完成條件實際驗證。
- Review 說明觀察、影響與建議，或記錄具體測試結果。
- 使用 AI 協助時，在 PR 揭露使用方式，由提交者確認來源、理解修改並完成驗證。
- 僅放適合公開的資料，分享錯誤訊息前先遮掉密碼與 Token。
- `main` 由講師整合，全班在功能分支上開發。

## 範本內容

- `#intro` 社團介紹
- `#resources` 學習資源
- `#faq` 常見問題
- `#join` 參與準備

範本保留課堂任務所需的待改善內容，例如 GitHub 官方文件連結。實際修改範圍與完成條件以各個 Issue 為準。

## 授權

MIT License，詳見 `LICENSE`。
