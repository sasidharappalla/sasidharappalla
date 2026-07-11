<div align="center">

# Sasidhar Appalla

**Software Engineer · Data Engineer**

Building reliable backend systems, event-driven platforms, and data-intensive applications.

MS Computer Science @ NC State University

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sasidhar-appalla/)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:pappall@ncsu.edu)

</div>

---

## About

I build backend and data platforms with a focus on distributed systems, cloud infrastructure, event-driven workflows, and applied GenAI. My work spans API design, messaging and streaming, storage, observability, deployment automation, and evaluation tooling.

My background includes clinical-data pipelines that processed **100K+ records per day**. I am currently pursuing an MS in Computer Science at NC State and exploring software engineering and data engineering opportunities where reliability and clear system design matter.

## Selected Engineering Work

### [LabFlow](https://github.com/sasidharappalla/labflow) · Event-Driven Research Platform

`TypeScript` `Kafka` `PostgreSQL` `Redis` `Airflow` `Prometheus`

Processes research experiment events through three services with idempotent consumers, bounded retries, persisted dead-letter queues, operator-controlled replay, and write-through caching. PostgreSQL remains the source of truth; Airflow is deliberately limited to scheduled reconciliation and recovery workflows.

**Inspect:** [architecture](https://github.com/sasidharappalla/labflow/blob/main/docs/architecture.md) · [API](https://github.com/sasidharappalla/labflow/blob/main/docs/api.md) · [nine design decisions](https://github.com/sasidharappalla/labflow/blob/main/docs/decisions.md) · [tests and CI](https://github.com/sasidharappalla/labflow/blob/main/.github/workflows/ci.yml)

### [DocuQuery](https://github.com/sasidharappalla/rag-qa-system) · RAG Platform Deployment

`Python` `FastAPI` `ChromaDB` `Docker` `Terraform` `Kubernetes` `Helm`

Combines PDF ingestion, retrieval, pluggable LLM providers, evaluation, and Prometheus instrumentation with a repeatable platform layer. The repository includes a non-root container, Terraform for Azure AKS, a Helm chart, GitLab CI validation, Kubernetes probes and resource controls, structured logging, and a deterministic demo mode that does not require a paid model key.

**Inspect:** [implementation notes](https://github.com/sasidharappalla/rag-qa-system/blob/main/IMPLEMENTATION.md) · [Terraform](https://github.com/sasidharappalla/rag-qa-system/tree/main/infra) · [Helm chart](https://github.com/sasidharappalla/rag-qa-system/tree/main/helm/docuquery) · [CI pipeline](https://github.com/sasidharappalla/rag-qa-system/blob/main/.gitlab-ci.yml) · [tests](https://github.com/sasidharappalla/rag-qa-system/tree/main/tests)

### [AuraNet](https://github.com/sasidharappalla/auranet) · Distributed Social Platform

`Python` `FastAPI` `Next.js` `PostgreSQL` `RabbitMQ` `MinIO`

A full-stack social platform with 39 API operations across 12 FastAPI routers, plus a health endpoint. It includes JWT authentication, community and voting workflows, a RabbitMQ-backed image-processing worker, PostgreSQL persistence, MinIO object storage, and a containerized Next.js frontend. Developed as a personal, AI-assisted portfolio project.

**Inspect:** [API composition](https://github.com/sasidharappalla/auranet/blob/main/backend/app/main.py) · [tests](https://github.com/sasidharappalla/auranet/tree/main/backend/tests) · [CI](https://github.com/sasidharappalla/auranet/blob/main/.github/workflows/ci.yml) · [container stack](https://github.com/sasidharappalla/auranet/blob/main/docker-compose.yml) · [load scenario](https://github.com/sasidharappalla/auranet/blob/main/benchmarks/load.js)

**Reported project results:** sub-200 ms p95 API latency, 1,000+ concurrent users, and 99%+ uptime.

## Additional Work

- **[S3Lite](https://github.com/sasidharappalla/s3lite)** · Personal object-storage project implementing bucket and object operations, API-key authentication, HMAC presigned URLs, SHA-256 integrity checks, PostgreSQL metadata, and MinIO persistence. **Reported result:** 1,000+ concurrent operations. [API](https://github.com/sasidharappalla/s3lite/blob/main/app/main.py) · [tests](https://github.com/sasidharappalla/s3lite/tree/main/tests) · [CI](https://github.com/sasidharappalla/s3lite/blob/main/.github/workflows/ci.yml) · [load scenario](https://github.com/sasidharappalla/s3lite/blob/main/benchmarks/load.js)

- **[BurnOut Wellness App](https://github.com/sasidharappalla/BurnOut_FitnessApp)** · Team project built with Flask and MongoDB for activity logging, calorie tracking, goals, and social accountability. **Project-reported outcomes:** 50+ beta users, 80% weekly retention, and a 45% engagement increase.

- **LLM Procedural Content Generation** · Research project comparing Phi-3, Gemma-2, and Qwen-2.5 with a ViT-based evaluation harness. **Project-reported results:** 100% structural stability and 97% accuracy across the evaluated architectures.

## Core Stack

| Area | Technologies |
| --- | --- |
| Languages | Python, TypeScript, Go, Java, C++, SQL |
| Backend | FastAPI, Express, Node.js, SQLAlchemy, Prisma |
| Data and messaging | PostgreSQL, Redis, Kafka, RabbitMQ, MinIO, ChromaDB |
| Platform | Docker, Kubernetes, Terraform, Helm, Azure AKS |
| Delivery and observability | GitHub Actions, GitLab CI, Prometheus, Grafana, structured logging |

---

<div align="center">

Open to software engineering and data engineering opportunities.

[LinkedIn](https://www.linkedin.com/in/sasidhar-appalla/) · [Email](mailto:pappall@ncsu.edu)

</div>
