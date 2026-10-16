# Hi, I'm Nikita

**Python Backend Developer · Computer Science Student**

I build backend applications with Python and FastAPI. My main interests are
API design, data modeling, authentication, and clear boundaries between
application components. I'm looking for a Python backend internship or junior role.

## Projects

### Mini Jira

My main backend project: a self-hosted application under active development.
The current alpha covers authentication and account management; project and
issue tracking are planned.

- Async REST API with FastAPI, SQLAlchemy, PostgreSQL, and Alembic.
- JWT access tokens, refresh-token rotation and revocation, and HttpOnly cookies.
- Password hashing, profile management, and password recovery.
- Automated tests, Docker Compose, GitHub Actions, and container images in GHCR.
- Deployed on a Linux VPS behind Caddy with HTTPS.

I design the domain model, database schema, and backend architecture and write
the core backend code myself. The React and TypeScript interface was developed
with AI assistance.

[Backend repository](https://github.com/sokolov-na/mini-jira-api) ·
[Application](https://mini-jira.ru) ·
[API docs](https://api.mini-jira.ru/docs)

### HTTP CRUD API

A Python HTTP API built without a web framework to understand request handling,
routing, validation, and persistence beneath framework abstractions.

- CRUD endpoints for users, with JSON file storage.
- Service and repository layers, validation, and error handling.
- Unit, integration, and end-to-end tests.
- Structured JSONL logging, environment-based configuration, and Docker Compose.

[Repository](https://github.com/sokolov-na/http-crud-api)

## Tools I Use

- **Backend:** Python, FastAPI, Pydantic, SQLAlchemy, Alembic, PostgreSQL.
- **Development:** Git, uv, pytest, Ruff, basedpyright.
- **Infrastructure:** Linux, Docker, Docker Compose, GitHub Actions, GHCR, Caddy.
- **Earlier experience:** JavaScript, HTML, CSS, Node.js, Express, and Prisma;
  basic familiarity with React and TypeScript.

## How I Work

I use DDD and Clean Architecture where they help clarify the domain and
responsibilities. I prefer being able to explain a design choice and its
trade-offs over adding abstractions by default.

I use AI to discuss solutions and help with documentation, audits, tests,
deployment, and targeted refactoring. I review its suggestions and remain
responsible for the code and engineering decisions.

Currently studying Redis and caching, resource-level permissions, monitoring,
and distributed systems fundamentals.

[Telegram](https://t.me/N_SOKOL_A)
