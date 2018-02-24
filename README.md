---
description: This is a short description of my page
---

# Introduction

有點摸不清楚 Gitbook Editor for Mac 的正確使用流程。

1. 先安裝 gitbook-cli npm 套件。
2. 建立書籍專案目錄後，使用 `gitbook init` 初始化，但這指令就只建立了 README 與 SUMMARY 兩個檔案，連 gitignore 都沒有，似乎有些多餘。
3. 使用 Gitbook Editor 開啟該目錄，確實可以編輯目錄內的文件，但左上方始終出現 **Untitled** 字樣很怪。

## GitHub

搭配 GitBook Editor 與 GitHub 的使用，在遠端倉儲設置時只能使用 HTTPS 模式，認證時的密碼則必須先到 GitHub 新增一個 Access Token 當作密碼（記得設置時要給正確的倉儲管理權限），不能直接以 2FA 模式驗證。

## Gitbook CLI 指令

* gitbook init
* gitbook build \[book\] \[output\]
* gitbook serve \[book\] \[output\]
* gitbook install \[book\]
* gitbook parse \[book\]
* gitbook pdf \[book\] \[output\]
* gitbook epub \[book\] \[output\]
* gitbook mobi \[book\] \[output\]

具體的說，所有內容編輯都是使用編輯器（Gitbook Editor 或 Sublime Text），Gitbook 指令都是編譯與開發流程。

