# BRONINJA TOP UP — Build Plan

## 1. Project Scaffolding
- [x] Create folder structure (server, public, data, docs)
- [x] package.json + install express, better-sqlite3, bcryptjs, jsonwebtoken, multer, cookie-parser, helmet, express-rate-limit, dotenv

## 2. Backend
- [x] Database schema + seed 16 games, packages, admin user, site content
- [x] Auth (JWT httpOnly cookie, bcrypt, rate limiting)
- [x] Public API: games, packages, create order, order status lookup, payment methods, content
- [x] Payment proof upload + admin verification
- [x] Admin API: games CRUD, image upload, packages CRUD, orders + status, content, dashboard stats

## 3. Frontend
- [x] Design system CSS (dark black/deep purple, gaming aesthetic, responsive)
- [x] Logo + header/nav + hero
- [x] Game grid (16 games) with images
- [x] Top-up flow: package select, Player ID / Server ID, payment method, order summary, checkout
- [x] Order confirmation + payment QR/instructions + proof upload
- [x] Track order page
- [x] Admin login + dashboard (games, packages, orders, content)

## 4. Assets
- [x] Generate logo
- [x] Source/generate game cover images
- [x] QR placeholder images for ABA / ACLEDA / KHQR

## 5. Docs
- [x] README with structure, install, run, deploy, admin guide, integration notes

## 6. Verification
- [x] Run server, smoke-test all API endpoints
- [x] Screenshot key pages, verify responsive
