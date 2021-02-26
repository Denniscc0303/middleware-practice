# Middleware 練習

練習使用middleware記錄request的時間戳記/方法/url/作用時間顯示在server log

## 專案畫面

![image](https://github.com/Denniscc0303/Images/blob/master/2-3%20A12%20%E8%80%81%E7%88%B8%E7%9A%84%E7%A7%81%E6%88%BF%E9%8C%A2_index_Dennis_20210205.JPG)

![image](https://github.com/Denniscc0303/Images/blob/master/2-3%20A12%20%E8%80%81%E7%88%B8%E7%9A%84%E7%A7%81%E6%88%BF%E9%8C%A2_new_20210205.JPG)

![image](https://github.com/Denniscc0303/Images/blob/master/2-3%20A12%20%E8%80%81%E7%88%B8%E7%9A%84%E7%A7%81%E6%88%BF%E9%8C%A2_edit_20210205.JPG)

![image](https://github.com/Denniscc0303/Images/blob/master/2-3%20A12%20%E8%80%81%E7%88%B8%E7%9A%84%E7%A7%81%E6%88%BF%E9%8C%A2_filter_Dennis_20210205.JPG)

## Features - 產品功能

1. 使用者可以在切換路由時在server上記錄request 時間戳記
2. 使用者可以在切換路由時在server上記錄request 方法
3. 使用者可以在切換路由時在server上記錄request 路由
4. 使用者可以在切換路由時在server上記錄request 收到請求與送出回應的時間差

## Environment SetUp - 環境建置

1. Node.js : v10.15.0
2. Express : v4.17.1
3. Nodemon : v2.0.7

## Installing - 專案安裝流程

1. 打開你的 terminal，Clone 此專案至本機電腦

```
git clone https://github.com/Denniscc0303/middleware-practice.git
```

2. 開啟終端機(Terminal)，進入存放此專案的資料夾

```
cd middleware-practice
```

3. 安裝 npm 套件

```
在 Terminal 輸入 npm install 指令
```

5. 啟動伺服器，執行 app.js 檔案

```
node app.js
```

6. 當 terminal 出現以下字樣，表示伺服器已啟動並成功連結

```
App running on port 3000

```

現在，你可開啟任一瀏覽器瀏覽器輸入 [http://localhost:3000](http://localhost:3000) 開始使用middleware-practice。

## Contributor - 專案開發人員

> [Dennis Chen](https://github.com/Denniscc0303)