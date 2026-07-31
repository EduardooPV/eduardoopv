<h1 align="left">Luiz Eduardo Prado Veltroni</h1>

<p align="left">
  <b>Fullstack Software Engineer</b> &nbsp;·&nbsp; TypeScript &nbsp;·&nbsp; Node.js / NestJS &nbsp;·&nbsp; .NET &nbsp;·&nbsp; Vue &amp; React
</p>

<p align="left">
  I build <b>regulated fintech systems</b> at <b>Warren Investimentos</b> — investment onboarding, compliance, portability (CVM 210) and Wealth as a Service (WaaS).
  In this domain a bug is a regulatory incident, not just a bad UX, so most of my work is about <b>reliability, traceability and explicit trade-offs</b>.
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/luiz-veltroni/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:eduardoveltroni@hotmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=flat-square&logo=gmail&logoColor=white" alt="E-mail" /></a>
</p>

---

## Selected projects

These are labs, not toys. Each one exists to answer a concrete engineering question, and each README opens with **problem → decision → trade-off**.

| Project | Question it answers | Stack | Evidence in the repo |
| --- | --- | --- | --- |
| **[shopping-list-api](https://github.com/EduardooPV/shopping-list-api)** | How much framework do you actually need? A production-shaped REST API written on Node's native `http` — no Express, no Nest. | Node.js (native http), TypeScript, Prisma, PostgreSQL, Jest, Docker, Kubernetes | JWT + refresh token in HttpOnly cookie, bcrypt, use cases / entities, OpenAPI 3 served via Scalar, Prometheus latency histogram (p50/p95/p99), K8s manifests, GitHub Actions |
| **[corretora-investimentos](https://github.com/EduardooPV/corretora-investimentos)** | What actually breaks in a brokerage domain (Account, Asset, Order) as you add infrastructure? Built in phases: naive first, then measured, then fixed. | Vue, NestJS (BFF), .NET, PostgreSQL, Redis, RabbitMQ, Keycloak, Grafana | An N+1 introduced **on purpose** and measured before being fixed, idempotency key on order placement, ACID transaction on balance, OAuth2 + PKCE via Keycloak |
| **[aws-serverless](https://github.com/EduardooPV/aws-serverless)** | Can a distributed financial flow be developed and tested end to end locally, before touching a real AWS bill? | .NET, LocalStack, Terraform, AWS (Lambda, SQS, SNS) | Phase 1 shipped: infrastructure as code + API running on LocalStack. Later phases (DLQ, SNS fan-out, Step Functions, Saga) are **roadmap, marked as such** |
| **[mock-bff](https://github.com/EduardooPV/mock-bff)** | How do you unblock front-end work when the BFF does not exist yet? | Vue, Node.js, Express | Configurable mock BFF with editable routes, payloads and latency |

Phase status is always explicit: ✅ done · 🚧 in progress · ⬜ planned.

## Experience in one paragraph

**Warren Investimentos** — Fullstack Software Engineer (Nov/2024 → now). Investment platform: onboarding, compliance, CVM 210 portability, WaaS and internal backoffice tooling. Vue + Node.js/NestJS BFF + .NET microservices, with automated tests (Playwright, Cypress, Vitest), CI/CD on GitHub Actions and observability on Datadog/Grafana.

**Monks** — Front-end Engineer (Jul/2021 → Nov/2024), from intern to mid-level. React, Next.js, TypeScript and Headless CMS for national and international clients; reusable component libraries with Storybook distributed as internal packages; technical SEO, accessibility and web performance work.

## Stack

**Frontend** — TypeScript · JavaScript · React · Next.js · Vue · Storybook · Design Systems · Micro frontends · Web performance · Accessibility

**Backend** — Node.js · NestJS · .NET 8 / C# · REST APIs · BFF · Microservices

**Data & messaging** — PostgreSQL · Prisma · Redis · RabbitMQ

**Cloud & DevOps** — AWS · Docker · Terraform · GitHub Actions · CI/CD · Kubernetes (manifests, local `kind` cluster)

**Quality & observability** — Jest · Vitest · Cypress · Playwright · Prometheus · Grafana · Datadog

**Auth** — OAuth2 / OIDC · Keycloak · JWT · RBAC

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="34" alt="typescript" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="34" alt="nodejs" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="34" alt="nestjs" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" height="34" alt="dotnet" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" height="34" alt="vue" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="34" alt="react" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="34" alt="nextjs" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="34" alt="postgresql" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="34" alt="redis" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rabbitmq/rabbitmq-original.svg" height="34" alt="rabbitmq" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="34" alt="docker" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="34" alt="kubernetes" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" height="34" alt="terraform" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="34" alt="aws" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" height="34" alt="github actions" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/grafana/grafana-original.svg" height="34" alt="grafana" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/datadog/datadog-original.svg" height="34" alt="datadog" />
  <img width="10" />
  <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/playwright.png" height="34" alt="playwright" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitest/vitest-original.svg" height="34" alt="vitest" />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/storybook/storybook-original.svg" height="34" alt="storybook" />
</div>

## Currently

Closing the queues and observability phases of `corretora-investimentos`, and writing about what changes in day-to-day engineering when the requirement comes from a regulator instead of a PM.

Open to fullstack / backend roles in fintech and product companies (Brazil, remote or São Paulo).

---

<details>
<summary><b>Versão em português</b></summary>

<br/>

Sou **Software Engineer fullstack** e trabalho com **produtos financeiros regulados** na **Warren Investimentos**: cadastro, compliance, portabilidade de investimentos (CVM 210), WaaS e ferramentas internas de backoffice. Vue no front, Node.js/NestJS como BFF e .NET nos microsserviços, com testes automatizados (Playwright, Cypress, Vitest), CI/CD e observabilidade (Datadog, Grafana).

Antes disso passei 3 anos na **Monks**, de estagiário a pleno, construindo aplicações React/Next.js com Headless CMS, bibliotecas de componentes com Storybook, SEO técnico, acessibilidade e performance web para clientes nacionais e internacionais.

Os repositórios acima são laboratórios com um objetivo por vez: cada um responde a uma pergunta técnica concreta e o README explica **problema → decisão → trade-off**, com o status de cada fase marcado explicitamente.

- 💼 [LinkedIn](https://www.linkedin.com/in/luiz-veltroni/)
- ✉️ eduardoveltroni@hotmail.com

</details>
