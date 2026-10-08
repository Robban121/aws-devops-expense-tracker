# aws-devops-expense-tracker
Individual project using Devops tech stack

# AWS DevOps Expense Tracker

A production-style cloud-native expense tracking application deployed on AWS using Terraform, Amazon EKS, Helm, ArgoCD and GitLab CI/CD.

---

## Project Overview

The goal of this project was to design, provision and deploy a cloud-native application using Infrastructure as Code, GitOps and Kubernetes deployment practices.

Key capabilities:

- Infrastructure provisioning using Terraform
- Containerized application deployment using Docker
- Kubernetes orchestration using Amazon EKS
- GitOps deployment using ArgoCD
- CI/CD automation using GitLab CI
- PostgreSQL database on Amazon RDS
- HTTPS exposure using Route53, ACM and AWS Load Balancer Controller

---

## Architecture

[Architecture]
diagrams/AWS Diagram.drawio.png
---

## Technology Stack

### Cloud
- AWS VPC
- Amazon EKS
- Amazon RDS
- Amazon ECR
- Route53
- ACM
- IAM

### Container Platform
- Docker
- Kubernetes
- Helm

### Infrastructure as Code
- Terraform
- HCP Terraform

### CI/CD & GitOps
- GitLab CI/CD
- ArgoCD

---

## Infrastructure Provisioned

Terraform provisions:

- VPC
- Public and Private Subnets
- EKS Cluster
- Managed Node Groups
- RDS PostgreSQL
- ECR Repositories
- IAM Roles
- Route53 Records
- ACM Certificates

---

## Screenshots

### GitLab CI/CD Pipeline

[Pipeline]
snapshots/CICD_1.png
snapshots/CICD_2.png
snapshots/CICD_3.png

### ArgoCD Application

[ArgoCD]
snapshots/ArgoCD.png

### EKS Cluster

[EKS]
snapshots/EKS_1.png
snapshots/EKS_2.png
### Expense Tracker Dashboard

[Dashboard]
snapshots/application_dashboard.png.png

---

## Documentation

- [Architecture](docs/architecture.md)
- [Deployment Flow](docs/deployment-flow.md)
- [Lessons Learned](docs/lessons-learned.md)

---
