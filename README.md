# Laravel 10 Inertia 外送美食到你家

消費者可一鍵快速點餐，而餐廳會同步接到訂單。當餐廳製作好食物後，並送餐至消費者指定地點，消費者付費後即完成該次訂餐，以利彼此互利互惠，創造雙贏。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 執行 __Artisan__ 指令的 __migrate__ 來執行所有未完成的遷移。
```sh
$ php artisan migrate
```
- 執行安裝 Vite 和 Laravel 擴充套件引用的依賴項目。
```sh
$ npm install
```
- 執行正式環境版本化資源管道並編譯。
```sh
$ npm run build
```
- 運行單元測試和功能測試。大多數的單元測試可能只專注於單一個方法，功能測試則可以測試大部分的程式碼，包含一些物件如何進行互動，甚至是完整的 HTTP 請求到一個 JSON 端點。
```sh
$ php artisan test
```
- 在瀏覽器中輸入已定義的路由 URL 來訪問，例如：http://127.0.0.1:8000。
- 你可以經由 `/register` 來進行註冊。
- 完成註冊後，可以經由 `/login` 來進行登入。

----

## 畫面截圖
![](https://i.imgur.com/a3erflC.png)
> 檢查程式碼是否如預期般執行

![](https://i.imgur.com/iG5djbG.jpg)
> 讓餐廳有機會做出強力曝光與提高能見度

![](https://i.imgur.com/2qOFZuG.png)
> 可以讓曾經的內用過客變成熟客，繼續延續餐廳美味的服務，讓消費者在忙碌之時，能在家享受美食，延續美味記憶
