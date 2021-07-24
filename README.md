# 中介軟體實作練習 Middleware Practice
以 Express 所建立的中介軟體實作練習。

## 功能 Features
當伺服器收到任何來自瀏覽器的請求時，就將其顯示於伺服器端並包括：
- 請求時間戳記 (time-stamps) - 以當地時間 (台北) 顯示
- 請求的 HTTP 方法
- URL
- 請求到回覆所花費的時間

## 環境 Environment
- Node.js
- Nodemon

## 安裝 Installation

1. 取得專案至本地
```
git clone https://github.com/wilson614/middleware-practice
```
2. 進入專案目錄
```
cd middleware-practice
```
3. 安裝套件
```
npm install
```
4. 啟動專案
```
npm run dev
```
5. 出現以下訊息後，即可在 http://localhost:3000 開始使用
```
App is running on http://localhost:3000
```
