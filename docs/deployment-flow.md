# Deployment Flow

## CI/CD Workflow

1. Developer pushes code.
2. GitLab CI pipeline starts.
3. Docker image is built.
4. Image is pushed to Amazon ECR.
5. Deployment repository is updated.
6. ArgoCD detects changes.
7. Application is deployed to EKS.

## GitOps Workflow

Application Repository
→ GitLab CI
→ ECR
→ Deployment Repository
→ ArgoCD
→ EKS
