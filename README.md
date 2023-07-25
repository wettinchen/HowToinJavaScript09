## How To in JavaScript 09
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 How To in JavaScript 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6O6B63J0GYHeNDzBMKE7RSD

### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## How To in JavaScript 09
## Serverless Functions in JavaScript | Build Netlify Serverless Functions with JavaScript
   Quick Concept outline
   中文摘要說明與重點提問

###  1. Intro 
        教學影片開頭和 netlify 介紹
        https://www.netlify.com/products/functions/

###  2. Structure HTML
        (1)新增資料夾 dist
        (2)新增 index.html
        (3)修改 title 元素，文字為 Serveless Tutorial
        (4)新增 h1 元素

###  3. Add CSS
        (1)新增資料夾 css
        (2)新增 main.css
        (3)設置 CSS 重置
        (4)設置 html, body, h1, media query 樣式
        (5)新增資料夾 img
        (6)新增 city.png
        (7)設定圖片覆蓋 html 頁面
        (8)連接 css 至 html

###  4. Add JavaScript
        (1)新增資料夾 js
        (2)新增 main.js
        (3)連接 JavaScript 至 html
        (4)宣告 getRandomDadJoke 自定義函數
        (5)宣告 displayJoke 自定義函數
        (6)宣告 h1，文字內容為 joke
        (7)宣告 refreshJoke 自定義函數
        (8)宣告 joke，使用 displayJoke，參數為 joke
        (9)使用 setInterval，在 3000 毫秒後，使用 refreshJoke
        (10)立刻載入 refreshJoke

###  5. Add a CSS Animation
        (1)設定 css 動畫
        (2) h1 加入 class 為 .fade-in

###  6. JS Fetch with Async / Await
        (1)宣告 url
        (2)宣告 jokeStream
        (3)宣告 jsonJoke
        (4)宣告 joke
        (5)回傳結果

###  7. Quick Refactor
        修改為 setInterval(refreshJoke(), 10000);

###  8. Create a git repo and push to GitHub
        (1)在 TERMINAL 輸入 git init
        (2)在 TERMINAL 輸入 git add .
        (3)在 TERMINAL 輸入 git commit -m "first commit"
        (4)前往 GitHub 點擊 Your repositories
        (5)命名 repositories名稱 完成後 點擊 Create repositories
        (6)在 TERMINAL 輸入 
        git remote add origin名稱 https://github.com/使用者名稱/repositories名稱.git
        (7)在 TERMINAL 輸入 git branch -M main
        (8)在 TERMINAL 輸入 git push -u origin名稱 main

###  9. Link your project to Netlify with Continuous Deployment
        點擊 GitHub，選擇特定的 repositories

### 10. Install NodeJS
        前往 https://nodejs.org/zh-tw 選擇長期維護版

### 11. Install Netlify CLI
        (1)在 TERMINAL 輸入 npm netlify-cli -g
        (2)新增資料夾 netlify.tomi

### 12. Initialize npm

### 13. Create a .gitignore file

### 14. Install node-fetch package dependency

### 15. Create the serverless functions folder

### 16. Create a serverless function

### 17. Modify the fetch function in our main.js

### 18. Use Netlify CLI to test our serverless function

### 19. A more practical serverless example

### 20. Where to add environment variables in Netlify