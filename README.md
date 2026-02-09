<h1 align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=I'm%20Anass&fontSize=70&animation=fadeIn" />
</h1>

<p align="center">
  <strong>🚀 DevOps Engineer | Infrastructure as Code Enthusiast | Cloud Architect</strong>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hennour-anass-devops/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anas.hennour.10@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=an4she21&color=left" alt="visitor badge"/>
</p>

---

### 🛠 Tech Stack & Tooling

| Category | Tools |
| :--- | :--- |
| **Cloud & Infrastructure** | ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat-square&logo=amazon-aws&logoColor=white) ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=flat-square&logo=terraform&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **Containers & Orchestration** | ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=flat-square&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat-square&logo=docker&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1628?style=flat-square&logo=helm&logoColor=white) |
| **CI/CD & Automation** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Monitoring & Logging** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=Prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=Grafana&logoColor=white) ![ELK](https://img.shields.io/badge/ELK-005571?style=flat-square&logo=elastic-stack&logoColor=white) |

---

### 🧠 Modern Infrastructure Workflow
This diagram represents my standard approach to building automated, resilient systems:

```mermaid
graph LR
    A[Code] -->|Push| B(GitHub)
    B --> C{CI/CD Pipeline}
    C -->|Security Scan| D[Docker Registry]
    D -->|GitOps Deploy| E[K8s Cluster]
    E --> F[Observability]
    F -.->|Automated Alert| A

    style C fill:#2671E5,stroke:#fff,color:#fff
    style E fill:#326ce5,stroke:#fff,color:#fff
    style F fill:#F46800,stroke:#fff,color:#fff
