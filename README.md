<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Muhammed+Samir+%F0%9F%91%8B;Backend+Developer+(.NET);Multi-tenant+SaaS+%26+AI+products;Arabic-first+platforms+for+the+Gulf" alt="Typing SVG" />
</a>

<br/>
<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammed-samir-)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:muhammedsamirelsharkawy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MuhammedSamir1)

</div>

---

### About Me

Backend developer with **1+ years** of production experience building APIs and distributed systems with **ASP.NET Core**. At **ElectroPi** I build and ship products for Saudi and Gulf clients end to end: AI meeting intelligence, hiring, multi-tenant strategy SaaS, and consulting platforms.

I focus on clean architecture, bilingual (Arabic / English) products, and systems that hold up under real load: background jobs that recover on their own, clear failure states, and tests for every behavior change.

---

### Tech Stack

<div align="center">

**Languages & Frameworks**

[![My Skills](https://skillicons.dev/icons?i=cs,dotnet,ts,react,nextjs,tailwind)](https://skillicons.dev)
<br/>
<img src="https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/MediatR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
<img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" />

**Databases**

[![My Skills](https://skillicons.dev/icons?i=postgres,mongodb,redis)](https://skillicons.dev)
<br/>
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />

**Messaging & Background Jobs**

<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
<img src="https://img.shields.io/badge/Hangfire-gray?style=for-the-badge&logo=dotnet&logoColor=white" />

**DevOps & Tools**

[![My Skills](https://skillicons.dev/icons?i=docker,git,github,githubactions,jenkins,linux,nginx,grafana,prometheus,azure,postman)](https://skillicons.dev)

</div>

---

### Architecture & Design

```
Microservices · Clean Architecture · Vertical Slice · Onion Architecture
CQRS · Domain-Driven Design (DDD) · SOLID · Event-Driven Architecture
Multi-Tenancy (database per tenant) · Spec-Driven Development · Result Pattern
```

---

### Experience

**Backend Developer — [ElectroPi](https://electropi.ai)** &nbsp;`Oct 2025 – Present · Cairo`
- Building and shipping six products on .NET 10 + PostgreSQL (see [Work at ElectroPi](#work-at-electropi))
- Integrated AI meeting bots, live transcription and AI analysis into an approval workflow, with real-time updates over SignalR
- Built multi-tenant SaaS with a database per tenant, Keycloak auth and tenant resolution from JWT claims
- Built Kafka & RabbitMQ consumers, background workers, and CI/CD with GitHub Actions and Jenkins

**Backend Developer Intern — Elevate Tech** &nbsp;`Feb 2026 – Present · Remote`
- Building systems in a Microservices / Modular Monolith environment
- Working with RabbitMQ, Azure Service Bus, Redis, and CI/CD pipelines
- Agile/Scrum workflows with sprint planning and Jira

**Backend Developer Intern — UpSkilling Eg** &nbsp;`Feb 2025 – Oct 2025 · Remote`
- Advanced backend track: Clean Architecture, Onion, Vertical Slice, CQRS
- Secure APIs with JWT authentication and role-based authorization
- SQL Server + EF Core (Code-First), AutoMapper, FluentValidation

---

### Work at ElectroPi

> Private company products. Code is not public.

#### Qarar — AI decision intelligence for meetings
> Arabic-first platform that turns Teams and Google Meet meetings into decisions and tasks that are reviewed, approved and tracked

- **.NET 10** API + **Next.js** frontend, PostgreSQL, bilingual Arabic / English
- A recording bot joins meetings from Outlook / Google calendars, streams a live transcript and live translation, then produces an AI report
- Organizer review → manager approval workflow for decisions, tasks, risks and open questions, with task escalation
- Live bot status over **SignalR**, failure classification with automatic retries, and background services that recover stuck meetings
- Moved the meeting bot to a new provider behind the same API; 2,000+ xUnit tests

#### Al Camp — Talent & hiring platform
> Jobs, applications, interviews, assessments and offers for companies and candidates

- **.NET 10 Minimal APIs**, Vertical Slice + CQRS (MediatR), FluentValidation, Mapster
- JWT with hashed refresh tokens, OTP flows (email verification, 2FA, password reset) and a dynamic, cached permission system
- File storage on the local disk or S3-compatible (MinIO / AWS S3), branded email templates with MailKit
- Admin panel in **React 19** + TanStack Query; AI-generated interview questions and assignment grading through a FastAPI service

#### Tx360 Dashboard — Multi-tenant strategy SaaS
> Strategy management engine: strategies, goals, projects and initiatives per organization

- **Database-per-tenant** with Finbuckle; the tenant is resolved from the **Keycloak** JWT claim on every request
- Core database for the tenant registry, onboarding, invitations and OTP; tenant data isolated in its own database
- Researched data-source integrations (analytics and social tools) through Airbyte / Kestra

#### Tx360 Admin Console — Tenant management API
- ASP.NET Identity, JWT with refresh-token rotation, user and tenant management for the Tx360 platform
- Assessment content admin (pillars, practices, goals, steps, questions), keeping scores computed at runtime, not stored

#### Saleh Al-Amri Consulting — Business consulting platform
- Bilingual Arabic / English REST API on **ASP.NET Core 10 Minimal APIs**, Vertical Slice with Commands, Queries and Orchestrators
- Identity + JWT, MailKit email, Serilog logging, **Prometheus** metrics, Docker, Jenkins CI/CD

#### Saleh Al-Amri Admin — Admin dashboard
- **React** + Refine + Ant Design admin panel with real-time updates over SignalR and Recharts dashboards

---

### Personal Projects

#### [HR Management System](https://github.com/MuhammedSamir1/HRManagementSystem)
> RESTful API built with **ASP.NET Core 8**, Vertical Slice Architecture & CQRS (MediatR)

- Full HR hierarchy: Organization → Company → Branch → Department → Team
- Modules: Employees, Shifts, Payroll (salaries, bonuses, penalties, loans), Holidays, Contracts
- JWT auth with role-based and feature-based authorization
- Global exception middleware, FluentValidation, AutoMapper, Swagger docs
- SQL Server + EF Core Code-First with Fluent API

#### Maaloma Backend *(Production)*
> Backend for a live consultation & services platform

- APIs for users, bookings, services, and payments
- Integrated **Moyasar** payment gateway with secure transaction handling
- PostgreSQL schema designed for booking and service workflows

---

### Education

**B.Sc. Computer Science** — Higher Institute for Management and Information Technology, Kafr El Sheikh &nbsp;`2019 – 2023`

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=MuhammedSamir1&style=flat-square&color=6C63FF" alt="Profile Views" />
</div>
