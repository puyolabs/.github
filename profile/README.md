## PuyoLabs

Production-grade personal engineering — products built to be *shown*, not just described.

### Featured

**[janus](https://github.com/puyolabs/janus)** — single-host edge gateway: one Caddy fronts `:80/:443` and routes by Host header to each project.
Two faces (LAN via local-CA TLS, public via a gated tunnel profile that's off by default), per-ecosystem Docker network isolation, and push-to-deploy where projects self-register their routes. Apache-2.0.

**[kairos-llm-scorer](https://github.com/puyolabs/kairos-llm-scorer)** — LLM job-fit scoring service extracted from Kairos.
Structured output (forced tool-use), an eval harness (97.1% decision agreement vs a 65.7% deterministic baseline), and deploy IaC (Terraform ECR/Fargate/ALB + a Kubernetes manifest). Validated end-to-end against real AWS.

**[argus](https://github.com/puyolabs/argus)** — Next.js (App Router) frontend for the screening loop: findings list → verdict detail → decision → enqueue re-score.
Passwordless Google sign-in over a stateless encrypted-cookie session (no database — the backend stays the single source of truth), a BFF boundary that keeps the backend host and service tokens server-side, TanStack Query caching, light/dark theming, i18n, and design-first RFCs. Apache-2.0.

### Stack

PHP/Symfony · TypeScript (Angular/React) · Python/FastAPI · PostgreSQL + pgvector · Anthropic SDK · Caddy · Docker · Terraform · AWS

---

Maintained by **Moisés Puyosa** — Senior Software Engineer, full-stack PHP/TS + shipped applied-AI. Remote, GMT-5.
[LinkedIn](https://www.linkedin.com/in/mpuyosa91)
