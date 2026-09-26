# Akash Damle

**Backend engineer, 8+ years of total experience.** I build and run systems in Django, with Node.js and TypeScript alongside: typed API contracts, test suites that run in CI, and deployments I maintain myself.

Badlapur, India · Available for remote roles · [akashdamle.in](https://www.akashdamle.in)

---

## Work

**Freelance Software Engineer** · Independent, remote · Mar 2021 – present

- Built and self-host Django CRM systems for 27+ clients: schools, clinics and small businesses. Employee management, payroll, attendance and reporting.
- Own the backend on every engagement: schema design, REST API, provisioning, release and ongoing support. Sole engineer on some; on others, alongside a frontend developer.
- Run the infrastructure directly: self-managed Linux servers with PostgreSQL, including backups, TLS and upgrades.

**Junior Software Developer** · Matalli Infotech, Dombivli · Aug 2018 – Feb 2021

- Built and maintained internal web applications on Django 2.2 LTS in a small team.
- Wrote unit and database-level tests, worked on CI/CD pipelines, and managed deployments to Linux servers, AWS and Heroku.

---

## Projects

### [bharat-post-dir](https://github.com/code-kasha/bharat-post-dir)

India's postal directory as a lookup page, a JSON API and a one-file download: 155,599 offices, with every page stating where the data came from. Django, Django REST Framework, SQLite, Docker.

- Imports are validated in full, then replace the directory in one transaction; a failed import changes nothing.
- The lookup page costs one HTTP request, with no JavaScript, and works by keyboard and screen reader.
- v1.0.0 is released with a public Docker image for amd64 and arm64, and a [live demo](https://bharat-post-dir.onrender.com/) until 26 December 2026.

### [Lead Management Platform](https://github.com/code-kasha/lead-platform-digital_heroes)

Lead management built to a short deadline as a qualification task. Django REST Framework, React, TypeScript.

- Role-based access control across the lead lifecycle: creation, assignment, status transitions, notes and activity history, enforced on the server.
- The OpenAPI specification generates the TypeScript models the frontend uses, so a backend change shows up as a type error.
- JWT authentication with refresh tokens.

### [MaxRead API](https://github.com/code-kasha/maxread-api)

A REST API for a novel-reading app. Express, TypeScript, MongoDB.

- Zod schemas drive request validation and the generated OpenAPI docs, so the two cannot drift.
- Integration tests with Vitest and Supertest against an in-memory MongoDB, run by GitHub Actions with lint and type-check on every push.

### CRM · in research and planning

My main product: a CRM that arrives already set up for how your business works (sales, agency, real estate or field services) instead of making you configure it first.

---

## Stack

**Backend:** Django, Django REST Framework, Node.js, Express  
**Languages:** Python, TypeScript, JavaScript, SQL  
**Data:** PostgreSQL, MongoDB, SQLite, schema design, query tuning  
**Quality:** Pytest, Vitest, Supertest, Zod, OpenAPI  
**Platform:** Linux, Docker, GitHub Actions, AWS, Heroku  
**Frontend:** React, Next.js, Tailwind CSS

---

## Education

B.Sc, Computer Science · P V G's College of Science, 2014–2018

---

## Contact

[Email](mailto:akashdamle07@gmail.com) · [LinkedIn](https://www.linkedin.com/in/akash-damle-58a808258/) · [Website](https://www.akashdamle.in)
