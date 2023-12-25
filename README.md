# 短網址產生器 url-shortener

---

## 介紹

此專案為 ALPHA Camp Dev C3 M6 指標作業 所製作。
運用 Node.js 與 Express 建立本機伺服器，在伺服器運行期間可執行短網址的產生與重新導向。

---

## 功能

* 依輸入網址產生對應的短網址，若輸入已經轉換過的網址則會得到與第一次生成時一樣的短網址。
並且網址結尾是否有斜線 / 皆會視為同樣網址。例如： 第一次輸入 https://github.com/ 並轉換成短網址，之後輸入 https://github.com 會得到一樣的結果。
* 以 json 檔儲存網址資料。
* 將短網址導向原址。
* 短網址之 id 無效時，導回短網址生成器首頁 http://localhost:3000
* 複製按鈕可一鍵複製轉換後的短網址。
* 點擊標題「URL SHORTENER」可返回首頁。

---

## 啟動專案 

把專案複製到你的電腦上:

` $ git clone https://github.com/Tancred1014/short-url `

導入專案資料夾:

` $ cd /short-url `

安裝npm:

` $ npm install `

啟動專案:

` $ npm run start `

成功時，終端機會顯示訊息，請打開瀏覽器進入網址:

` Listening :  http://localhost:3000 `

結束:

> ctrl + c

## 開發工具
* Git v2.41.0
* npm v9.5.0
* nvm 1.11.1
* node v18.15.0
* nodemon v2.0.22
* express v4.18.2
* express-handlebars v7.0.7
* Bootstrap 5.2.1
