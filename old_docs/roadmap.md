# MVP - Clusterless

- Pure SaaS (Hosted only)
- Shared Kubernetes cluster
- Metrics
- CLI
- Initial UI
- Billing is flat for tenenat depending on resources
- Kubeconfig (kubeadm) for tenant (VCluster)
- Kubeconfig (namespaces) for namespaces
- Environment is a collection of NameSpaces
- Open Tenant - all NS communicate with each other
- App templates / Blueprints / Golden paths / Starter kits
- DNS
- Ingress
- Gateway API
- GitOps (ArgoCD)
- Cert Manager

# v.0.1.0

- Close tenants (no NS communication by default)
- Private cluster
- SSO login
- Data persistence (PVs, PVCs, at tenant level)
