# Yengner Bermudez

**Backend & Infrastructure Engineer** · Former Citi Technology Summer Analyst · Founder of DeepVisor

I build backend services, data pipelines, and the infrastructure that runs them. I'm finishing my computer science degree at the University of South Florida, with graduation expected in December 2026.

[Portfolio](https://yengner.com) · [LinkedIn](https://www.linkedin.com/in/yengner-bermudez) · [Email](mailto:yengnerb475@gmail.com)

## Citi · Technology Summer Analyst, Application Development

**Summer 2026 · Tampa, FL**

- Migrated Java batch workloads for **Oracle Revenue Management and Billing (ORMB)** from legacy Linux VMs to **Red Hat OpenShift**, containerizing the JVM, Perl, and Oracle Client dependencies.
- Implemented a persistent Kubernetes worker Deployment and on-demand batch Jobs. Configured a headless Service and Oracle Coherence Well-Known Addresses (WKA) for discovery across pods.
- Built a seven-stage CI/CD pipeline with **Harness CD, Docker, and Helm** to automate image builds, security scans, publishing, OpenShift deployments, and compliance checks.
- Managed ConfigMaps, Secrets, and shared persistent storage for batch logs. Used **Grafana** and centralized logs to troubleshoot failed runs, and wrote a Bash script to automate batch job submission.

## Projects

### DeepVisor · Founder & Developer

I'm building an account intelligence platform for paid social. It pulls in Meta Ads data, surfaces performance changes, and gives operators a queue of items to review.

- Built asynchronous, idempotent ingestion with pagination, retries, and rate-limit handling.
- Implemented tenant-scoped authorization using Supabase Auth and PostgreSQL row-level security.
- Reduced dashboard load times from 7–9 seconds to about 2.7 seconds with indexing, caching, and precomputed summaries.
- Run Dockerized n8n and PostgreSQL services on Oracle Cloud Infrastructure behind Cloudflare Tunnel.

[Visit DeepVisor](https://www.deepvisor.com)

### EdgeFoundry · Market Data & Backtesting

A Python research project that collects commodity market data, stores it in SQLite, and evaluates paper-trading strategies through repeatable backtests. It includes scheduled Docker jobs, a dashboard, and unit tests for the processing and backtesting logic.

### FloorPlan Project · Computer Vision

A machine learning project for detecting and segmenting architectural elements in floor plan images.

[View the repository](https://github.com/Yengner/FloorPlan-Project)

## Technical skills

| Area | Tools and technologies |
| --- | --- |
| Languages & scripting | Java, Python, TypeScript, JavaScript, SQL, Bash, C# |
| Containers & orchestration | Kubernetes, Red Hat OpenShift, Docker, Docker Compose, Helm |
| Cloud & delivery | Oracle Cloud Infrastructure (OCI), Linux (RHEL and Ubuntu), Harness CD, GitHub Actions, Cloudflare Tunnel, Vercel |
| Backend & data | REST APIs, PostgreSQL, Oracle Database, SQLite, Supabase, Node.js, Next.js, .NET |
| Enterprise platforms & observability | ORMB, Oracle Utilities Application Framework (OUAF), Oracle Coherence, Grafana |
| Messaging | Apache Kafka |

## Community

**Outreach Director, SHPE at USF.** I led external outreach for HackaBull and organized a Citi Tampa office tour for more than 25 members.
