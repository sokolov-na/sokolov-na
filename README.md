# Hi, I'm Nikita

I'm a Computer Science student focused on backend engineering with Python.

I approach software as a system rather than a collection of technologies. I want to understand how the layers fit together — from application logic and data modeling to networking, infrastructure, deployment, and observability.

My current focus is backend development, but the long-term goal is broader: to become a versatile software engineer capable of understanding, designing, and maintaining systems as a whole.

## About me

I learn primarily by building things.

I started with lower-level backend fundamentals and gradually moved toward higher-level abstractions. Instead of treating frameworks as black boxes, I prefer to understand what they solve, what they hide, and where their boundaries are.

This approach has taken me from building an HTTP API without a framework to designing an asynchronous backend with a database, migrations, authentication, testing, and infrastructure around it.

I care about simple architecture, explicit responsibilities, and deliberate trade-offs. I don't want to introduce abstractions because they look sophisticated — I want them to exist because the problem actually requires them.

I'm also interested in the operational side of software: how an application is tested, deployed, observed, logged, and maintained after it leaves the development environment.

## Current focus

**Backend**

* Python
* FastAPI
* PostgreSQL
* SQLAlchemy
* Alembic
* Async programming
* Redis
* Docker

**Engineering**

* Backend architecture
* Database design
* Authentication & authorization
* HTTP & networking
* Testing
* Logging & observability
* CI/CD
* Deployment & infrastructure
* Algorithms & Data Structures

## Projects

### Mini Jira

A backend issue-tracking system built with Python and FastAPI.

The project is used as a practical environment for learning how a backend evolves from application code into a complete system.

Current stack:

* Python
* FastAPI
* PostgreSQL
* SQLAlchemy
* Alembic
* Pydantic
* Docker

Current functionality includes:

* User CRUD
* Password hashing with Argon2
* JWT-based authentication
* Access and refresh tokens
* Refresh-token rotation and revocation
* HttpOnly refresh-token cookies
* Async database access
* Database migrations
* Structured application architecture
* Automated testing

The project is intentionally smaller than Jira itself. The goal is not to reproduce an existing product, but to use a realistic domain to explore backend architecture and the engineering decisions surrounding it.

The next stages extend the system beyond application logic into caching, observability, monitoring, CI/CD, and deployment to a remote server.

**Repository:** [mini-jira](https://github.com/sokolov-na/mini-jira)

### HTTP CRUD API

A small HTTP CRUD API built from scratch without a web framework.

This was my first deliberate step toward understanding backend development below the framework level.

It includes:

* Custom HTTP server and routing
* Service and repository layers
* Validation and error handling
* Unit, integration, and end-to-end tests
* Structured JSONL logging
* Environment-based configuration
* Docker and Docker Compose

**Repository:** [http-crud-api](https://github.com/sokolov-na/http-crud-api)

## How I use AI

I use AI extensively as a development and learning tool, but I don't want it to replace engineering judgment.

I prefer to understand the problem first, design the architecture, and make the important decisions myself.

AI is useful to me for:

* Research and learning
* Code review
* Refactoring
* Documentation
* Finding edge cases
* Exploring alternative approaches
* Testing ideas
* Routine development work

The important part is understanding the system and the reasoning behind its design, regardless of who wrote a particular piece of code.

## What I'm aiming for

I want to become a strong and versatile software engineer with a broad understanding of software systems.

I'm interested not only in writing application code, but also in understanding what happens around it: how data moves through a system, how services communicate, how failures are handled, how software is tested and deployed, and how a running system is observed and maintained.

My goal is to build that understanding layer by layer and eventually be comfortable moving between different parts of a system when the problem requires it.

---

*Building systems, understanding their boundaries, and learning how the pieces fit together.*
