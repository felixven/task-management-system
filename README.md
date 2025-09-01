# 任務管理系統Task-Management-System

## 系統介紹：
- 本專案「任務管理系統（Task Management System）」，由練習基礎語法的 Todo Management System 延伸而來，後續嘗試將工作中接觸到的技術與研究概念融入系統設計，進一步擴充功能與介面。
- 系統採用前後端分離架構開發：
   - 前端：以 React.js 開發使用者介面
   - 後端：以 Spring Boot + MySQL 建立 API 服務

## 功能介紹：
- 使用者管理：註冊 / 登入 / JWT Token 驗證，支援角色權限分流。
- 任務管理：
   - 任務建立、更新、刪除、審核（Admin）
   - 子任務建立、更新、刪除（Admin）
   - 任務和子任務參與、完成、查詢（所有User）
- 排行榜：提供「協作榜」與「完成者榜」，可展開查看明細。

## 系統展示：
- 前端部署於 Vercel，後端以 Docker 容器化部署於 Render，並使用 MySQL 資料庫。
- Demo網址：平台架設於[Vercel](https://todo-ms-chi.vercel.app/)
- 測試帳號/密碼：
  登入頁面輸入 **帳號或電郵** 和密碼 即可

| Role   | 帳號   | 電郵                     |密碼      |
|--------|-------|-------------------------|----------|
| Admin  | admin | admin@example.com       |admin1234 |
| User   |  user | user@example.com        |user1234  |

## 使用技術：
- 前端：Vite / React.js / Tailwind.css
- 後端：Java Spring Boot / MySQL

## 前後端完整原始碼：
- 前端：[Front-End Repository](https://github.com/felixven/todo-frontend.git)
- 後端：[Back-End Repository](https://github.com/felixven/todo-backend.git)
