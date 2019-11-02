# 我的餐廳清單 (Restaurant List)

使用 Node.js + Express 打造的餐廳清單網站，可閱讀餐廳詳細資訊，也可依照餐廳名稱與分類進行搜尋。

## 環境建置與需求 (Prerequisites)

* [Node.js](https://nodejs.org/)
* [Express ^4.17.1](https://expressjs.com)
* [Express-Handlebars ^3.1.0](https://www.npmjs.com/package/express-handlebars)

## 安裝與執行步驟 (Installing and execution)

1.開啟終端機(Terminal)，clone到本機專案位置:

```
git clone https://github.com/bluesmy/restaurant_list.git
```

2.切換至專案資料夾

```
cd restaurant_list
```

3.安裝套件
```
npm install  //自動安裝package.json內套件
```

4.啟動伺服器，並執行專案

```
npm run dev
```

終端顯示 `Express is listening on http://localhost:3000` 即成功啟動伺服器

```
Ctrl + C *2  //連按兩下Ctrl + C關閉伺服器
```

## 功能描述 (Features)

- 首頁展示所有餐廳照片、餐廳名稱、餐廳分類、餐廳評分
- 依照餐廳名稱及餐廳類別來搜尋餐廳
- 檢視餐廳詳細資訊包含類別、地址、電話、描述、圖片
  - 點選地址旁圖示可開啟新分頁查看Google Map上該地點資訊

## 專案畫面 (Screenshot)

![首頁](https://github.com/bluesmy/restaurant_list/blob/master/public/img/index.png)
![餐廳詳細資訊](https://github.com/bluesmy/restaurant_list/blob/master/public/img/restaurant_id.png)

## 專案使用工具 (Built With)

* [Visual Studio Code](https://code.visualstudio.com/) - The integrated development environment used
* [Express](https://expressjs.com) - The web framework used
* [Express-Handlebars](https://www.npmjs.com/package/express-handlebars) - The template engine used

## 專案開發人員 (Contributor)

* **Sheri Su** - [bluesmy](https://github.com/bluesmy)
