<!-- Header Section -->
<h1 align="center">👋 Hi, I'm <span style="color:#4F46E5">Euphoria</span> — Full-Stack Developer</h1>

<p align="center">Building scalable, production-grade systems across backend, frontend, and mobile — from CRM platforms and telephony integrations to e-commerce and education tech.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Role-Backend%20Focused%20Full--Stack-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-Expert-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-Expert-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Location-Uzbekistan-ffdd00?style=for-the-badge"/>
</p>

---

## 🧑‍💻 About Me

I am a **backend-focused full-stack developer** who builds real, production-deployed systems. My core strength is **server-side architecture** — designing clean, layered backends with Python (**FastAPI, Django, DRF**) and Node.js/TypeScript (**NestJS**), backed by PostgreSQL, MySQL, and Redis.

I work across the entire stack: from **REST APIs, database design, queue systems, and authentication flows** on the backend, to **Next.js dashboards and Flutter mobile apps** on the frontend. I've shipped CRM platforms, e-commerce systems, LMS backends, Telegram bots, and **VoIP/telephony integrations** using Asterisk/FreePBX — including in-browser WebRTC calling and real-time call event handling.

I care about **production hardening, Docker-based deployments, reverse proxy configuration, and getting systems to run reliably on real servers** — not just code that works locally.

---

## 🚀 Real Production Projects

### 🔹 **Euphoria CRM — Recruitment Platform**
A full-scale CRM for a recruitment company.
- **Stack:** NestJS + Next.js + PostgreSQL + Redis + Telegraf bot
- Blacklist system with status badges, repeat-candidate detection, and a stats dashboard
- RBAC with CASL, Redis `permission_changed` flag forcing re-auth on permission edits
- Axios refresh-token logic, bfcache navigation fixes, schedule/interview flow
- **Telephony integration:** WebRTC in-browser calling (SIP.js), Asterisk AMI event handling, Socket.io real-time notifications, MinIO recording storage
- Docker Compose (base + prod overlay via Makefile), multi-stage Dockerfiles, nginx reverse proxy
- Deployed to a corporate server (`crm.corp.euphoriagroup.uz`) with full production hardening

### 🔹 **PBX Analytics Dashboard**
A FastAPI analytics platform for FreePBX/Asterisk CDR data.
- Layered architecture: repository → service → endpoint
- MySQL access over SSH tunnel
- Excel export via pandas/openpyxl
- SQL patterns reverse-engineered from the Asternic CDR module

### 🔹 **e-elements.uz — Dietary Supplements E-Commerce**
- **Stack:** NestJS + PostgreSQL + Redis
- **Payme** integration (all six JSON-RPC methods verified in sandbox) + **Click** integration
- SMS authentication flow (send-sms → verify-phone → complete-register) with Redis rate limiting
- Order state machine with **BullMQ** delayed expiry jobs

### 🔹 **Audio Call Recording & LLM Analysis CRM**
- **Stack:** NestJS + Next.js, dual-database setup, raw SQL via `pg`
- Recording storage, transcription, and LLM-based call analysis
- Redis caching with TTL logic, orders module refactor driven by status codes

### 🔹 **TOMU.uz — Online Education Platform**
- Admin panel: Next.js 15, MUI Joy UI, TypeScript, Zustand, React Query
- Modules: Grammar, Homework, Tariffs, Groups, Users, Orders, Feedback, Notifications, payments
- Firebase FCM notifications, role-based sidebar filtering

### 🔹 **m-edu LMS — Backend + Mobile**
- `m-edu-backend` (NestJS LMS) + Flutter admin & student apps
- **Flutter stack:** Riverpod, Dio, go_router, freezed, BLoC (clean architecture)
- Apple-style design, light/dark mode

### 🔹 **VPS Deployments & Infrastructure**
- Deployed `corporative-bina.uz` to a Contabo VPS (Ubuntu 24.04)
- Server hardening, Nginx reverse proxy, PM2, SSL via Certbot, TypeORM migrations
- Diagnosed and fixed a Docker IPv6 DNS resolution bug via `/etc/docker/daemon.json`

---

## 🛠️ Technologies & Tools

### 🐍 **Backend — Python**
- FastAPI, Django, Django REST Framework
- SQLAlchemy, pandas, openpyxl

### 🟢 **Backend — Node.js / TypeScript**
- NestJS
- BullMQ (job queues), CASL (RBAC)
- Raw SQL (`pg`), TypeORM

### ☕ **Kotlin & Swift**
- Kotlin (Android / native)
- Swift (iOS / native)

### 📱 **Mobile — Flutter**
- Riverpod, BLoC
- Dio, go_router, freezed
- Clean architecture, light/dark theming

### 🎨 **Frontend**
- Next.js, React
- TypeScript, Zustand, React Query
- MUI Joy UI, TailwindCSS

### 🗄️ **Databases & Caching**
- PostgreSQL, MySQL
- Redis (caching, rate limiting, pub/sub)

### 📞 **Telephony / VoIP**
- Asterisk, FreePBX
- AMI (event handling), CDR analytics
- SIP.js, WebRTC

### 🤖 **Bots & Integrations**
- Telegraf / Telegram Bot API
- Payme, Click payment gateways
- Firebase FCM, Socket.io

### 🐳 **DevOps & Infrastructure**
- Docker, Docker Compose (multi-stage, prod overlays)
- Nginx (reverse proxy), PM2
- Certbot / SSL, Contabo & corporate VPS deployments
- SSH tunneling, MinIO

---

## 📈 What I Focus On

- ⚡ Designing **clean, layered backend architecture** (repository → service → endpoint)
- 🗄️ Robust **database design** across PostgreSQL & MySQL
- 🔁 **Queue systems & async workflows** (BullMQ, delayed jobs, state machines)
- 🔐 **Authentication, RBAC, and security** (JWT, CASL, Redis-backed sessions)
- 💳 **Payment gateway integrations** (Payme, Click)
- 📞 **Telephony systems** (Asterisk/FreePBX, WebRTC, real-time events)
- 🐳 **Production deployment & hardening** (Docker, Nginx, SSL, VPS)
- 📱 **End-to-end delivery** — backend, web frontend, and mobile

---

## 🧩 Soft Skills
- Strong systems thinking
- Fast problem-solving & debugging
- Production-first mindset
- Clear communication
- Attention to detail
- Self-driven & disciplined

---

## 📞 Contact
- **GitHub:** *You're already here 😊*
- 💬 Open to collaboration, freelance, and full-time opportunities

---

<p align="center">
  <strong>✨ Thanks for visiting my profile!</strong>
  <br/>
  Building reliable systems, one deployment at a time.
</p>
