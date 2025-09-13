# Employee Portal

A full-stack employee management application with an Angular 11 frontend and a Spring Boot 2.4.x backend.  
Frontend is deployed on **Netlify**; backend is deployed on **Render**; data is stored in **PostgreSQL (Supabase)**.  
Built to be cloud-ready with CI (GitHub Actions), container images (GHCR), health checks, CORS, and clean documentation.

> This repo is a **hub**. The code lives in two repositories:
> - **Frontend (Angular)**: https://github.com/shubhamdarge/employee-portal-frontend  
> - **Backend (Spring Boot)**: https://github.com/shubhamdarge/employee-portal-backend

---

## Tech Stack

- **Frontend:** Angular 11, TypeScript, Netlify (hosting)
- **Backend:** Spring Boot 2.4.x, Java 8, Docker, Render (hosting)
- **Database:** PostgreSQL on Supabase (managed Postgres + pooler)
- **CI/CD:** GitHub Actions, images published to GHCR
- **Observability:** Spring Boot Actuator (health), JSON logging (Logback)

---

## Features

- Employee CRUD: create, list, update, delete
- RESTful API with Spring Data JPA
- Environment-based config (dev vs prod)
- SPA routing on Netlify (no 404 on refresh)
- CORS configured for Netlify + localhost
- CI pipelines for both repos
- Containerized backend with published images
