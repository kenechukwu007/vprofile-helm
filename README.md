# Vprofile GitOps Repository

This repository contains the Kubernetes manifests and a Helm chart for the Vprofile application.

## Helm chart

The chart is located at `helm/vprofile`.

## Deploy

```bash
helm install vprofile ./helm/vprofile
```

## Notes

- Ingress is enabled by default.
- ALB annotations are configured for AWS EKS.
- Docker registry secret is disabled by default.
- All image tags default to `latest`.
