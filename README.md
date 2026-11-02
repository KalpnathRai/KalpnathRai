<div align="center">

  <!-- Waving Banner with Name (Executive Dark Slate to Ocean Blue & Electric Cyan) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,50:0052cc,100:00c6ff&height=220&section=header&text=Kalp%20Nath%20Rai&fontSize=48&fontAlignY=46&fontColor=ffffff" width="100%" alt="Kalp Nath Rai" />

  <!-- Animated Typing Headline -->
  <a href="https://github.com/KalpnathRai">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=0052CC&center=true&vCenter=true&width=650&lines=Cloud+%26+DevSecOps+Engineer+(5%2B+Yrs+Exp);AI+%26+Agentic+Cloud+Security+%E2%80%A2+MCP+%26+RAG;Terraform+%E2%80%A2+Azure+%26+AWS+%E2%80%A2+Kubernetes;Platform+Engineering+%E2%80%A2+CI%2FCD+Automation" alt="Typing SVG" />
  </a>

  <p align="center">
    <strong>Cloud &amp; DevSecOps Engineer &bull; Azure &amp; AWS &bull; Terraform &bull; CI/CD &bull; AI &amp; MCP</strong><br/>
    <em>Secure infrastructure. Repeatable delivery. Observable systems.</em>
  </p>

  <!-- Connect Badges (Amirul Style) -->
  <p align="center">
    <a href="https://www.linkedin.com/in/kalp-nath-rai-39848820" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://github.com/KalpnathRai?tab=repositories">
      <img src="https://img.shields.io/badge/GitHub-Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="#">
      <img src="https://img.shields.io/badge/Location-India-2ea44f?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location" />
    </a>
    <a href="mailto:kalprai32@gmail.com">
      <img src="https://img.shields.io/badge/Email-Get_in_Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>

</div>

---

## 👏 About

I am a **Cloud & DevSecOps Engineer** with **5+ years of hands-on experience** in multi-cloud infrastructure engineering, automation, and platform security. My work focuses on designing and implementing production-ready, repeatable, and secure cloud environments across **Microsoft Azure** and **AWS**.

I specialize in **Infrastructure as Code (Terraform)**, **Platform Engineering**, **CI/CD pipeline automation (Azure DevOps & GitHub Actions)**, **Kubernetes (AKS & EKS)**, and modern **AI & Agentic Cloud Security (Model Context Protocol - MCP, AI Agents, and Secure RAG infrastructure)**.

My objective is to build clean, observable, and cost-efficient cloud architectures where security, compliance, and reliability are automated from commit to production.

---

## 🛡️ Engineering Principles

Every architecture, pipeline, and infrastructure module I build adheres to these foundational engineering standards:

* **Infrastructure as Code (IaC):** All infrastructure is 100% declared in code, version-controlled, modular, and reviewable via pull requests. No manual console drift.
* **Shift Security Left:** Automated formatting (`terraform fmt`), linting (`tflint`), secret detection (`GitLeaks`), and security misconfiguration scanning (`Checkov`, `Trivy`) run on every PR before merge.
* **Protect Credentials & Zero Standing Access:** Zero plaintext secrets or committed `.tfvars`. State files are remotely locked and encrypted; access is governed via **Microsoft Entra ID / AWS IAM** with **Privileged Identity Management (PIM)** and Managed Identities.
* **Least Privilege & Network Isolation:** Prevent unnecessary public exposure. Workloads reside in private subnets across **Hub-and-Spoke VNets / VPCs**, accessed via **Private Endpoints / PrivateLink**, **Azure Bastion**, and inspected by **Firewalls**.
* **Safer Change Management:** Every change requires a generated plan artifact (`terraform plan`), automated cost delta checks (`Infracost`), and peer approvals through `CODEOWNERS` policies.
* **Operational Readiness:** Systems are deployed with centralized logging (**Log Analytics**, **CloudWatch**), actionable metric alerts (**Azure Monitor**, **Prometheus/Grafana**), and documented runbooks.
* **Evidence Over Claims:** Focus on tested, validated implementations with clear architectural decision records (ADRs) and measurable outcomes.

---

## 🎯 Core Focus Areas

* **Cloud Platforms & Networking:** Multi-cloud architecture across Microsoft Azure and Amazon Web Services (AWS), Hub-and-Spoke topologies, VNets/VPCs, Subnets, NSGs, Security Groups, Azure Firewall, AWS WAF, and Private Endpoints.
* **Infrastructure as Code (IaC):** Reusable and versioned Terraform modules, Terragrunt, Azure Bicep/ARM, remote state locking with Azure Blob Storage and AWS S3 / DynamoDB, and automated drift detection.
* **CI/CD Automation & GitOps:** End-to-end multi-stage YAML pipelines in Azure DevOps and GitHub Actions, incorporating automated testing, quality gates, and secure deployment strategies.
* **DevSecOps & Supply Chain Security:** Integrating automated SAST, SCA, container vulnerability scanning, and policy-as-code using GitLeaks, Checkov, Trivy, SonarQube, and Snyk.
* **Containers & Kubernetes:** Docker image optimization, container registry security (ACR / ECR), and enterprise Kubernetes workload deployment and management on AKS and EKS using Helm.
* **Reliability, Monitoring & FinOps:** Proactive observability using Azure Monitor, Log Analytics, AWS CloudWatch, Prometheus, and Grafana; cloud cost optimization through rightsizing, waste elimination, and automated scheduling.
* **AI & Agentic Cloud Security:** Implementing Model Context Protocol (MCP) servers, leveraging GitHub Copilot and AI agents for automated PR remediation, and provisioning secure cloud infrastructure for private RAG platforms.

---

## 🛠️ Technical Stack & Tools

| Domain | Technologies & Tools |
| :--- | :--- |
| **Cloud Platforms** | Microsoft Azure, Amazon Web Services (AWS), Hybrid Cloud |
| **Cloud Networking** | Hub-and-Spoke VNets, AWS VPC, Subnets, NSGs, Security Groups, Azure Firewall, AWS WAF, Private Endpoints, PrivateLink, Azure Bastion |
| **Infrastructure as Code** | Terraform, Terragrunt, Azure Bicep, ARM Templates, Ansible, Packer |
| **CI/CD & Platform Engineering** | Azure DevOps Pipelines, GitHub Actions, GitLab CI, ArgoCD, Helm |
| **Containers & Orchestration** | Docker, Kubernetes (AKS & EKS), Azure Container Registry (ACR), Amazon ECR, Ingress Controllers |
| **Cloud Security & DevSecOps** | GitLeaks, Checkov, Trivy, SonarQube, Snyk, TFLint, Azure Key Vault, AWS KMS, Policy-as-Code |
| **Identity & Access** | Microsoft Entra ID (Azure AD), AWS IAM, RBAC, Privileged Identity Management (PIM), Managed Identities, IAM Roles |
| **Monitoring & SRE** | Azure Monitor, AWS CloudWatch, Log Analytics Workspace, Prometheus, Grafana, Infracost, Alert Action Groups |
| **AI & Agentic Cloud Security** | Model Context Protocol (MCP), GitHub Copilot, AI Ops Agents, Secure RAG Infrastructure, Harness AI |
| **Scripting & OS** | Bash, PowerShell Core, Python 3, Linux (Ubuntu, RHEL) |

---

## 💼 Experience & Key Deliverables (5+ Years)

* **Multi-Cloud IaC Provisioning:** Built and managed production-grade cloud infrastructure on Azure and AWS using modular, parameter-driven **Terraform** configurations with remote state locking.
* **Automated CI/CD Delivery:** Designed and maintained scalable **Azure DevOps & GitHub Actions YAML pipelines** automating build, security testing, and infrastructure deployment workflows.
* **Shift-Left Security Implementation:** Integrated security gates into developer pull requests using **GitLeaks** for secret prevention, **Checkov** for IaC compliance, and **Trivy** for container vulnerability scans.
* **Secure Enterprise Networking:** Architected **Hub-and-Spoke network topologies** with centralized inspection via **Azure Firewall**, forced tunneling (`0.0.0.0/0`), and private connectivity for PaaS services using **Private Endpoints & PrivateLink**.
* **Kubernetes Cluster Operations:** Containerized applications using **Docker** and managed production deployments on **Azure Kubernetes Service (AKS)** and **Amazon EKS** using **Helm charts** and network policies.
* **Identity Governance & Access Control:** Enforced strict least-privilege security using **Microsoft Entra ID**, **AWS IAM**, and **Privileged Identity Management (PIM)** with Just-In-Time role activation.
* **Observability & Incident Management:** Configured centralized log aggregation via **Log Analytics Workspaces** and **AWS CloudWatch**, setting up automated alerts and dashboards for rapid troubleshooting.
* **FinOps & Cloud Cost Optimization:** Achieved 25%+ cost reductions across cloud subscriptions through automated non-production VM shutdown schedules, instance rightsizing, and orphaned resource cleanup.
* **AI-Assisted DevOps Adoption:** Leveraged **Model Context Protocol (MCP)** tools, **GitHub Copilot**, and AI agents to accelerate troubleshooting, automate code validation, and support secure RAG infrastructure deployments.

---

## 🚀 Featured Architecture Repositories

| Repository | Focus Area | Technologies |
| :--- | :--- | :--- |
| **[azure-enterprise-landingzone](https://github.com/KalpnathRai)** | Production-grade multi-subscription landing zone with Hub-and-Spoke networking and governance guardrails | `Terraform` `Azure CAF` `Azure Policy` `Hub-Spoke` |
| **[devsecops-golden-pipeline](https://github.com/KalpnathRai)** | Multi-stage CI/CD security template featuring automated SAST, secret detection, IaC scanning, and cost gating | `Azure DevOps` `GitHub Actions` `Checkov` `GitLeaks` `Trivy` |
| **[aks-production-baseline](https://github.com/KalpnathRai)** | Secure AKS cluster deployment with Azure CNI, Key Vault CSI secret driver, and Helm release workflows | `Kubernetes` `AKS` `Helm` `Docker` `Key Vault` |
| **[devsecops-mcp-agent](https://github.com/KalpnathRai)** | Model Context Protocol (MCP) server integration enabling AI agents to scan IaC and triage pipeline build logs | `MCP` `Python` `AI Agents` `Checkov` `DevOps` |
| **[finops-cloud-waste-cleanup](https://github.com/KalpnathRai)** | Automated scripts to detect and remediate unattached disks, idle public IPs, and underutilized VMs | `Python` `PowerShell` `Azure CLI` `FinOps` |

---

## 📚 Currently Learning & Exploring

* Advanced custom **Model Context Protocol (MCP)** tool servers for automated SRE incident remediation.
* Hardening enterprise **Private RAG (Retrieval-Augmented Generation)** workloads across Azure & AWS.
* Kernel-level container security and observability with **eBPF & Cilium**.

---

## 🔗 Connect With Me

<p align="left">
  <a href="https://www.linkedin.com/in/kalp-nath-rai-39848820" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:kalprai32@gmail.com">
    <img src="https://img.shields.io/badge/Email-Kalp_Nath_Rai-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/KalpnathRai">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>
