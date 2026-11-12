# Hi, I'm Matej 👋

**DevOps & platform engineer** from Zagreb, Croatia: Kubernetes, GitOps,
CI/CD and self-hosted infrastructure.

- 💼 **System Engineer at Enlayer** (formerly Telelink Business Services),
  looking after customers' production server environments
- 🏗️ Building and running a **production-style homelab**: a cloud VPS and a
  home VM over WireGuard, GitLab CI/CD, k3s deployed by ArgoCD, full
  observability, encrypted backups, all of it in Git
- 🎓 **AWS Certified Solutions Architect – Associate**, now studying for the
  **CKA**

## 🏗️ Homelab

[![Homelab architecture](https://raw.githubusercontent.com/MatejK97/homelab/main/docs/architecture.png)](https://github.com/MatejK97/homelab)

Everything is code, every change goes through a merge request, and every
service is monitored. Highlights:

- **GitOps:** ArgoCD app-of-apps, SOPS-encrypted secrets, Renovate MRs for
  every image and chart update
- **CI/CD & DevSecOps:** shared GitLab CI templates, gitleaks and Trivy in every
  pipeline, scoped deploy keys
- **Observability:** Prometheus, Grafana, Loki and Alloy, alert rules as code,
  email alerts and a dead man's switch
- **IaC:** Terraform for GitLab itself, Ansible for the hosts
- **Security:** admin UIs reachable only over WireGuard, key-only SSH,
  append-only off-site backups

| Repository | |
|---|---|
| [homelab](https://github.com/MatejK97/homelab) | The full write-up: architecture, decisions, lessons learned |
| [gitops](https://github.com/MatejK97/gitops) | Everything on the k3s cluster, deployed by ArgoCD |
| [ci-templates](https://github.com/MatejK97/ci-templates) | Shared GitLab CI pipelines with security scanning |
| [terraform](https://github.com/MatejK97/terraform) | GitLab's own configuration as code |
| [traefik](https://github.com/MatejK97/traefik) | Reverse proxy with public and VPN-only entrypoints |

## 🛠️ Tools

**Platform**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![k3s](https://img.shields.io/badge/k3s-FFC61C?style=flat&logo=k3s&logoColor=black)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?style=flat&logo=windows&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

**CI/CD & automation**
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Renovate](https://img.shields.io/badge/Renovate-1A1F6C?style=flat&logo=renovate&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

**Observability & networking**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=flat&logo=grafana&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat&logo=wireguard&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matej-kovacevic-dev/)
