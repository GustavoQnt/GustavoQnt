<h1 align="center">Oi, eu sou o Gustavo 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=38BDF8&center=true&vCenter=true&width=900&lines=Construindo+sistemas+resilientes+e+escal%C3%A1veis;Retry%2C+idempot%C3%AAncia%2C+outbox%2C+deduplication;Bibliotecas+open+source+para+problemas+reais" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/GustavoQnt?tab=followers">
    <img alt="Followers" src="https://img.shields.io/github/followers/GustavoQnt?style=for-the-badge&color=0ea5e9" />
  </a>
  <a href="https://github.com/GustavoQnt?tab=repositories">
    <img alt="Repos" src="https://img.shields.io/badge/Reposit%C3%B3rios-GitHub-111827?style=for-the-badge&logo=github" />
  </a>
  <img alt="Profile views" src="https://komarev.com/ghpvc/?username=GustavoQnt&style=for-the-badge&color=0ea5e9" />
</p>

---

## 🚀 Sobre mim

Desenvolvedor focado em **resiliência, confiabilidade e performance** de sistemas distribuídos. Construo bibliotecas open source que resolvem problemas reais de infraestrutura — desde **caching com TTL e LRU eviction**, passando por **idempotência e deduplicação de requests**, até **entrega confiável de webhooks com retry e HMAC signing**.

Meus projetos são ferramentas de produção: zero dependências desnecessárias, benchmarks comparativos, e testes cobrindo edge cases. Acredito que conceitos como **idempotency keys**, **stale-while-revalidate**, **outbox pattern** e **retry com backoff** não deveriam ser reimplementados do zero em cada projeto — por isso crio libs reutilizáveis para esses padrões.

- 🔁 **Retry & Resiliência** — entrega garantida com backoff e reprocessamento
- 🔑 **Idempotência** — deduplicação de requests e cache de respostas com TTL
- 📬 **Webhook delivery** — HMAC signing, event tracking, entrega confiável
- ⚡ **Caching** — TTL + LRU + SWR com O(1) lookup e zero deps
- 🧱 **Arquitetura** — DDD, Clean Architecture, sistemas modulares

---

## 🛠️ Stack

**Languages & Runtime**
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,cs,rust,java&perline=6" />
</p>

**Backend & APIs**
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,fastify,express,spring,dotnet&perline=6" />
</p>

**Frontend**
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,angular,tailwind&perline=4" />
</p>

**Databases & Cache**
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,sqlite&perline=5" />
</p>

**DevOps & Cloud**
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,aws,git,github&perline=6" />
</p>

---

## 📊 Estatísticas & Contribuições

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=GustavoQnt&show_icons=true&theme=tokyonight&rank_icon=github&include_all_commits=true&locale=pt-br" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GustavoQnt&layout=compact&theme=tokyonight&langs_count=8" />
</p>

<p align="center">
  <img height="170" src="https://streak-stats.demolab.com?user=GustavoQnt&theme=tokyonight&locale=pt_BR" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://ghchart.rshah.org/7c3aed/GustavoQnt" />
    <source media="(prefers-color-scheme: light)" srcset="https://ghchart.rshah.org/6d28d9/GustavoQnt" />
    <img alt="GitHub Contribution Graph" src="https://ghchart.rshah.org/7c3aed/GustavoQnt" />
  </picture>
</p>

---

## 💡 Core Skills

| Categoria | Skills |
|-----------|--------|
| **Backend & APIs** | NestJS (DI, Guards, Interceptors), Fastify, Express, Node.js, ASP.NET Core, gRPC, RESTful APIs, WebSockets (Socket.IO), Microservices |
| **Databases** | PostgreSQL, MySQL, MongoDB, MS SQL Server, Redis (caching, distributed locks, sessions), SQLite |
| **ORMs & Migrations** | Prisma, TypeORM, Drizzle, Entity Framework Core, NHibernate, Alembic |
| **Async & Scaling** | BullMQ + Redis (background jobs, DLQ, retries), Bull Board, event-driven architecture, distributed locks, single-flight pattern |
| **Cloud & Infrastructure** | AWS (Lambda, EC2, S3, CloudFront, SQS, Cognito), Docker, Kubernetes, Terraform, CI/CD |
| **Reliability** | State machines, circuit breakers, **idempotency**, **retry logic with backoff**, health checks, request deduplication |
| **Auth & Security** | JWT, Clerk, AWS Cognito, OAuth, HMAC signing |
| **Observability** | ELK Stack, structured logging, event tracking, SonarQube, alerting |
| **Integrations** | Stripe, Twilio, Firebase, Google Vision, FFmpeg |
| **Practices** | TDD, BDD, SOLID, Clean Architecture, Git workflows |

---

---

## 📌 Projetos em destaque

### 🔑 [idempotency-kit](https://github.com/GustavoQnt/idempotency-kit)
**Idempotência para Node.js** | TypeScript
Toolkit de idempotência com **deduplicação de requests in-flight** e **cache de respostas com TTL**. Evita reprocessamento de operações duplicadas em APIs — basta um idempotency key. ⭐ Request deduplication • TTL caching • Promise memoization

---

### ⚡ [swr-lru-cache](https://github.com/GustavoQnt/swr-lru-cache)
**Cache in-memory com TTL + LRU + SWR** | TypeScript
Cache com **LRU eviction**, **TTL expiration**, **stale-while-revalidate** e **request deduplication**. Zero dependências, O(1) lookup, event emitter para observabilidade. ⭐ SWR pattern • LRU eviction • Zero deps

---

### 📬 [hooksmith](https://github.com/GustavoQnt/hooksmith)
**Webhook delivery engine** | Rust
Sistema de **entrega de webhooks** com **retry**, **HMAC signing**, **idempotência** e **event tracking**. Construído com Axum + Tokio + SQLite para performance e confiabilidade. ⭐ Async delivery • HMAC signing • Event sourcing

---

### 🧱 [blockchain](https://github.com/GustavoQnt/blockchain)
**Blockchain Implementation** | C# / .NET 8
Implementação modular de blockchain com **SHA256 hashing**, **Merkle tree**, **validação de transações**, **mempool** e **mining**. Clean Architecture com API REST, CLI e testes unitários. ⭐ DDD • Clean Architecture • Comprehensive tests

---

## 🌐 Contato

<p align="center">
  <a href="mailto:gstvquintela@gmail.com">
    <img src="https://img.shields.io/badge/Email-0ea5e9?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/gustavo-quintela-75b9853b1/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>


