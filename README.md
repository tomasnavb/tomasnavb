# Tomás Navarro
### Cloud Infrastructure Engineer

Infrastructure-focused engineer with 2.5 years of experience 
managing Linux servers, PostgreSQL databases, and real-time 
IoT data pipelines in production. Designing and deploying 
production-grade cloud infrastructure on GCP using Terraform, 
HCP Terraform, and Cloud Build — with a focus on multi-environment 
isolation, least-privilege IAM, and zero static credentials.

📍 France → Open to Remote globally  
📧 tomasnavarro.dev@gmail.com

---

## 🏗️ Projects

### [GCP Excel Processing Pipeline — GKE Platform](https://github.com/tomasnavb/excel-processing-pipeline-gke)
*Active development — Sep 2026–present*

- GCP Organization with 4 isolated Folders and Projects (bootstrap / development / production / shared)
- HCP Terraform managing 11 workspaces across dev/prod/shared/mgmt via `for_each`
- Workload Identity Federation across all environments — no static service account keys
- Networking (VPC, subnets) implemented for dev and prod

**Next:** GKE cluster, Cloud Run API, Pub/Sub worker, Firestore

---

### [GCP Production-Grade Infrastructure](https://github.com/tomasnavb/gcp-wordpress-blueprint)
*Feb 2026–present*

- Two isolated VPCs (prod + management) with no public IPs
- Regional MIG with auto-healing across 3 zones + HTTP Load Balancer
- Cloud SQL with private IP only — IAP-only SSH, no bastion host
- Secret Manager with least-privilege service accounts per workload
- Dual backup strategy via Cloud Functions + Cloud Scheduler
- Immutable deployments from Packer golden images
- Cloud Build CI/CD with plan/apply separation and destructive change protection

---

## 🛠️ Tech Stack

**Cloud & IaC**  
`GCP` `Terraform` `HCP Terraform` `Workload Identity Federation`
`Cloud Identity` `Cloud Build` `Cloud SQL` `Cloud Functions`
`Cloud NAT` `IAP` `Secret Manager` `Packer` `Cloud Storage`

**Systems & Networking**  
`Linux / Ubuntu` `VPC` `Firewalls` `Networking` `Bash`

**Data & Observability**  
`PostgreSQL` `MongoDB` `Grafana`

**Automation & Dev**  
`Python` `Flask` `REST APIs` `Git` `Docker`

---

## 🏅 Certifications

- **HashiCorp Certified: Terraform Associate (004)** — HashiCorp, Aug 2026 [Verify](https://www.credly.com/badges/71b756d9-f4b8-41b0-96ba-1c938ac7f14c/public_url)
- **Google Associate Cloud Engineer** — Google Cloud, Jun 2026 · [Verify](https://www.credly.com/badges/d5fb3178-7fdd-4a2f-8232-2607c6dc6aac)
- **EF SET English Certificate — C1 Advanced** (70/100)

---

## 💼 Experience

**IoT Infrastructure Engineer — Efficact** *(Oct 2022 – May 2025)*  
Sole infrastructure engineer for a 3-server Linux environment 
supporting ~400 industrial devices across 6-8 client deployments. 
Administered production PostgreSQL databases, built Grafana 
dashboards, developed a Python/Flask REST API for real-time 
industrial KPIs, and owned day-to-day incident response.

**Independent IT Consultant** *(May 2025 – Present)*  
Built a Python/MongoDB desktop application (PyQt5) that reduced 
a ~20-hour manual segmentation process to under 20 minutes 
across 16 recurring publishers.

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tomasnav-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/tomasnav)
[![Email](https://img.shields.io/badge/Email-tomasnavarro.dev%40gmail.com-D14836?style=flat&logo=gmail)](mailto:tomasnavarro.dev@gmail.com)
