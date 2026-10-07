# Lessons Learned

## EKS NodeCreationFailure

### Issue
Worker nodes failed to join the cluster.

### Root Cause
Private subnet networking configuration.

### Resolution
Enabled public API endpoint access and validated networking.

---

## ImagePullBackOff

### Issue
Pods failed to pull images from ECR.

### Resolution
Corrected image architecture and registry configuration.

---

## Route53 Hosted Zone Conflict

### Issue
Terraform attempted to create duplicate hosted zones.

### Resolution
Imported resources into Terraform state.

---

## ArgoCD Repository Authentication

### Issue
ArgoCD could not access repository.

### Resolution
Configured repository credentials using Kubernetes secrets.
