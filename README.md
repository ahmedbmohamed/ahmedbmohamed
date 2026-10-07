## Hi, I'm Ahmed Benmohamed 👋

**Cloud, DevSecOps & Network Security Engineer** based in Tunis, Tunisia.
Engineering degree in Security of Computer Systems and Networks (TEK-UP University, 2026).

- 🏆 **Global Second Prize**, Huawei ICT Competition 2025–2026 (Cloud Track)
- 🎓 **5 Red Hat certifications**: RHCE, RHCSA, Ansible, Containers (Podman), Cloud-native Applications
- 🔭 Currently: Kubernetes, GitOps and cloud security
- 📫 [LinkedIn](https://www.linkedin.com/in/ahmed-benmohamed-71b243309) · [Portfolio](https://ahmedbmohamed.github.io) · ahmedbenmohamed99@gmail.com

### ⭐ Featured project

**[devsecops-gitops-lab](https://github.com/ahmedbmohamed/devsecops-gitops-lab)**: a complete DevSecOps + GitOps flow on Kubernetes.

- GitHub Actions CI: unit tests → Docker build → **Trivy security gate** (blocks HIGH/CRITICAL vulnerabilities) → push to GHCR → image tag committed to Helm values
- Hardened Helm chart: non-root, read-only root filesystem, dropped capabilities, probes, resource limits
- **ArgoCD** auto-sync with prune and self-heal on minikube
- Documented proof: a pull request with a vulnerable dependency was blocked by the pipeline

### 🛠️ What I work with

| Area | Tools |
|---|---|
| Cloud & DevOps | Kubernetes, Helm, ArgoCD, GitHub Actions, Docker, Podman, Ansible, Azure, Huawei Cloud |
| Linux & scripting | Red Hat Enterprise Linux, Ubuntu, Bash, Python, Git |
| Security | Wazuh SIEM, SOAR automation, Trivy, FortiGate, pentesting (OWASP Top 10), ISO 27001 |
| Networking | OSPF, MP-BGP, MPLS L3VPN, VLANs, HSRP/VRRP, AAA/RADIUS, GNS3 |

### 📌 Other work

- **Autonomous SOC platform** (final-year project): Wazuh SIEM + machine learning + SOAR that detects and contains incidents in under 35 seconds (FortiGate and iptables blocking, host isolation)
- **IP/MPLS backbone & L3VPN lab**: PE/P/CE with multi-area OSPF, MPLS LDP, MP-BGP VPNv4, VRFs, IP SLA monitoring
- **LLM for SOC analysts**: natural language → KQL queries for Microsoft Sentinel (LLaMA, RAG, LoRA)
