# 得來素 生產排程與成本管理系統

DerLife Production & Cost Management System — 內部生產排程、斤兩計算、成本管理工具。

## 功能

- 📅 當月每日工作排程表
- 📋 製作數量輸入（餛飩、水餃、粽子、油飯、G腿 等）
- 📊 各商品製作數量一覽表
- 📝 製作斤兩計算
- 🌾 乾貨需備總量
- 🎋 粽子 / 🍚 油飯 / 🍄 其他商品斤兩管理
- 💰 各商品成本分析
- ⚖️ 食材及調味料重量一覽表
- 🔐 權限管理（管理員專用）

## 登入方式

系統僅限授權人員使用。使用 **Google 帳號登入**，帳號需在白名單內才能存取。

- 管理員：jacky5453@gmail.com（預設，無法移除）
- 一般使用者：由管理員從系統內「🔐 權限管理」分頁新增

## 技術

- 單一 HTML（Vanilla JS + localStorage）
- Firebase Authentication（Google Provider）
- Firebase Firestore（白名單 collection：`production-schedule-whitelist`）
- 部署：GitHub Pages

## 線上網址

https://jacky5453-beep.github.io/derlife-schedule/
