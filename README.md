# Hi, I'm Antonio Bermúdez 👋

**Software engineer. I design systems and ship products, and I pick the stack for the problem, not the other way around.**

Lately that means event-driven backends, AI agents that do real work, and running my own infrastructure at home before anything reaches production.

[Blog](https://antoniobermudez.dev) · [Newsletter](https://antoniobermudez.dev/en/newsletter/) · [LinkedIn](https://www.linkedin.com/in/antoniobermudezr/)

---

## What I'm building

### [Tempoo Analytics](https://tempooanalytics.eu)
A privacy-first, GDPR-compliant alternative to Google Analytics. A 2 KB tracking script, no cookies, and near real-time dashboards powered by an event-driven pipeline with queues. Next up: a public API and an MCP server so AI agents can query your analytics directly.

### [relay-mcp](https://github.com/TempooDev/relay-mcp)
An MCP server that lets your AI agents hand work to other models. Claude Code, Gemini CLI and any MCP client share one task queue that routes each job by tier (`local`, `light`, `heavy`, `max`) to Ollama, any OpenAI-compatible API or a CLI. Premium tokens go where they matter, and sensitive work can stay on your machine.

### [Asistente Ayuntamiento](https://github.com/TempooDev/asistente-ayuntamiento)
A RAG assistant for citizens of a local council. A Go scraper ingests official bulletins (BOE, BOJA…), a worker indexes them in pgvector through RabbitMQ, and an Angular front end answers questions with sources, backed by an evaluation suite.

### [antoniobermudez.dev](https://antoniobermudez.dev)
My bilingual blog (ES/EN) about architecture, AI, infrastructure, product and the craft of building software. Static site with a headless CMS, build-time generated covers, a comments API and a weekly AI and tech newsletter.

### Homelab
Proxmox, ephemeral VMs with Terraform, local LLMs and Grafana. It's where I stress-test my own products and try new models before trusting them with real work.

---

## Other projects

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [EMMA](https://github.com/TempooDev/EMMA) | Distributed platform to monitor and optimize energy assets with real-time European market data | .NET, Python, MQTT/Kafka, TimescaleDB, React |
| [IoT-Grid](https://github.com/TempooDev/IoTGrid) | Polyglot real-time telemetry pipeline, each service in the language that fits it | Go, .NET, Bun + TypeScript, Redis, PostgreSQL |
| [ReformaOS](https://github.com/TempooDev/ReformaOS) | Full-stack app to manage home renovations, mortgages and rentals | Go, Angular, PostgreSQL, MinIO |
| [BlazorSignalStore](https://github.com/TempooDev/BlazorSignalStore) | Reactive state management for Blazor inspired by Angular Signals | C# |

---

## How I work

- **Architecture first:** event-driven systems, vertical slices, queues and observability from day one.
- **AI as part of the system:** RAG, agents and MCP servers, with evaluation and a clear line between what runs locally and what goes to the cloud.
- **Polyglot by choice:** Go, TypeScript, Angular, .NET and Python, picked per service.
- **Own the infrastructure:** Docker, Terraform, self-hosted services and load tests before launch.

Always happy to talk about architecture, AI agents or a product idea. Reach me on [LinkedIn](https://www.linkedin.com/in/antoniobermudezr/).
