# Wilfred Ballo

**Cloud Engineer · GCP · Terraform · Go · Python**

I build production-grade cloud infrastructure on Google Cloud — focused on security automation, governance tooling, FinOps, and GitOps delivery pipelines. Every project here solves a real operational problem.

> Currently building: **[CloudGuard](https://github.com/wilfb-debug/cloudguard-gcp-governance)** — automated GCP resource governance with real-time security and cost scanning.

---

## Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | GCP — Cloud Run, GKE, BigQuery, Cloud SQL, Cloud Asset Inventory, IAP, Artifact Registry |
| **IaC** | Terraform, Kustomize |
| **Languages** | Python, Go, HCL |
| **CI/CD** | GitHub Actions, Cloud Build, ArgoCD |
| **Containers** | Docker, Kubernetes |

---

## Featured Projects

### Security & Governance
**[CloudGuard GCP Governance](https://github.com/wilfb-debug/cloudguard-gcp-governance)**
Scans GCP resources for misconfigurations, cost risks, and compliance violations using Cloud Asset Inventory. Writes findings to BigQuery and surfaces them via Looker Studio.
`Python` `Cloud Run` `BigQuery` `Cloud Asset Inventory` `Terraform`

---

### FinOps
**[SpendSentinel GCP Autopilot](https://github.com/wilfb-debug/spend-sentinel-gcp-autopilot)**
Automated FinOps platform that detects idle and oversized cloud resources, surfaces cost risks to BigQuery, and enforces cleanup policies via Cloud Run services.
`Python` `Cloud Run` `Cloud Scheduler` `BigQuery` `FinOps`

---

### Infrastructure & Networking
**[Identity-First Zero-Trust Network](https://github.com/wilfb-debug/gcp-identity-first-network-terraform)**
Private GCP network with zero public IPs — access enforced entirely through IAM and Identity-Aware Proxy. Demonstrates least-privilege, identity-over-network security design.
`Terraform` `IAP` `VPC` `Cloud Logging`

**[Secure Cloud Run API](https://github.com/wilfb-debug/gcp-secure-cloudrun-api)**
Secure-by-default Flask API on Cloud Run with 4-stage modular Terraform (bootstrap → foundation → cloudrun → IAM) and full GitHub Actions CI/CD pipeline.
`Python` `Terraform` `Cloud Run` `GitHub Actions`

---

### Platform Engineering
**[Zero-Downtime GitOps Platform](https://github.com/wilfb-debug/gcp-zero-downtime-gitops-platform)**
Multi-environment GitOps delivery on GKE using ArgoCD and Kustomize overlays. Automated reconciliation with zero-downtime workload promotion across dev and staging.
`GKE` `ArgoCD` `Kustomize` `Kubernetes`

**[CreatorStore Lite](https://github.com/wilfb-debug/creatorstore-lite-gcp)**
Containerised Go e-commerce backend with PostgreSQL, designed for local Docker Compose development and Cloud Run + Cloud SQL production deployment.
`Go` `PostgreSQL` `Docker` `Cloud Run`

---

## Architecture Principles

- **Security by default** — private networks, IAM least-privilege, no public exposure without intent
- **Everything as code** — infrastructure, policy, and configuration managed in Git
- **FinOps-aware** — cost visibility and governance built into architecture decisions from day one
- **Operable, not just deployable** — systems designed to be understood and maintained in production

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/wilfredballo)
[![GitHub](https://img.shields.io/badge/GitHub-wilfb--debug-181717?style=flat&logo=github)](https://github.com/wilfb-debug)

