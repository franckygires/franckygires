# Francky Girès FANOU

**IT Consultant | IS Architect – Cloud & DevOps**
Abidjan, Côte d'Ivoire · Cotonou, Benin · Open to relocation / Remote

Architecture, integrations and deployments, from requirements analysis to delivery. Everything is versioned, reproducible and auditable.

🔗 [franckygires.com](https://franckygires.com/en) · [LinkedIn](https://www.linkedin.com/in/francky-fanou) · [Online résumé](https://franckygires.com/en/cv)

## What I do

- **Scoping & IS architecture**: architecture dossiers, staged roadmaps, progressive migrations when service continuity is critical.
- **Build & integrations**: Infrastructure as Code, CI/CD pipelines and GitOps, security built in from the design stage.
- **Delivery & operations**: monitoring, incident management, business continuity and disaster recovery plans, documented procedures.

## Public reference

[**k3s-gitops-reference**](https://github.com/franckygires/k3s-gitops-reference): a 3-node K3s cluster built entirely from Git with Argo CD, PostgreSQL with synchronous replication, secrets in Vault, automated TLS and default-deny networking. On every push, CI rebuilds it on a clean machine and stops the node that hosts the database primary while a client is writing: no acknowledged write lost.

## Projects

| Project | In short |
|---|---|
| [Sovereign high-availability cloud infrastructure](https://franckygires.com/en#projet-infra) | Bare-metal 3-node K3s cluster run with GitOps (ArgoCD), synchronous PostgreSQL replication (RPO = 0), full rebuild from Git in under 30 minutes. Client anonymised. |
| [GoMarket, mobile marketplace](https://franckygires.com/en#projet-gomarket) | Serverless backend on GCP, Mobile Money payment, Algolia search, real-time notifications. |
| [GoMarket V2, migration without downtime](https://franckygires.com/en#projet-gomarket-v2) | Hybrid Firestore + Cloud SQL architecture, step-by-step migration (Strangler Fig). |
| [KubeQuest, cloud-native platform on Azure](https://franckygires.com/en#projet-kubequest) | 100% automated provisioning with Terraform, K3s, GitHub Actions CI/CD. |
| [Qualiscan, multi-tenant B2B SaaS](https://franckygires.com/en#projet-qualiscan) | Data isolation between client establishments, secured API, Docker deployments on Azure. |

All nine projects and their sheets are on the [portfolio](https://franckygires.com/en#realisations).

## Technical environment

- **Cloud**: Azure, Google Cloud Platform, AWS
- **Containers & orchestration**: Docker, Kubernetes (K3s), Helm, Longhorn
- **IaC & GitOps**: Terraform, Ansible, ArgoCD, GitHub Actions, GitLab CI/CD
- **Security**: Vault, External Secrets, cert-manager, RBAC, OAuth2
- **Observability**: Prometheus, Grafana, Loki
- **Development**: Node.js, TypeScript, PostgreSQL, Firestore

## Education and certifications

- AWS Certified Cloud Practitioner
- AWS Certified Solutions Architect – Associate (in progress)
- RNCP level 7 title, Information Systems Architect (ETNA, 2025)
- Professional Master in Technological Innovation, Cloud Computing (EPITECH, 2023 – 2025)

---

🇫🇷 Version française du portfolio : [franckygires.com/fr](https://franckygires.com/fr)
