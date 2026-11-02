# Hey, I'm Timothy Musama 👋

**Full-Stack Developer at Injozi · Johannesburg, South Africa 🇿🇦**

I build production software end to end: AI-powered backend systems, cloud infrastructure, and polished web and mobile interfaces. My focus is systems that are secure, auditable, and built to be maintained, not just demoed.

[![Portfolio](https://img.shields.io/badge/Portfolio-kami--solutions-D4AF37?style=flat&logo=vercel&logoColor=white)](https://kami-solutions-website.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Timothy_Musama-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/timothy-musama-b164a7367/)
[![Email](https://img.shields.io/badge/Email-musmatimothy@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:musmatimothy@gmail.com)

---

## ⚡ What I Do

- **Design and ship backend systems**: FastAPI and Django REST APIs, PostgreSQL, async pipelines, and microservice architectures.
- **Build multi-agent AI workflows**: LLM extraction and drafting with a human-in-the-loop approval layer and a full audit trail.
- **Run my own infrastructure**: AWS (EC2, RDS, S3, SES, SQS, Secrets Manager, CloudWatch), Docker, and CI/CD with GitHub Actions.
- **Craft the front end**: React, TypeScript, and React Native with a consistent design system.

---

## 🛠️ Tech Stack

**Backend**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django_REST_Framework-092E20?style=flat&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_+_Alembic-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

**Cloud & DevOps**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

**AI**  
![Claude AI](https://img.shields.io/badge/Claude_AI-D97757?style=flat&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-5A4FCF?style=flat)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Workflows-1F2937?style=flat)

**Frontend & Mobile**  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 💼 Professional Work

### 🤖 AI Booking & Automation Platform — Injozi
*Confidential client project. Details shared in person for verified opportunities.*

An AI-assisted booking and quoting platform for a production business operating across multiple South African cities. It turns unstructured client emails into reviewed, ready-to-send quotes, and nothing goes out without a human approving it.

**How it works:** inbound email → AI extraction → live inventory and availability check → AI-drafted quote and reply → human review → approved send. Every step is logged and explainable.

**What I built and own:**

- A **FastAPI microservices backend** of 9 independently deployable services (auth, workflow, email, draft, audit, inventory, notification, and more) behind an API gateway, each with its own PostgreSQL database and Alembic migrations.
- A **multi-agent AI pipeline** on Claude (email intake, inventory lookup, quote drafting, response writing) with a **human approval layer**. Edits between the AI draft and the final version are stored to improve future results.
- A **workflow state machine** (received → processing → drafted → pending approval → approved → sent) with failure handling, retries, and a quarantine and re-ingest path.
- **Live integration** with a third-party rental management system's API, treated as the system of record.
- **AWS infrastructure** in `af-south-1`: EC2 deployed via Dokploy, RDS PostgreSQL with automated backups, S3 raw-email storage, SES inbound and outbound email, SQS-driven pipeline triggers, Secrets Manager, and CloudWatch alarms.
- **Security-first foundations**: HttpOnly-cookie JWT auth, server-side validation on every endpoint, a full audit trail, and a credential-scanning and cleanup pass across the codebase.
- A **React and TypeScript dashboard** for operators: approval queue, draft editing, sent archive, audit log, and pipeline status.
- **CI/CD on GitHub Actions** (lint, security scan, tests, Docker build, migration check) with 400+ automated tests and 70%+ coverage across services.

**Stack:** Python · FastAPI · PostgreSQL · SQLAlchemy · Alembic · React · TypeScript · Claude AI · AWS (EC2 · RDS · S3 · SES · SQS · Secrets Manager · CloudWatch) · Docker · Nginx · Dokploy · GitHub Actions

> 🔒 *Private repositories. Walkthrough and architecture discussion available on request.*

---

### 🚗 MotorCloud Business — Mkhwany Holdings
A mobile-first vehicle management application in the MotorCloud ecosystem (Django API, Angular web app, and React Native mobile app).  
I designed and built the React Native UI/UX, including the user journey, screen flows, and all core pages, and contributed to security testing of the platform (dependency scanning, security-header inspection, JWT inspection).

**Stack:** TypeScript · React Native · Context API · iOS (Swift build chain)  
Built with strict TypeScript discipline and 95% test coverage across the codebase.

> 🔒 *Private repository. Available for review upon request.*

---

## 🚀 Personal Projects

### 🏢 Nexus Portal — Enterprise Management Platform
A cross-platform management portal for multi-subsidiary organisations, covering financial requisitions and approvals, HR leave, vehicle fleet tracking, lease management, and policy and claims. One React Native codebase runs on Android, iOS, and Web. I am now extending it into a multi-tenant SaaS with an async **FastAPI microservices backend**.

**What I built:** full UI/UX across 18 screens, a complete TypeScript type system with 25+ interfaces, role-based access control, and a semantic design system.

**Stack:** TypeScript · React Native · Expo v54 · Expo Router · React 19 · RBAC · FastAPI (backend in progress)  
[View Repo →](https://github.com/KamiSolutions/nexus-portal)

### 💅 NailTry — Nail Booking App
A React Native and Expo app that connects clients with nail technicians for style discovery and appointment booking. Features auth, booking management, status tracking, skeleton loaders, and a Django REST API backend. Built with strict TypeScript, Context API, and production-grade error handling.  
[View Repo →](https://github.com/KamiSolutions/Nail-app)

### 🖥️ Admin Dashboard
A Next.js 15 admin dashboard with TypeScript, Tailwind CSS, Shadcn UI, Auth.js, and PostgreSQL.  
[View Repo →](https://github.com/KamiSolutions/admin-dashboard)

### 🌐 CleanX Website
A multi-page business website in HTML, CSS, and JavaScript, deployed on Vercel.  
[View Repo →](https://github.com/KamiSolutions/valoworx-html) · [Live Demo →](https://valoworx-html.vercel.app)

---

## 🧭 How I Work

- **Security over convenience.** Secrets live in a secrets manager, auth tokens stay out of the browser, and the backend never trusts the frontend.
- **AI drafts, humans decide.** I design AI systems with approval gates, audit trails, and explainable outputs.
- **Clean architecture.** Thin views and handlers, business logic in services, typed code, and tests that run in CI on every push.
- **Ship incrementally.** Phased rollouts, clear documentation, and honest status reporting.

---

## 📫 Let's Connect

💼 **Open to full-stack, backend, and mobile developer roles** in Johannesburg and remote.  
📧 [musmatimothy@gmail.com](mailto:musmatimothy@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/timothy-musama-b164a7367/)  
🌍 [Portfolio](https://kami-solutions-website.vercel.app)
