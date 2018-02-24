# 麻煩

概念是這樣：安裝 gitbook-cli 程序後，是用來「建置」或「編譯」，使用 GitBook 官方網站就等於把這些背後程序由其伺服器來執行。但本地執行遇到 Node 套件或環境的問題頗多，轉製 ePub 其實也要靠 Calibre 背後的轉製程序。

- 使用 gitbook build 可以建立網頁電子書的目錄，但無法使用 gitbook serve 來啟動 localhost 4000 port 的預覽，不知是否與 Mac 環境設置了 Valet（Nginx）有關？
- 直接開啟目錄，雙擊 `_book` 建置目錄下的 index.html，可以直接以瀏覽器檢視。確實就是個「靜態網站」，甚至也能擺放到 GitHub Pages。
- 安裝 autocover plugin 前必須先裝 canvas 套件，但即使安裝了、建置過程中沒出錯，目錄下還是不會出現自動生成的封面。