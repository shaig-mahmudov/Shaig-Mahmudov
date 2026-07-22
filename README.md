<div align="center">

# Shaig Mahmudov

### Backend Engineer · Developer Tools · Reliability Engineering

I build backend systems, developer tools, and infrastructure-oriented software using Java, Go, Rust, Python, and TypeScript.

[Projects](#featured-projects) · [Engineering Focus](#engineering-focus) · [Contact](#contact)

</div>

---

## About Me

I am a backend-focused software engineer interested in systems that involve more than standard CRUD operations.

My work currently focuses on:

* Developer tooling and code intelligence
* Backend reliability and failure testing
* Java and Spring Boot systems
* Go-based infrastructure tools
* Rust-based local developer tools
* AI-assisted backend infrastructure
* Static analysis and Model Context Protocol integrations
* Domain-driven and modular system design

I enjoy designing system boundaries, modelling failure scenarios, defining contracts, and building tools that help other developers understand or test complex systems.

## Currently Working On

* **Graphine** — a local-first code-intelligence and MCP foundation for Java and Spring Boot repositories
* **Wreckr** — a production scenario testing platform for backend systems
* **Loopin** — an event discovery and small-group matching platform
* **autoreq** — a command-line HTTP client for repeatable requests, assertions, monitoring, and history

## Featured Projects

### [Graphine](https://github.com/shaig-mahmudov/graphine)

Local-first code intelligence for Java and Spring Boot repositories.

Graphine analyzes repository structure without uploading source code and exposes compact structural context to AI coding agents through MCP.

**Highlights:**

* Rust workspace and CLI
* Java analysis through Eclipse JDT
* Spring static-semantics analysis
* Local SQLite-backed indexes
* MCP server over STDIO
* Evidence-backed symbol and endpoint queries
* Deterministic evaluation and benchmark tooling
* Explicit uncertainty and unsupported-state handling

**Technologies:** Rust, Java, Eclipse JDT, SQLite, MCP

---

### [Wreckr](https://github.com/shaig-mahmudov/wreckr)

A production scenario testing platform designed to break backend systems before production does.

Wreckr simulates failure modes that are difficult to cover with ordinary unit or integration tests.

**Scenarios include:**

* Load spikes
* Race conditions
* Duplicate transactions
* Broken idempotency
* Retry storms
* Weak rate limiting
* Slow dependencies
* Queue backlogs

**Technologies:** Go, PostgreSQL, Redis, Asynq, Next.js, Docker, k6

---

### [Loopin](https://github.com/the-loopin)

A modular event discovery and group-matching platform.

Loopin helps users discover events, create or join small groups, communicate through real-time chat, and receive semantic event recommendations.

The system is divided into:

* [loopin-api](https://github.com/the-loopin/loopin-api) — Spring Boot backend
* [loopin-web](https://github.com/the-loopin/loopin-web) — Next.js web application
* [loopin-ai](https://github.com/the-loopin/loopin-ai) — FastAPI embedding and reranking service

**Technologies:** Java, Spring Boot, PostgreSQL, Redis, pgvector, Python, FastAPI, Next.js

---

### [autoreq](https://github.com/shaig-mahmudov/autoreq)

A lightweight developer CLI for sending, repeating, inspecting, and monitoring HTTP requests.

**Features include:**

* HTTP method shortcuts
* Headers, query parameters, and request bodies
* Bearer and basic authentication
* Request assertions
* Retries and repeat modes
* Until-pass and until-fail execution
* SQLite request history
* Saved requests, environments, and collections
* JSON and CSV history export

**Technologies:** Go, SQLite

## Engineering Focus

### Backend Systems

* Java and Spring Boot
* REST API design
* Authentication and authorization
* PostgreSQL and relational modelling
* Redis
* WebSocket, STOMP, and real-time communication
* Background processing
* Rate limiting
* API security

### Developer Tooling

* Command-line applications
* Static code analysis
* Repository indexing
* Model Context Protocol servers
* Local-first tools
* Structured evidence retrieval
* Benchmark and evaluation systems

### Reliability

* Idempotency
* Race-condition testing
* Retry behaviour
* Load and spike testing
* Bounded concurrency
* Queue overload protection
* Readiness and liveness checks
* Observability and metrics
* Graceful dependency failure

### Architecture

* Domain-Driven Design
* Hexagonal Architecture
* Modular monoliths
* Service boundaries
* Event-driven design
* CQRS concepts
* Explicit contracts and invariants

## Technology Stack

### Languages

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square\&logo=openjdk\&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square\&logo=go\&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)

### Backend and Data

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square\&logo=springboot\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square\&logo=sqlite\&logoColor=white)

### Infrastructure and Tooling

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square\&logo=apachemaven\&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square\&logo=nextdotjs\&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square\&logo=prometheus\&logoColor=white)

## How I Approach Engineering

I prefer systems with:

* Clear ownership boundaries
* Explicit contracts
* Measurable behaviour
* Reproducible tests
* Controlled failure modes
* Honest documentation
* Secure defaults
* Minimal hidden behaviour

I am especially interested in understanding how a system behaves when dependencies slow down, requests are duplicated, queues fill up, connections are interrupted, or assumptions stop being true.

## Contact

* GitHub: [@shaig-mahmudov](https://github.com/shaig-mahmudov)
* Website: [shaig.dev](https://shaig.dev)
* Email: [mahmudovshaig@gmail.com](mailto:mahmudovshaig@gmail.com)

---

<div align="center">

Building tools and backend systems with an emphasis on reliability, structure, and clear engineering boundaries.

</div>
