# Brian Ndung'u

**Software engineer · Backend systems, APIs and data products** · Computer Science student at Chuka University · Kenya

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
| [ParkNairobi](https://github.com/ray100-art/Park-Nairobi-Fronted) | Smart parking across Kenyan towns: live bay map, nearest-bay search, M-Pesa payments with status polling, sensor entry and exit events, and an admin console | JavaScript, Leaflet, OpenStreetMap, Docker, Nginx, Netlify |
| [DRIP e-commerce backend](https://github.com/ray100-art/DRIP---ECOMMERCE-BACKEND) | REST API for an online fashion store: JWT auth, catalogue, orders, and M-Pesa STK Push checkout | Java 17, Spring Boot 3, Spring Security, JPA, MySQL, Daraja API |
| [DRIP e-commerce frontend](https://github.com/ray100-art/DRIP--ECOMMERCE-FRONTED) | Storefront with catalogue, search, wishlist, cart, M-Pesa checkout and an admin page | JavaScript, HTML, CSS |
| [DaktariAssist](https://github.com/ray100-art/DaktariAssist) | AI clinical second opinion for Kenyan clinicians: checks a proposed diagnosis against vitals and symptoms, and returns red flags, differentials and tests as structured JSON | Java 21, Spring Boot 3, Llama 3.3 70B via Groq |
| [School Record Management System](https://github.com/ray100-art/SchoolRecordManagementSystem) | Desktop app for students, teachers, grades, attendance and fees, with admin and teacher roles and BCrypt logins | Java 21, JavaFX, PostgreSQL, JUnit 5 |
| [Expert Diagnostic System](https://github.com/ray100-art/ExpertDiagnosticSystem) | Computer-troubleshooting expert system that diagnoses 11 faults and explains its reasoning | Prolog |

## What I do

| Area | Focus |
|---|---|
| **Full-stack development** | End-to-end web products: REST APIs, relational data models, authentication, and responsive frontends |
| **Application development** | Web, mobile and desktop apps built for real users and local needs such as mobile-money payments |
| **Desktop applications** | JavaFX line-of-business software with role-based access and a database backend |
| **AI and machine learning** | LLM-powered decision support, prompt design with structured outputs, expert systems, and applied ML |

## Tech stack

| Area | Tools |
|---|---|
| Languages | Java, Python, TypeScript, JavaScript, SQL, C, C++, Prolog |
| Backend | Spring Boot (Web, Security, Data JPA), FastAPI, SQLAlchemy, Pydantic, Alembic, JWT |
| Frontend | React, Vite, Tailwind CSS, TanStack Query, React Router, Leaflet |
| Desktop | JavaFX, FXML, ControlsFX |
| Databases | PostgreSQL, MySQL, SQLite |
| AI and ML | LLM integration (Groq, Llama 3.3), structured JSON outputs, rule-based expert systems |
| Integrations | M-Pesa Daraja (STK Push), OpenStreetMap, geolocation |
| Testing | pytest, Vitest, Testing Library, Playwright, JUnit 5 |
| Delivery | Docker, Nginx, Netlify, Git, Maven |

## How I work

- **Schema first.** I get the data model right before building screens on top of it.
- **Tests against real systems.** End-to-end tests hit the real API, not mocks.
- **Honest interfaces.** Empty and uncertain states are designed, not hidden.

---

Open to full-stack, backend, application-development and AI engineering roles. The fastest way to reach me is
[email](mailto:ndungub058@gmail.com) or [WhatsApp](https://wa.me/254110908913).
