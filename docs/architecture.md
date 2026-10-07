# Architecture

## High-Level Architecture

User
→ Route53
→ Application Load Balancer
→ Ingress
→ Frontend
→ Backend
→ Amazon RDS

## Components

### Route53
Provides DNS routing.

### ACM
Provides TLS certificates.

### Application Load Balancer
Routes external traffic into the cluster.

### EKS
Hosts frontend and backend workloads.

### RDS PostgreSQL
Stores application data.

### ECR
Stores container images.

### Terraform
Provisions infrastructure resources.
