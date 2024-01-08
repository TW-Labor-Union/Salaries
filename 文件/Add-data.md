# 新增流程

1. 設定這個資料夾專屬的 Git 帳號和信箱 (只有在第一次 commit 時候，才需要設定)
2. 切換 GitHub 使用者帳號
3. 發 PR

以下針對每個步驟進行說明

## 設定這個資料夾專屬的 Git 帳號和信箱

只有在第一次 commit 時候，才需要設定

打開終端機 (CMD，Command Prompt)，輸入 (`$ ` 不用輸入，那表示這在終端機環境下)

```
$ git config user.name "Git 使用者名稱"
$ git config user.email "Git 電子信箱"
```

## 切換 GitHub 使用者帳號

詳見 [切換 GitHub 帳號](./切換GitHub帳號.md)

## 發 PR

將本地分支 (local branch)，使用 `git push` 推到 GitHub 之後，發起 `Pull Request`
