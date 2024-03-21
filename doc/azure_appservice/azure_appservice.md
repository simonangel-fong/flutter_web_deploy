# Flutter Web Deployment - Azure

[Back](../../README.md)

- [Flutter Web Deployment - Azure](#flutter-web-deployment---azure)
  - [Create and Develope Flutter Web App](#create-and-develope-flutter-web-app)
  - [Add `Node.js` configuration files](#add-nodejs-configuration-files)

---

- ref:
  - https://www.showwcase.com/article/34739/flutter-web-app-to-azure-app-service-with-node-js

## Create and Develope Flutter Web App

---

## Add `Node.js` configuration files

- Dependences
  - `package.json`

```json
{
  "name": "counter-app-flutter",
  "version": "0.0.0",
  "private": true,
  "scripts": {
    "start": "node ./bin/www"
  },
  "dependencies": {
    "cookie-parser": "~1.4.4",
    "debug": "~2.6.9",
    "express": "~4.16.1",
    "http-errors": "~1.6.3",
    "jade": "~1.11.0",
    "morgan": "~1.9.1"
  }
}
```

---

- Node.js script
  - `app.js`

```js
var express = require("express");
var path = require("path");
var cookieParser = require("cookie-parser");
var logger = require("morgan");

var app = express();

app.use(logger("dev"));
app.use(express.json());
app.use(express.urlencoded({ extended: false }));
app.use(cookieParser());
app.use(express.static(path.join(__dirname, "build", "web")));

module.exports = app;
```

---
