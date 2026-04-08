# Wilfred Ballo

**Cloud Engineer · GCP · Terraform · Go · Python**

I build production-grade cloud infrastructure on Google Cloud — security automation, governance tooling, FinOps, and GitOps delivery pipelines. Every project here solves a real operational problem and ships with tests.

> 🔨 Currently building: **[CloudGuard](https://github.com/wilfb-debug/cloudguard-gcp-governance)** — automated GCP governance platform with real-time security, cost, and compliance scanning.

---

## Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | GCP — Cloud Run · GKE · BigQuery · Cloud SQL · Cloud Asset Inventory · IAP · Artifact Registry |
| **IaC** | Terraform · Kustomize |
| **Languages** | Python · Go · HCL |
| **CI/CD** | GitHub Actions · Cloud Build · ArgoCD |
| **Containers** | Docker · Kubernetes |

---

## Featured Projects

### 🔒 Security & Governance

**[CloudGuard GCP Governance](https://github.com/wilfb-debug/cloudguard-gcp-governance)**
[![CI](https://github.com/wilfb-debug/cloudguard-gcp-governance/actions/workflows/ci.yml/badge.svg)](https://github.com/wilfb-debug/cloudguard-gcp-governance/actions/workflows/ci.yml)
![Tests](https://img.shields.io/badge/tests-41_passing-brightgreen)

Serverless governance platform that scans GCP resources for misconfigurations, cost risks, and compliance violations. REST API with severity/category filtering, BigQuery persistence, and Looker Studio dashboarding. 4 active security/cost/governance checks — expandable rule engine.

`Python` `Cloud Run` `BigQuery` `Cloud Asset Inventory` `Terraform`

---

### 💰 FinOps

**[SpendSentinel GCP Autopilot](https://github.com/wilfb-debug/spend-sentinel-gcp-autopilot)**

Automated FinOps platform that continuously detects idle and oversized cloud resources, surfaces cost risks to BigQuery, and enforces cleanup policies via Cloud Run. Reduces cloud waste through scheduled detection and enforcement workflows.

`Python` `Cloud Run` `Cloud Scheduler` `BigQuery` `FinOps`

---

### 🏗️ Infrastructure & Networking

**[Identity-First Zero-Trust Network](https://github.com/wilfb-debug/gcp-identity-first-network-terraform)**
[![CI](https://github.com/wilfb-debug/gcp-identity-first-network-terraform/actions/workflows/ci.yml/badge.svg)](https://github.com/wilfb-debug/gcp-identity-first-network-terraform/actions/workflows/ci.yml)

Zero public IPs — access enforced entirely through IAM and Identity-Aware Proxy. Terraform-managed VPC with deny-all ingress baseline. Demonstrates identity-over-network security design with automated linting and security scanning (tflint + tfsec).

`Terraform` `IAP` `VPC` `tflint` `tfsec`

**[Secure Cloud Run API](https://github.com/wilfb-debug/gcp-secure-cloudrun-api)**
[![CI](https://github.com/wilfb-debug/gcp-secure-cloudrun-api/actions/workflows/ci.yml/badge.svg)](https://github.com/wilfb-debug/gcp-secure-cloudrun-api/actions/workflows/ci.yml)

Secure-by-default Flask API with 4-stage modular Terraform (bootstrap → foundation → cloudrun → IAM) and full GitHub Actions CI/CD. No public access — IAM token required for every invocation.

`Python` `Terraform` `Cloud Run` `GitHub Actions`

---

### ⚙️ Platform Engineering

**[Zero-Downtime GitOps Platform](https://github.com/wilfb-debug/gcp-zero-downtime-gitops-platform)**

Multi-environment GitOps delivery on GKE — ArgoCD + Kustomize overlays for dev and staging. Declarative workload promotion with automated reconciliation and zero-downtime deployments.

`GKE` `ArgoCD` `Kustomize` `Kubernetes`

**[CreatorStore Lite](https://github.com/wilfb-debug/creatorstore-lite-gcp)**
[![CI](https://github.com/wilfb-debug/creatorstore-lite-gcp/actions/workflows/ci.yml/badge.svg)](https://github.com/wilfb-debug/creatorstore-lite-gcp/actions/workflows/ci.yml)
![Tests](https://img.shields.io/badge/tests-14_passing-brightgreen)

Production-pattern Go REST API with PostgreSQL — repository interface, connection pooling, input validation, and 14 table-driven tests with `-race` flag. Docker Compose local dev → Cloud Run + Cloud SQL production deployment path.

`Go` `PostgreSQL` `Docker` `Cloud Run` `GitHub Actions`

---

## Architecture Principles

- **Security by default** — private networks, IAM least-privilege, no public exposure without intent
- **Everything as code** — infrastructure, policy, and configuration managed in Git
- **FinOps-aware** — cost visibility and governance built into architecture decisions from day one
- **Tested before shipped** — unit tests, CI pipelines, and coverage gates on every active project

---

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=wilfb-debug&show_icons=true&hide_border=true&count_private=true&theme=default)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=wilfb-debug&layout=compact&hide_border=true&theme=default)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/wilfred-ballo-21b300119)
[![GitHub](https://img.shields.io/badge/GitHub-wilfb--debug-181717?style=flat&logo=github)](https://github.com/wilfb-debug)
