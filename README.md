# Hi, I'm Brian Ndung'u

**Software Engineer · Backend, APIs, AI & Machine Learning** · Computer Science, Chuka University · Kenya 🇰🇪

I design and ship production-minded software end to end: secure REST APIs, well-modelled
relational data, and clean frontends on top. My core stack is **Java / Spring Boot** and
**Python / FastAPI**, with **React + TypeScript** on the client. I care about the things that
make software trustworthy in the real world: correct data models, real authentication,
payment flows that survive network failures, and tests that prove it works.

[Portfolio](https://ray100-art.github.io/) ·
[LinkedIn](https://www.linkedin.com/in/brian-ndung-u-7a0a31345/) ·
[Email](mailto:ndungub058@gmail.com) ·
[WhatsApp](https://wa.me/254110908913)

---

## Featured work

### [ParkNairobi](https://github.com/ray100-art/Park-Nairobi-Frontend): smart parking for Kenyan towns
Live bay map, nearest-bay search, bookings, **M-Pesa payments with status polling**, and sensor
entry/exit events feeding occupancy in real time, plus an admin console for operators.
Backed by a Spring Boot API with role-based access, Flyway migrations, WebSocket updates and an
authenticated, idempotent M-Pesa callback (backend repo private, walkthrough on request).
[Live demo](https://ray100-art.github.io/Park-Nairobi-Frontend/)
`Java 21` `Spring Boot 3` `MySQL` `JavaScript` `Leaflet` `Docker` `Nginx`

### [DaktariAssist](https://github.com/ray100-art/DaktariAssist): AI clinical second opinion
Checks a clinician's proposed diagnosis against vitals and symptoms and returns red flags,
differentials and recommended tests as **structured JSON parsed into typed Java objects** instead of free text,
so the output is dependable enough to build on.
`Java 21` `Spring Boot 3` `LLM integration` `Llama 3.3 70B` `Groq` `Prompt engineering`

### [DRIP Commerce](https://github.com/ray100-art/DRIP---ECOMMERCE-BACKEND): e-commerce platform
REST backend with **JWT authentication (BCrypt + signed tokens)**, catalogue, orders and
**M-Pesa STK Push checkout** (Safaricom Daraja API), paired with a
[storefront](https://github.com/ray100-art/DRIP--ECOMMERCE-FRONTED) featuring search, wishlist, cart and admin.
`Java 17` `Spring Boot 3` `Spring Security` `JPA/Hibernate` `MySQL`

### [School Record Management System](https://github.com/ray100-art/SchoolRecordManagementSystem)
Desktop system for students, teachers, grades, attendance and fees, with admin and teacher roles,
BCrypt-hashed credentials and a PostgreSQL backend.
`Java 21` `JavaFX` `PostgreSQL` `JUnit 5`

<details>
<summary><b>More: algorithms and AI foundations</b></summary>

- [Expert Diagnostic System](https://github.com/ray100-art/ExpertDiagnosticSystem): Prolog rule-based expert system that diagnoses 11 computer faults and explains its reasoning chain
- [Tournament Sort](https://github.com/ray100-art/TournamentSortAlgorithm): O(n log n) knockout-bracket sort in C++
- [Selection Sort](https://github.com/ray100-art/SelectionSortAlgorithm): C implementation with heap allocation and input validation

</details>

---

## What I bring

**Backend & API engineering**
- RESTful API design: resource modelling, validation, pagination, consistent error contracts, OpenAPI docs
- Authentication and authorization: JWT, password hashing (BCrypt), role-based access control
- Payment integration: mobile-money (M-Pesa) flows, asynchronous callbacks and idempotent processing
- Layered architecture (controller → service → repository), dependency injection, SOLID principles

**Data**
- Relational modelling and normalisation, SQL, indexing, transactions
- Schema migrations (Alembic, JPA) and ORM use without losing sight of the SQL underneath

**AI & Machine Learning**
- LLM application design: prompt engineering, structured outputs, guardrails and failure handling
- Knowledge representation and rule-based inference; machine-learning fundamentals and model evaluation

**Quality & delivery**
- Automated testing at every level: unit, integration and end-to-end (JUnit, pytest, Vitest, Playwright)
- Git workflows, pull requests and code review; CI with GitHub Actions
- Containerisation with Docker, Nginx reverse proxying, Linux, and static/cloud hosting

**Professional**
- Turning loosely defined, real-world problems (parking, clinics, schools, retail) into scoped, working software
- Working directly with non-technical stakeholders and explaining trade-offs in plain language
- Clear technical writing: READMEs, API documentation and design notes
- Agile delivery: small increments, frequent feedback, and ownership from idea to deployment

---

## Tech stack

| | |
|---|---|
| **Languages** | Java · Python · TypeScript · JavaScript · SQL · C · C++ · Prolog |
| **Backend** | Spring Boot (Web, Security, Data JPA) · FastAPI · SQLAlchemy · Pydantic · Hibernate |
| **Frontend** | React · Vite · Tailwind CSS · TanStack Query · React Router · Leaflet |
| **Data** | PostgreSQL · MySQL · SQLite · Alembic |
| **AI / ML** | LLM APIs (Groq, Llama) · structured outputs · expert systems |
| **Testing** | JUnit 5 · pytest · Vitest · Testing Library · Playwright |
| **DevOps & tools** | Docker · Nginx · GitHub Actions · Git · Maven · Linux · Netlify |
| **Desktop** | JavaFX · FXML |

---

## How I work

- **Model the data first.** A correct schema makes everything built on top of it simpler.
- **Prove it works.** Tests run against real systems wherever possible, not only mocks.
- **Design for failure.** Timeouts, retries, empty states and bad input are part of the feature.
- **Leave it readable.** Code, commits and docs are written for the next engineer.

---

**Open to** backend, full-stack and AI engineering roles and internships.
The fastest way to reach me is [email](mailto:ndungub058@gmail.com).
