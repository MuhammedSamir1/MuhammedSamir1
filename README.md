<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1b27,50:3b2f80,100:6C63FF&height=220&section=header&text=Muhammed%20Samir&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Backend%20Engineer%20%E2%80%A2%20.NET%20%E2%80%A2%20AI%20and%20SaaS%20products&descAlignY=58&descSize=18" alt="Muhammed Samir" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=8B85FF&center=true&vCenter=true&width=640&lines=Building+production+APIs+with+ASP.NET+Core;Multi-tenant+SaaS+%C2%B7+database+per+tenant;AI+meeting+intelligence+%C2%B7+live+transcripts;Arabic-first+products+for+the+Gulf" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://linkedin.com/in/muhammed-samir-"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:muhammedsamirelsharkawy@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://electropi.ai"><img src="https://img.shields.io/badge/ElectroPi-6C63FF?style=for-the-badge&logo=lightning&logoColor=white" alt="ElectroPi" /></a>
  <img src="https://komarev.com/ghpvc/?username=MuhammedSamir1&style=for-the-badge&color=3b2f80&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 👨‍💻 About Me

<table>
<tr>
<td width="52%" valign="top">

- 🏢 **Backend Developer at [ElectroPi](https://electropi.ai)**, shipping six products end to end
- 🌍 Building **Arabic-first** platforms for Saudi and Gulf clients
- 🧠 AI meeting intelligence, hiring, strategy SaaS and consulting platforms
- 🏗️ Clean, Vertical Slice and Onion architecture, CQRS, DDD
- 🛡️ Systems that recover on their own: retries, reconciliation jobs, clear failure states
- ✅ A test for every behavior change
- 📍 Cairo, Egypt

</td>
<td width="48%" valign="top">

```csharp
public sealed class MuhammedSamir : Engineer
{
    public string Role => "Backend Developer @ ElectroPi";
    public string Stack => ".NET 10 · PostgreSQL · React";

    public string[] Building =>
    [
        "AI meeting intelligence",
        "Multi-tenant SaaS",
        "Hiring platforms",
    ];

    public string[] Speaks => ["العربية", "English"];

    public string Motto =>
        "Ship it, test it, make it heal itself.";
}
```

</td>
</tr>
</table>

---

## 🚀 Work at ElectroPi

> Private company products. The code is not public.

<table>
<tr>
<td width="50%" valign="top">

### 🎙️ Qarar
**AI decision intelligence for meetings**

A bot joins Teams and Google Meet meetings, streams a **live transcript and translation**, and turns the meeting into decisions, tasks and risks that go through **review and approval**.

- Calendar sync with Outlook and Google
- Live bot status over SignalR, automatic retries
- Background jobs that recover stuck meetings
- 2,000+ xUnit tests

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/Microsoft_Graph-0078D4?style=flat-square&logo=microsoft&logoColor=white" />

</td>
<td width="50%" valign="top">

### 🧑‍💼 Al Camp
**Talent and hiring platform**

Jobs, applications, interviews, assessments and offers for companies and candidates, with **AI-generated interview questions** and assignment grading.

- Vertical Slice + CQRS with MediatR
- JWT, hashed refresh tokens, OTP and 2FA
- Dynamic permissions cached per role
- Files on S3-compatible storage (MinIO / AWS S3)

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Tx360 Dashboard
**Multi-tenant strategy management SaaS**

Strategies, goals, projects and initiatives for each organization, with **a database per tenant**.

- Tenant resolved from the Keycloak JWT on every request
- Core database for tenants, onboarding and invitations
- Data-source integrations through Airbyte / Kestra

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white" /> <img src="https://img.shields.io/badge/Finbuckle-MultiTenant-2E7D32?style=flat-square" /> <img src="https://img.shields.io/badge/Hangfire-1E1E1E?style=flat-square" /> <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white" />

</td>
<td width="50%" valign="top">

### 🛠️ Tx360 Admin Console
**Tenant and content management API**

User and tenant management for the Tx360 platform, plus the **assessment content** admin: pillars, practices, goals, steps and questions.

- ASP.NET Identity with refresh-token rotation
- Scores computed at runtime, never stored
- Integration tests with Testcontainers

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/ASP.NET_Identity-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Testcontainers-291A3F?style=flat-square&logo=testcontainers&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💼 Saleh Al-Amri Consulting
**Bilingual business consulting platform**

Arabic / English REST API on **Minimal APIs**, Vertical Slice with Commands, Queries and Orchestrators.

- Identity + JWT, MailKit email, QuestPDF reports
- Serilog, Sentry and Prometheus metrics
- Docker, Jenkins CI/CD

<img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" /> <img src="https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white" /> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />

</td>
<td width="50%" valign="top">

### 🖥️ Saleh Al-Amri Admin
**Admin dashboard**

Admin panel for the consulting platform with **real-time updates** and charts.

- Refine + Ant Design
- SignalR live updates, Recharts dashboards
- Vitest and Playwright tests

<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" /> <img src="https://img.shields.io/badge/Refine-14141F?style=flat-square" /> <img src="https://img.shields.io/badge/Ant_Design-0170FE?style=flat-square&logo=antdesign&logoColor=white" /> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<h3 align="center">Backend</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" /><br/><br/>
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Minimal_APIs-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/MediatR-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FluentValidation-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mapster-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AutoMapper-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Hangfire-1E1E1E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/QuestPDF-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" />
</p>

<h3 align="center">Frontend <sub>(familiar)</sub></h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,vite,mui&theme=dark" /><br/><br/>
  <img src="https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white" />
  <img src="https://img.shields.io/badge/Ant_Design-0170FE?style=for-the-badge&logo=antdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/Refine-14141F?style=for-the-badge" />
</p>

<h3 align="center">Data & Messaging</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,redis,mongodb&theme=dark" /><br/><br/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
</p>

<h3 align="center">Auth & Integrations</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white" />
  <img src="https://img.shields.io/badge/ASP.NET_Identity-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth_2.0-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Microsoft_Graph-0078D4?style=for-the-badge&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_APIs-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/Finbuckle_MultiTenant-2E7D32?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MinIO_%2F_S3-C72E49?style=for-the-badge&logo=minio&logoColor=white" />
</p>

<h3 align="center">AI Integrations</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Live_Transcription-6C63FF?style=for-the-badge" />
</p>

<h3 align="center">Cloud, DevOps & Observability</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,linux,githubactions,jenkins,grafana,prometheus,aws,git,postman&theme=dark" /><br/><br/>
  <img src="https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Serilog-1E1E1E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white" />
</p>

<h3 align="center">Testing</h3>
<p align="center">
  <img src="https://img.shields.io/badge/xUnit-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Moq-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NSubstitute-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FluentAssertions-3b2f80?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logo=testcontainers&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white" />
</p>

---

## 🏛️ Architecture & Practices

<p align="center">
  <img src="https://img.shields.io/badge/Clean_Architecture-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Vertical_Slice-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Onion-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CQRS-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DDD-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Microservices-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Event--Driven-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Multi--Tenancy-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Result_Pattern-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Spec--Driven_Development-1a1b27?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SOLID-1a1b27?style=for-the-badge" />
</p>

---

## 💼 Experience

**Backend Developer · [ElectroPi](https://electropi.ai)** &nbsp;`Oct 2024 – Present · Cairo`
- Building and shipping six products on .NET 10 and PostgreSQL ([see above](#-work-at-electropi))
- Integrated AI meeting bots, live transcription and AI analysis into an approval workflow, with real-time updates over SignalR
- Built multi-tenant SaaS with a database per tenant, Keycloak auth and tenant resolution from JWT claims
- Built Kafka and RabbitMQ consumers, background workers, and CI/CD with GitHub Actions and Jenkins

**Backend Developer Intern · Elevate Tech** &nbsp;`Feb 2026 – Present · Remote`
- Building systems in a Microservices / Modular Monolith environment
- Working with RabbitMQ, Redis, and CI/CD pipelines
- Agile/Scrum workflows with sprint planning and Jira

**Backend Developer Intern · UpSkilling Eg** &nbsp;`Feb 2025 – Oct 2025 · Remote`
- Advanced backend track: Clean Architecture, Onion, Vertical Slice, CQRS
- Secure APIs with JWT authentication and role-based authorization
- SQL Server + EF Core (Code-First), AutoMapper, FluentValidation

---

## 🧪 Personal Projects

<table>
<tr>
<td width="50%" valign="top">

### [🏢 HR Management System](https://github.com/MuhammedSamir1/HRManagementSystem)
RESTful API on **ASP.NET Core 8** with Vertical Slice and CQRS (MediatR).

- Organization → Company → Branch → Department → Team
- Employees, shifts, payroll, holidays, contracts
- Role- and feature-based authorization

</td>
<td width="50%" valign="top">

### 🗓️ Maaloma Backend *(Production)*
Backend for a live consultation and services platform.

- Users, bookings, services and payments
- **Moyasar** payment gateway
- PostgreSQL schema for booking workflows

</td>
</tr>
</table>

---

## 🎓 Education

**B.Sc. Computer Science** · Higher Institute for Management and Information Technology, Kafr El Sheikh &nbsp;`2019 – 2023`

---

## 📈 GitHub Activity

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MuhammedSamir1&theme=tokyonight&hide_border=true&background=1a1b27&ring=6C63FF&fire=8B85FF&currStreakLabel=8B85FF" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=MuhammedSamir1&theme=tokyo-night&hide_border=true&bg_color=1a1b27&color=8B85FF&line=6C63FF&point=ffffff&area=true" alt="Contribution graph" />
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C63FF,50:3b2f80,100:1a1b27&height=120&section=footer" alt="" />
</p>
