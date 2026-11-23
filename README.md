# Punith R

**Full-Stack / Backend Engineer focused on building production-style systems, with an emphasis on backend architecture, API design, database engineering, and system reliability.**

I enjoy building applications that go beyond CRUD by tackling real-world engineering challenges such as:

- Transactional consistency and data integrity
- Concurrent operations and race-condition prevention
- Offline-first workflows and synchronization
- Reliable asynchronous processing and real-time updates
- Scalable backend architecture and testing-driven reliability

Currently focused on backend engineering with **Go, PostgreSQL, and Node.js**, exploring concurrency, distributed systems concepts, and production-grade application design.

---

# Featured Projects

## TicketForge (Go / High-Concurrency Backend)

A high-concurrency ticket booking engine built with **Go and PostgreSQL 18**, focused on transactional inventory management, reservation lifecycles, payment processing, and reliable asynchronous workflows.

🔗 GitHub: https://github.com/Punith1117/ticket-forge

### Highlights

- Implemented concurrency-safe ticket reservations using PostgreSQL transactions, row-level locking, and inventory constraints to prevent overselling.
- Built a two-phase reservation and booking workflow with temporary inventory holds, lazy expiration, and simulated payment processing.
- Implemented a transactional outbox pattern with background workers, batch leasing using `FOR UPDATE SKIP LOCKED`, retry handling, and dead-letter processing.
- Designed payment webhook handling with idempotency protection and compensation for late payments.
- Implemented secure authentication using Argon2id password hashing, stateful sessions, and PostgreSQL-backed rate limiting.
- Used SQL-first database tooling with `pgx`, `sqlc`, and Goose migrations instead of an ORM.
- Documented architectural decisions, domain models, state machines, critical workflows, and failure scenarios through system design documents and ADRs.

**Tech Stack:** Go, PostgreSQL 18, pgx, sqlc, Goose, Docker, Mailpit

**Focus:** Concurrent systems, transactional consistency, inventory management, idempotency, asynchronous processing, and backend reliability.

*Status: Actively under development.*

## Secure Feedback Platform (System Design / Backend Focus)

A secure, offline-first feedback system designed for educational institutions with strong emphasis on **data integrity and reliability under failure conditions**.

🔗 Live: https://secure-feedback-platform.vercel.app/  
🔗 GitHub: https://github.com/Punith1117/secure-feedback-platform  

### Highlights

- Transaction-safe feedback submission with one-time access codes  
- Offline-first architecture with IndexedDB-based local persistence and sync recovery  
- Real-time admin updates using pub/sub (Ably)  
- Normalized PostgreSQL schema for scalable reporting and analytics  
- Integration and end-to-end testing with real database workflows  
- CI pipeline with automated testing and validation  

**Focus:** system reliability, transactional integrity, offline-first design, real-time systems  

---

## Social Media Platform (Full-Stack System)

A production-style social media application implementing core social networking features with a full REST API backend and frontend integration.

### Backend

🔗 GitHub: https://github.com/Punith1117/social-media-backend  

### Frontend

🔗 GitHub: https://github.com/Punith1117/social-media-frontend  
🔗 Live: https://social-media-punith1117.netlify.app/explore  

### Highlights

- JWT authentication with secure session handling  
- User profiles, follow system, posts, likes, and comments  
- Feed system with cursor-based pagination, infinite scrolling and optimized queries  
- RESTful API architecture using Express and PostgreSQL
- Rate limiting for comments
- Optimistic updates for likes
- File uploads via Cloudinary  
- Structured backend with controllers, middleware, and services  

**Focus:** REST API design, relational database modeling, full-stack integration  

---

# Technical Skills

**Languages:** Go, JavaScript, TypeScript  
**Backend:** Go, Node.js, Express, REST APIs  
**Databases:** PostgreSQL, Prisma, Drizzle ORM, sqlc  
**Frontend:** React, Next.js  
**Testing:** Go testing, Vitest, Playwright, Jest, Supertest  
**Tools & Infrastructure:** Git, Docker, GitHub Actions, Postman, Goose  
**Deployment:** Vercel, Netlify, Render

---

# Engineering Focus Areas

- Backend API design and system architecture
- Concurrent programming and race-condition prevention
- Database modeling, transactions, and consistency
- Authentication, authorization, and API security
- Idempotency and reliable payment workflows
- Background processing and event-driven architecture
- Distributed systems concepts and fault tolerance
- Integration, concurrency, and end-to-end testing

---

# Current Improvements

- Building TicketForge, a high-concurrency ticket booking backend in Go
- Exploring Redis for caching and distributed coordination
- Implementing background workers and reliable asynchronous processing
- Strengthening observability, structured logging, and system debugging
- Exploring load testing and backend performance optimization
- Improving Docker-based development and deployment workflows 

---

# Open Source Contributions 

- Contributed merged pull request to [React Documentation](https://github.com/reactjs/react.dev/pull/7629), improving learning resources by clarifying framework behavior after maintainer review and iterative feedback.
- Contributed multiple merged pull requests to [The Odin Project](https://github.com/TheOdinProject/curriculum/pull/29282), correcting curriculum content and updating React learning materials to remain compatible with React 19 ecosystem changes.
- Improved [Ghostfolio](https://github.com/ghostfolio/ghostfolio/pull/6978) by contributing Ukrainian localization updates through the project’s collaborative review and merge process.

---

# Learning Direction

- System design fundamentals for scalable web applications  
- Distributed systems concepts (event-driven design, caching layers)  
- Production-grade backend engineering practices  
- Performance optimization techniques for APIs and databases  

---

# Contact

- LinkedIn: https://www.linkedin.com/in/punith-r-yes  
- GitHub: https://github.com/Punith1117  
- Email: punith.r.pro@gmail.com
