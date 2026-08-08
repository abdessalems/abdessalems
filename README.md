# Abdessalem Saadaoui

**Functional Analyst & Full-Stack Developer** · Brussels, Belgium

I work at the point where a business requirement becomes a system: I write the analysis —
requirements, business rules, process models, interface contracts — then build it in Java and
Spring Boot, with the tests that prove it behaves.

Most developers can show you code. Most analysts can show you documents. The repositories below
show the same project as both — **[EuroPay Hub](https://github.com/abdessalems/europay-hub)** ships a
business requirements document, a functional specification, a rule catalogue, user stories with
acceptance criteria, BPMN and UML models and API contracts, alongside the Spring Boot service that
implements them and the ArchUnit + Testcontainers suite that keeps it honest.

---

## Analysis and engineering, on the same project

| Analysis | Engineering |
| --- | --- |
| Requirements engineering · functional specifications · business rules | Java 21 · Spring Boot 3 · Spring Security · JPA/Hibernate |
| Use cases · user stories · Given/When/Then acceptance criteria | REST API design · JWT & API-key auth · OpenAPI contracts |
| BPMN process models · UML (use case, class, ER, state, sequence) | PostgreSQL · Flyway migrations · data modelling |
| Test cases · SQL validation · traceability · risk analysis | JUnit 5 · Testcontainers · ArchUnit · Docker · GitHub Actions |

---

## Tech stack

**Backend**
![Java](https://img.shields.io/badge/Java%2021-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%203-6DB33F?logo=springboot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)

**Frontend**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/Vue%203-4FC08D?logo=vuedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)

**Data & delivery**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI-6BA539?logo=openapiinitiative&logoColor=white)

---

## Selected projects

### [EuroPay Hub](https://github.com/abdessalems/europay-hub) — merchant payment platform
`Java 21` `Spring Boot 3` `PostgreSQL` `Flyway` `React` `TypeScript`

Seven bounded contexts behind one API: merchant onboarding, orders, an explicit payment state
machine, idempotent payment creation, HMAC-signed webhooks with a transactional outbox, an
append-only audit log. Clean Architecture + DDD, with the layering **enforced in CI by ArchUnit**.
Ships the full functional-analysis document set in [`docs/`](https://github.com/abdessalems/europay-hub/tree/main/docs).

### [Functional Analyst Workspace](https://github.com/abdessalems/Functional-Analyst-Workspace) — analysis, made navigable
`Next.js 15` `React 19` `TypeScript` `Tailwind` `PlantUML`

A workspace that shows an analysis end to end — business need, acceptance criteria, rules, BPMN,
interface contract, SQL validation, tests. Every cross-reference resolves, and the traceability
matrix is *derived* from the artefacts' own links, so it cannot drift from them. New projects are
added by importing a spreadsheet that is validated before it is accepted.

### [AI Knowledge Assistant](https://github.com/abdessalems/ai-company-knowledge-assistant-rag) — on-premise RAG over company documents
`.NET` `Clean Architecture` `EF Core` `PostgreSQL` `Angular` `Ollama`

Upload PDFs and Word documents, ask questions in natural language, get answers with document, page
and section citations. Runs entirely locally — no document content leaves the network.

### [FSBE](https://github.com/abdessalems/FastApiProject) — activity planning API *(collaboration)*
`Python` `FastAPI` `SQLAlchemy` `JWT` `Poetry` `Docker`

A **two-person project** with [@antoinecaby](https://github.com/antoinecaby): users, companies,
planning activities and notifications behind JWT authentication and role checks. I wrote the larger
share of the commit history — see the
[contributors graph](https://github.com/abdessalems/FastApiProject/graphs/contributors) and
[my commits](https://github.com/abdessalems/FastApiProject/commits?author=abdessalems).

---

## Background

- **2019–2021** — Functional Analyst & Java Developer, Leejam Sports (Fitness Time), Saudi Arabia
- **2021–2024** — Relocated to Belgium and retrained: IT studies at EPFC Brussels and EFFICOM Lille
  — web back-end, test-driven development, DevOps — alongside an MBA in IT Management (2025)
- **2024–present** — Self-employed full-stack developer and functional analyst, Brussels

Around **four years** of professional experience across Saudi Arabia and Belgium.

Arabic (C2) · French (B2) · English (B2) · Dutch (A2)

---

## Contact

[![Website](https://img.shields.io/badge/Website-saadaoui.it.com-0F766E?logo=googlechrome&logoColor=white)](https://www.saadaoui.it.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/abdussalem-saadaoui-10bb7018a)
[![Email](https://img.shields.io/badge/Email-abdessalemsaa%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:abdessalemsaa@gmail.com)

Brussels, Belgium · self-employed (VAT BE1022923891) · available for freelance and permanent roles
