# Kubernetes Stateful Application & Scaling Architecture

A comprehensive set of Kubernetes manifests demonstrating advanced workload management, scaling, and RBAC policies.


- statefulset.yml: StatefulSet deployment for app and PostgreSQL database with persistent volume templates.
- headless.yml: Headless Service for internal DNS pod identification.
- srv.yml: NodePort Service for external traffic routing.
- hpa.yml: Horizontal Pod Autoscaler configuration based on CPU utilization.
- vpa.yml: Vertical Pod Autoscaler setup for dynamic resource allocation.
- role.yml & rolebind.yml: RBAC policy mapping permissions to custom ServiceAccount.
- secret.yml: Encrypted sensitive environment variables for PostgreSQL.
