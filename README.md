# Tomás Navarro
### Cloud Infrastructure / DevOps Engineer

Infrastructure-focused engineer with 2.5 years of experience operating production Linux infrastructure for industrial IoT workloads supporting ~400 devices.

Currently specializing in Google Cloud Platform and Infrastructure as Code, designing and deploying cloud infrastructure using Terraform, HCP Terraform, Packer, and Cloud Build. Focused on cloud networking, IAM, security, automation, and Kubernetes.

📍 Rosario, Argentina · Open to Remote  
📧 tomasnavarro.dev@gmail.com

---

## 🏗️ Projects

### [GCP Infrastructure — WordPress Blueprint](https://github.com/tomasnavb/gcp-wordpress-blueprint)
*Completed · Feb 2026 – Nov 2026*

Designed and deployed a complete GCP infrastructure for a highly available WordPress workload.

- Single VPC architecture with dedicated web and image-build subnets
- Regional Managed Instance Group with auto-healing across 3 zones
- Regional HA Cloud SQL with private IP connectivity
- Global HTTPS Load Balancer, Cloud CDN, and Cloud Armor security controls
- IAP-gated administrative access and hardened network exposure
- Terraform infrastructure provisioning with separate plan, apply, and image-build service accounts
- Packer golden images and Cloud Build CI/CD pipeline
- Automated security validation, destructive-change protection, and dependency integrity checks
- Tested Cloud SQL HA failover and point-in-time recovery; observed 10–21 seconds of downtime during failover tests

### [GCP Excel Processing Pipeline — GKE Platform](https://github.com/tomasnavb/excel-processing-pipeline-gke)
*Active development · Sep 2026 – Present*

Building a cloud-native GCP platform foundation for an Excel processing workload.

- GCP Organization hierarchy with isolated bootstrap, development, production, and shared folders
- Separate seed, development, and production projects
- HCP Terraform workspace provisioning through reusable `for_each` configuration
- Workload Identity Federation for GitHub integration — no static service account keys
- Cloud Identity groups and project-level IAM access management
- Private GKE Autopilot cluster provisioned through a reusable Terraform module
- Dedicated node service account and Cloud NAT for private outbound connectivity
- KEDA installed via Helm; workload integration and autoscaling configuration in progress
- GitHub Actions CI for Terraform formatting, validation, and TFLint

---

## 🛠️ Tech Stack

**Cloud & Infrastructure as Code**  
`GCP` `Terraform` `HCP Terraform` `Packer` `GKE Autopilot`

**Networking & Security**  
`VPC` `Cloud NAT` `Cloud Load Balancing` `Cloud CDN` `Cloud Armor` `IAP` `IAM` `Workload Identity Federation` `Secret Manager`

**CI/CD & Automation**  
`Cloud Build` `GitHub Actions` `Python` `Bash` `Git`

**Systems & Observability**  
`Linux / Ubuntu` `PostgreSQL` `Grafana` `Cloud Monitoring` `Cloud Logging`

**Containers & Data**  
`Docker` `Docker Compose` `Kubernetes` `KEDA` `Kafka` `NiFi` `Cassandra` `Node-RED` `MongoDB`

---

## 🏅 Certifications

- **Google Associate Cloud Engineer** — Google Cloud, Jun 2026 · [Verify](https://www.credly.com/badges/d5fb3178-7fdd-4a2f-8232-2607c6dc6aac)
- **HashiCorp Certified: Terraform Associate (004)** — HashiCorp, Aug 2026 · [Verify](https://www.credly.com/badges/71b756d9-f4b8-41b0-96ba-1c938ac7f14c/public_url)
- **Certified Kubernetes Administrator (CKA)** — In progress
- **EF SET English Certificate — C1 Advanced** (70/100)

---

## 💼 Experience

**IoT Infrastructure Engineer — Efficast S.A.**  
*Oct 2022 – May 2025 · Rosario, Argentina*

Sole infrastructure engineer responsible for a 3-server Linux environment hosted on DonWeb Cloud, supporting a production industrial IoT platform with approximately 400 devices across 6–8 client deployments.

- Administered production PostgreSQL databases handling continuous IoT telemetry.
- Built Grafana dashboards for real-time monitoring and infrastructure health.
- Owned day-to-day infrastructure monitoring, troubleshooting, and incident response.
- Developed a Python/Flask REST API calculating four industrial KPIs: OEE, availability, performance, and quality.

**Independent IT Consultant**  
*May 2025 – Present · Remote*

- Developed a Python/MongoDB desktop application using PyQt5 that reduced a spreadsheet segmentation process from approximately 20 hours of manual work to under 20 minutes across 16 recurring publishers.

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tomasnav-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/tomasnav)
[![Email](https://img.shields.io/badge/Email-tomasnavarro.dev%40gmail.com-D14836?style=flat&logo=gmail)](mailto:tomasnavarro.dev@gmail.com)
