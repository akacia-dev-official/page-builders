# Page Builder Library

## Introduction｜介紹

Page Builder Library 是一個基於 Laravel 的沙盒平台，用於測試各種前端區塊編輯器（Block Editor），以評估哪一種方案最符合我們的需求。

**EN**
Page Builder Library is a sandbox platform built with Laravel to experiment with different front-end block editors and evaluate which solution best fits our needs.

---

## Requirements｜需求

* Node.js
* PHP（需支援 Laravel）
* Composer

---

## Installation & Running｜安裝與執行

1. 安裝 PHP 相依套件：

   ```bash
   composer install
   ```

2. 安裝 Node 相依套件：

   ```bash
   npm install
   ```

3. 設定環境：

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. 啟動開發環境：

   ```bash
   npm run dev
   php artisan serve
   ```

5. 開啟瀏覽器：

   ```
   http://127.0.0.1:8000
   ```

---

**EN**

1. Install PHP dependencies:

   ```bash
   composer install
   ```

2. Install Node dependencies:

   ```bash
   npm install
   ```

3. Setup environment:

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. Run development servers:

   ```bash
   npm run dev
   php artisan serve
   ```

5. Open in browser:

   ```
   http://127.0.0.1:8000
   ```

---

## Notes｜備註

* 此專案為實驗性質，主要用於內部評估。
* 前端實作可能會頻繁變動。

**EN**

* This project is experimental and intended for internal evaluation.
* Front-end implementations may change frequently.

---
