<div align="center">

<img src="https://avatars.githubusercontent.com/u/293018936?v=4" width="120" height="120" alt="ayal408 GitHub avatar" />

# Backend & Systems Engineer

**Python backends · Multi-database architecture · Full-stack applications**

I build data layers and applications with a focus on clear abstractions,<br/>
reliable failure handling, and maintainable code.

[![Portfolio](https://img.shields.io/badge/Explore_my_work-A4U-0D9488?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ayal408.github.io/a4u/)
[![NexusDB](https://img.shields.io/badge/Open_source-NexusDB-2563EB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ayal408/nexusdb)
[![PyPI](https://img.shields.io/pypi/v/krossdb?style=for-the-badge&label=krossdb&color=2563EB)](https://pypi.org/project/krossdb/)

</div>

---

## About me

My main focus is backend engineering: designing APIs, organizing data access, and making system behavior easier to understand when something goes wrong. I also work across the frontend and deployment layers to connect those foundations to usable applications.

- **Building:** NexusDB, a shared Python data-access interface for relational, document, and vector databases.
- **Working on:** client/server applications, appointment scheduling, and an Israeli accounting and invoicing ERP.
- **Exploring:** circuit breakers, retries with backoff, cache-aside patterns, tenant isolation, and observability.
- **Engineering priorities:** explicit boundaries, consistent error handling, useful tests, and reproducible environments.

## Featured work

### NexusDB — one data-access interface, multiple database families

A Python library built around the **Repository** and **Unit of Work** patterns. It provides a shared interface over PostgreSQL, MySQL, SQLite, MongoDB, and Qdrant.

- Async data access, with SQLAlchemy for relational backends.
- Redis-backed caching, circuit breakers, and retries with exponential backoff.
- Tenant context, audit trails, metrics, and tracing.
- Domain events and a transactional outbox.

**Python · SQLAlchemy · Pydantic · Redis · PostgreSQL · MongoDB · Qdrant**

[Explore the repository](https://github.com/ayal408/nexusdb) · [View the package on PyPI](https://pypi.org/project/krossdb/)

> Published on PyPI as **`krossdb`**; the Python import name remains **`nexusdb`**.

### Domix — a client/server application

An application with a dedicated authentication service, an Nginx entry point, and Docker Compose orchestration.

**Client/server architecture · Authentication · Docker Compose · Nginx**

[Explore the repository](https://github.com/ayal408/domix)

### More projects

| Project | Focus | Stack / status |
| --- | --- | --- |
| Israeli accounting & invoicing ERP | Business workflows for small businesses in Israel | .NET · React · Private, in progress |
| Treatment scheduling | Booking and managing appointments | TypeScript |

## Technology stack

**Backend & application development**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

**Databases & caching**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Development, testing & infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

Also in my toolbox: **async SQLAlchemy · Pydantic v2 · structlog · Testcontainers · Bash**

## How I approach engineering

| Priority | What it means in my projects |
| --- | --- |
| Clear boundaries | Keep application logic separate from database drivers and infrastructure. |
| Failure handling | Make retries, timeouts, and error handling explicit. |
| Data isolation | Treat tenant context and access boundaries as part of the design. |
| Observability | Use structured logs and audit trails to explain system behavior. |
| Repeatable development | Use tests, CI, and containers to make changes easier to verify. |

<details>
<summary><strong>Contribution activity</strong></summary>

<br/>

![Animated GitHub contribution grid](https://raw.githubusercontent.com/ayal408/ayal408/output/github-contribution-grid-snake.svg)

[View achievements on GitHub](https://github.com/ayal408?tab=achievements)

</details>

---

<div align="center">

**Explore my projects and follow what I'm building.**

[Portfolio](https://ayal408.github.io/a4u/) · [Repositories](https://github.com/ayal408?tab=repositories) · [NexusDB on PyPI](https://pypi.org/project/krossdb/)

</div>
