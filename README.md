# Brian Ndung'u

**Software engineer · Backend systems, APIs and data products** · Kenya

I build backend systems that stay honest about what they know, from REST APIs with proper
auth to data pipelines whose output a non-engineer can trust. Most of my work is in Java
(Spring Boot) and Python (FastAPI), with React/TypeScript on the front end. I'm currently
building **ScoutBridge AI**, a football scouting platform that turns match data into
evidence-backed judgement.

[LinkedIn](https://www.linkedin.com/in/brian-ndung-u-7a0a31345/) ·
[Email](mailto:ndungub058@gmail.com) ·
[WhatsApp](https://wa.me/254110908913) ·
[Portfolio](https://ray100-art.github.io/)

---

## What I'm building

**ScoutBridge AI** — *private repository, walkthrough on request*
A talent-intelligence platform for under-covered football leagues. It keeps every metric
alongside its context (role, zone, phase of play, pressure, sample size, confidence), so a
number is never shown without saying how much it can be trusted.

- **Backend:** FastAPI monolith, async SQLAlchemy 2, Pydantic v2, Alembic migrations, PostgreSQL
- **Frontend:** React 18, TypeScript, Vite, Tailwind, TanStack Query, with a documented design system
- **Quality:** pytest for the API and Vitest for the UI. Playwright end-to-end tests run against the
  real API and enforce the product's honesty rules: age gating, confidence labels and calibration gates.
- **Access:** role-based access control (scout, viewer, admin, player) with JWT auth

## Selected projects

| Project | What it is | Stack |
|---|---|---|
| [DRIP e-commerce backend](https://github.com/ray100-art/DRIP---ECOMMERCE-BACKEND) | REST API for an online store with JWT authentication and role-based security | Java 17, Spring Boot 3, Spring Security, JPA, MySQL |
| [DRIP e-commerce frontend](https://github.com/ray100-art/DRIP--ECOMMERCE-FRONTED) | Storefront with catalogue, search, wishlist, checkout and an admin view | JavaScript, HTML, CSS |
| [DaktariAssist](https://github.com/ray100-art/DaktariAssist) | Symptom-analysis assistant that sends structured requests to an LLM | Java 21, Spring Boot 3, Groq API |
| [School Record Management System](https://github.com/ray100-art/SchoolRecordManagementSystem) | Desktop app for student records with hashed logins, PDF reports and CSV handling | Java, JavaFX, PostgreSQL, iText, BCrypt |
| [Park Nairobi](https://github.com/ray100-art/Park-Nairobi-Fronted) | Parking booking dashboard, containerised for deployment | JavaScript, Docker, Nginx, Netlify |
| [Expert Diagnostic System](https://github.com/ray100-art/ExpertDiagnosticSystem) | Rule-based diagnostic expert system | Prolog |

## Tech stack

| Area | Tools |
|---|---|
| Languages | Java, Python, TypeScript, JavaScript, SQL, C, C++, Prolog |
| Backend | Spring Boot (Web, Security, Data JPA), FastAPI, SQLAlchemy, Pydantic, Alembic, JWT |
| Frontend | React, Vite, Tailwind CSS, TanStack Query, React Router, JavaFX |
| Databases | PostgreSQL, MySQL, SQLite |
| Testing | pytest, Vitest, Testing Library, Playwright, JUnit 5 |
| Delivery | Docker, Nginx, Netlify, Git, Maven |
| AI | LLM API integration (Groq), rule-based expert systems |

## How I work

- **Schema first.** I get the data model right before building screens on top of it.
- **Tests against real systems.** End-to-end tests hit the real API, not mocks.
- **Honest interfaces.** Empty and uncertain states are designed, not hidden.

---

Open to backend, full-stack and data-product roles. The fastest way to reach me is
[email](mailto:ndungub058@gmail.com) or [WhatsApp](https://wa.me/254110908913).
