# Hi, I'm Nikita

**Python Backend Developer · Computer Science Student**

I build backend applications with Python, focusing on API design, databases, authentication, testing, and deployment.

I'm interested in how software works beyond individual frameworks — from application architecture and data modeling to networking, infrastructure, and production operations.

I learn by building systems, understanding their trade-offs, and improving them through practical experience.

## Tech Stack

**Backend & Databases**
- Python, FastAPI, Pydantic
- PostgreSQL, SQLAlchemy, Alembic
- Async programming, REST APIs
- Authentication & authorization

**Infrastructure & Engineering**
- Docker, Docker Compose, Linux
- Git, GitHub Actions, CI/CD, GHCR
- Caddy, Cloudflare, HTTPS
- Pytest, automated testing, application logging

**Additional Experience**
- JavaScript, HTML, CSS
- Node.js, Express, Prisma
- TypeScript and React — basic familiarity

## Projects

### Mini Jira

**A self-hosted project management application under active development, built around a Python backend.**

[Live Application](https://mini-jira.ru) · [API Documentation](https://api.mini-jira.ru/docs) · [Backend Repository](https://github.com/sokolov-na/mini-jira-api)

Mini Jira is my primary engineering project, developed to explore the full lifecycle of a backend system — from architecture and implementation to automated testing, deployment, and production operation.

**Backend**
- Asynchronous REST API with FastAPI and SQLAlchemy
- PostgreSQL with versioned Alembic migrations
- JWT-based authentication with access and refresh tokens
- Refresh-token rotation, revocation, and HttpOnly cookies
- Password hashing, account management, and email-based password recovery
- Automated functional and integration tests

**Infrastructure**
- Linux VPS deployment with Docker Compose
- Caddy reverse proxy and automatic HTTPS
- Cloudflare DNS configuration
- Container images distributed through GHCR
- GitHub Actions for automated testing and release workflows
- Versioned deployments with rollback capability

The application also includes a React and TypeScript web interface, developed with AI assistance and integrated with the backend API.

The current foundation covers authentication and account management. Upcoming development focuses on projects, membership, permissions, and issue tracking.

### HTTP CRUD API

[Repository](https://github.com/sokolov-na/http-crud-api)

An HTTP CRUD API built without a web framework to explore what happens beneath higher-level backend abstractions.

- Custom HTTP server and routing
- Service and repository layers
- Validation and error handling
- Unit, integration, and end-to-end tests
- Structured JSONL logging
- Environment-based configuration
- Docker and Docker Compose

This project helped me understand the responsibilities that frameworks typically abstract away.

## Engineering Approach

I prefer simple architecture, explicit responsibilities, and abstractions driven by real requirements rather than unnecessary complexity.

I value understanding how a system behaves as a whole — not only how its components are implemented, but also how they interact, fail, recover, and operate in production.

I use AI as a tool for research, implementation, code review, testing, and routine development. Architecture, trade-offs, and engineering decisions remain my responsibility.

## Currently Exploring

- Database design and transaction management
- Resource-level authorization and permission models
- Redis and caching strategies
- Application security, monitoring, and observability
- Distributed systems fundamentals

---

*Building systems, understanding their boundaries, and learning how the pieces fit together.*
