# BRONINJA TOP UP — Build Plan

## 1. Project Scaffolding
- [ ] Create folder structure (server, public, data, docs)
- [ ] package.json + install express, better-sqlite3, bcryptjs, jsonwebtoken, multer, cookie-parser, helmet, express-rate-limit, dotenv

## 2. Backend
- [ ] Database schema + seed 16 games, packages, admin user, site content
- [ ] Auth (JWT httpOnly cookie, bcrypt, rate limiting)
- [ ] Public API: games, packages, create order, order status lookup, payment methods, content
- [ ] Payment proof upload + admin verification
- [ ] Admin API: games CRUD, image upload, packages CRUD, orders + status, content, dashboard stats

## 3. Frontend
- [ ] Design system CSS (dark black/deep purple, gaming aesthetic, responsive)
- [ ] Logo + header/nav + hero
- [ ] Game grid (16 games) with images
- [ ] Top-up flow: package select, Player ID / Server ID, payment method, order summary, checkout
- [ ] Order confirmation + payment QR/instructions + proof upload
- [ ] Track order page
- [ ] Admin login + dashboard (games, packages, orders, content)

## 4. Assets
- [ ] Generate logo
- [ ] Source/generate game cover images
- [ ] QR placeholder images for ABA / ACLEDA / KHQR

## 5. Docs
- [ ] README with structure, install, run, deploy, admin guide, integration notes

## 6. Verification
- [ ] Run server, smoke-test all API endpoints
- [ ] Screenshot key pages, verify responsive
