# DevOps Learning Labs

A hands-on portfolio documenting progressive infrastructure and cloud engineering studies across provisioning, containerization, orchestration, and cloud security. Each module contains working configurations, lab notes, and takeaways from real implementation work.

---

## Modules

### [Terraform + AWS](https://github.com/xSnaeRx/learn-terraform-get-started-aws) Infrastructure as Code fundamentals using HashiCorp Terraform with AWS as the cloud provider. Covers resource provisioning, state management, variables, and outputs following the official HashiCorp getting started curriculum.

**Tools & Concepts:** Terraform, AWS (EC2, VPC, S3), HCL, remote state

---

### [Terraform + Docker](https://github.com/xSnaeRx/docker-containers-with-terraform.git) *(in progress)*
Extending Terraform skills to manage containerized workloads using Docker as the provider. Covers image management, container lifecycle, networking, and volume configuration — all provisioned declaratively via Terraform.

**Tools & Concepts:** Terraform, Docker, container networking, image management

---

### [Kubernetes / Helm](https://github.com/xSnaeRx/k8s-security-portfolio.git)
Hands-on Kubernetes cluster management and Helm-based application deployment. Includes deploying stateful workloads, working with namespaces, services, and configmaps, and packaging deployments as Helm charts.

**Tools & Concepts:** Kubernetes, Helm, Deployments, Services, ConfigMaps, StatefulSets, MariaDB


---

### [Cloud Security / Wiz Prep](https://github.com/xSnaeRx/k8s-security-portfolio/blob/8c3e3d1fde8c0813bdebdc57d3931303ef960e64/eks/eks-cluster-games-findings.md)
Applied cloud security concepts mapped to real-world infrastructure. Covers CSPM (Cloud Security Posture Management), CWPP (Cloud Workload Protection Platform), IAM policy analysis, and Kubernetes RBAC in the context of cloud-native security tooling.

**Tools & Concepts:** CSPM, CWPP, IAM, Kubernetes RBAC, Service Accounts, least privilege, attack surface reduction

---

## Stack Overview

| Domain | Tools |
|---|---|
| Infrastructure Provisioning | Terraform, AWS, GCP, Azure |
| Containerization | Docker, containerd |
| Orchestration | Kubernetes, Helm, EKS |
| CI/CD | GitHub Actions, Jenkins |
| Cloud Security | CSPM, CWPP, IAM, RBAC |

---

## About

This repository reflects active, ongoing study with an emphasis on building real understanding rather than surface-level familiarity. Labs are implemented hands-on in working environments using WSL, cloud provider CLIs, and local Kubernetes clusters.A clean index of my learning path with links to each repo.
