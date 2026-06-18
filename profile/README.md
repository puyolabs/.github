## PuyoLabs

Production-grade personal engineering — products built to be *shown*, not just described.

### Featured

**[janus](https://github.com/puyolabs/janus)** — single-host edge gateway: one Caddy fronts `:80/:443` and routes by Host header to each project.
Two faces (LAN via local-CA TLS, public via a gated tunnel profile that's off by default), per-ecosystem Docker network isolation, and push-to-deploy where projects self-register their routes. Apache-2.0.

**[kairos-llm-scorer](https://github.com/puyolabs/kairos-llm-scorer)** — LLM job-fit scoring service extracted from Kairos.
Structured output (forced tool-use), an eval harness (97.1% decision agreement vs a 65.7% deterministic baseline), and deploy IaC (Terraform ECR/Fargate/ALB + a Kubernetes manifest). Validated end-to-end against real AWS.

### Stack

PHP/Symfony · TypeScript (Angular/React) · Python/FastAPI · PostgreSQL + pgvector · Anthropic SDK · Caddy · Docker · Terraform · AWS

---

Maintained by **Moisés Puyosa** — Senior Software Engineer, full-stack PHP/TS + shipped applied-AI. Remote, GMT-5.
[LinkedIn](https://www.linkedin.com/in/mpuyosa91)
