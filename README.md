# Meinardo Benitez

Senior Cloud Engineer | DevSecOps & Platform Operations | AWS GovCloud · Azure Government | TS Cleared

I build and run secure cloud platforms for U.S. defense missions. 13+ years in DoD IT, from racking servers and running SQL to leading Azure Government operations for Army TRADOC, and now engineering Kubernetes platforms in AWS GovCloud. I like the hands-on troubleshooting as much as the leadership side: building teams, setting KPIs, and keeping production stable, compliant, and affordable.

Army veteran. Azure is where I came up; AWS, Kubernetes, and AI-driven automation are where I'm headed.

---

## What I'm Working On Now

**Booz Allen Hamilton — Senior Cloud Engineer, Platform Operations** *(Apr 2026 – Present)*

- Engineering mission application platforms on **Amazon EKS in AWS GovCloud** across demo, stage, and prod: Helm, ECR, IAM / Pod Identity, RDS PostgreSQL, DynamoDB, S3, Secrets Manager
- Using **Kubecost** to find wasted and underutilized EKS capacity, then **Karpenter** node provisioning and consolidation to right-size compute and cut unnecessary spend
- Building **pull-request build validation** in Azure DevOps that catches compile and container-build failures before merge, without publishing or deploying anything
- Onboarding and migrating application stacks between environments: ingress paths, service accounts, IAM, database dependencies, and release validation
- Day-to-day production debugging: CrashLoopBackOff, ImagePullBackOff, node disk pressure, RDS SSL and connectivity, DynamoDB throttling, F5 ingress and CORS routing
- Writing reusable migration checklists so the next environment move is repeatable, not tribal knowledge

## Recent Highlights

From leading Army TRADOC Azure Government (IL2/IL4) cloud operations, 2023–2026:

- 💰 Cut monthly cloud spend from **$62K to $43K** (~30%, $250K+ a year) on a $2.5M budget
- 👥 Led **12 direct reports** and coordinated 20+ cyber, app, and platform staff at **99.9% availability**
- 🚀 Zero-downtime migration of **11 WordPress sites** to Azure App Service, with 40% faster performance
- ⚙️ Terraform + Azure DevOps automation for **200+ VMs**, with 75% fewer deployment errors
- 🛡️ PowerShell / Azure Automation runbooks for **Evaluate-STIG** and STIG Manager, with 60% less manual remediation
- 🏅 22-person team development push that produced **14 new certifications**; named **2024 Collaborator of the Year**

---

## Tech I Work With

- **Cloud & containers:** AWS GovCloud (EKS, ECR, IAM, RDS, DynamoDB, S3, CloudWatch), Kubernetes, Karpenter, Docker, Helm, Azure Government (App Service, Monitor, Entra ID)
- **Automation & delivery:** Terraform, Azure DevOps Pipelines, GitHub Actions (OIDC), Ansible, PowerShell, Bash
- **Security & compliance:** DevSecOps, DISA STIG, RMF/ATO, ACAS / Tenable.sc, Checkov, Trivy, TFLint
- **FinOps & cost:** Kubecost, Infracost, Karpenter consolidation, cloud right-sizing
- **Operations:** incident and change management (ITIL), KPIs (availability, MTTR, change success)

---

## Portfolio Projects

🔹 **[terraform-ephemeral-sandbox-pipeline](https://github.com/mbeni555/terraform-ephemeral-sandbox-pipeline)**  
Every pull request spins up its own short-lived AWS sandbox and tears it down on close. GitHub Actions with OIDC (no static keys), Infracost cost comments on the PR, Checkov and TFLint gates, and S3-native state locking.

🔹 **[iac-ai-reviewer](https://github.com/mbeni555/iac-ai-reviewer)**  
A GitHub Action that scans changed Terraform and Kubernetes files with Checkov and Trivy, then uses a pluggable LLM provider to explain findings in plain English on the pull request. Works without an API key, too.

🔹 **[azure-vm-stig-assessment](https://github.com/mbeni555/azure-vm-stig-assessment)**  
PowerShell STIG assessment for Windows and Linux Azure VMs using managed identity, with no stored credentials. Built from the kind of compliance work I've done in GovCloud for years.

🔹 **[multi-cloud-free-tier-lab](https://github.com/mbeni555/multi-cloud-free-tier-lab)** *(in progress)*  
Security-first, zero-cost Terraform lab. The Azure foundation (resource group, segmented VNet, default-deny NSGs, Log Analytics) is in place; AWS and GCP stacks are next.

### On Deck

- **azure-gov-security-baseline:** STIG-aligned configuration patterns with Defender for Cloud and Sentinel
- **cloud-detection-engineering:** KQL hunting queries mapped to MITRE ATT&CK

---

## Service & Leadership

- U.S. Army Veteran (Operation Iraqi Freedom, 2009–2010), Army Commendation Medal and Combat Action Badge
- Team Rubicon Volunteer  
- James City County CERT  

---

## Education & Certifications

**B.S. Information Technology** (in progress), Southern New Hampshire University  
**A.S. Computer Information Science** (2012), ECPI University  

- CompTIA SecurityX (formerly CASP+) · Security+ CE
- MCSE: Cloud Platform & Infrastructure · MCSA: Windows Server / SQL Server
- AZ-900 Azure Fundamentals · AI-900 Azure AI Fundamentals
- Databricks Generative AI Fundamentals
- ITIL 4 Foundation · Certified ScrumMaster (CSM)

---

## Currently Strengthening

- AWS and Kubernetes platform engineering at scale
- Multi-cloud identity and network security models
- AI governance and secure AI system design, plus AI-assisted DevSecOps tooling
- Offensive security mindset for stronger defensive architecture
- Spanish (Duolingo)

---

## Connect with Me

- 🌐 [LinkedIn](https://www.linkedin.com/in/mbeni555/)
- 🎖 [Credly](https://www.credly.com/users/meinardo-benitez)
