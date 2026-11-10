### Hi, I'm Tony 👋

Solutions Architect / Tech Lead for **Cloud Engineering & SRE** with **25+ years in IT**, the last 14+ focused on making cloud platforms reliable, observable, and boring in the best way, across AWS (commercial + GovCloud), Azure, and Kubernetes. Now applying the same discipline to **enterprise GenAI**: guardrailed, private, cost-governed RAG platforms on Amazon Bedrock and Azure OpenAI.

- 🏛️ Today: architecture and SRE leadership for enterprise and government customers, with FedRAMP Moderate/High, DoD IL5/IL6, NIST 800-53, and CMMC in scope
- 🌎 Before that: led a 12-person global onshore/offshore SRE org on AWS and Azure
- 🧠 Lately: building production-shaped GenAI platforms (RAG with guardrails, private networking, per-team token budgets, and eval suites that gate every change) on AWS and Azure
- 🤖 Also: agentic Claude Code workflows that tie together cloud, observability, and incident tooling

#### Impact

- 🏦 **Led a 12-person global SRE org** in regulated financial services (AWS + Azure): cut MTTR **~35%**, reduced repeat incidents **~20%**, and lowered pages per on-call engineer **25%+** through runbook maturity, alert-routing cleanup, threshold tuning, and automated remediation of common failures
- 📈 Met a **99.95% availability target** on customer-facing platforms
- 🛡️ Architecture and SRE lead across **7 enterprise and government customers**; operated and maintained compliance controls for **3 FedRAMP High / DoD IL5 environments** through ATO readiness
- 🚚 **50+ services** migrated or re-platformed across multi-account AWS and EKS, built on standardized, reusable Terraform modules

#### What I work on

| | |
|---|---|
| **AI / GenAI platforms** | Amazon Bedrock (Guardrails, Knowledge Bases, S3 Vectors), Azure OpenAI (content filters, Prompt Shields), Azure AI Search (hybrid + semantic ranking), APIM AI gateway, RAG, promptfoo evals / red-teaming, OpenTelemetry GenAI metrics |
| **Cloud & platform** | AWS (incl. GovCloud), Azure, EKS / AKS, Windows infrastructure (IIS, AD, PowerShell remoting), SQL Server AG/WSFC, F5 BIG-IP |
| **Infrastructure as Code** | Terraform, Ansible, PowerShell, Python, Bash |
| **Observability as Code** | Prometheus, Grafana / Grafonnet, Datadog, Dynatrace, AppDynamics, Splunk, CloudWatch, PagerDuty |
| **Delivery** | Azure DevOps, GitHub Actions, GitOps, blue/green deployments |
| **Compliance & supply chain** | FedRAMP, DoD IL5/IL6, NIST 800-53, CMMC, CUI handling, SBOMs, vulnerability-remediation SLAs |

#### Certifications

- Microsoft Certified Solutions Expert (MCSE): Cloud Platform & Infrastructure
- DevOps Institute: Site Reliability Engineering Foundation (SRE-F)
- CompTIA Security+
- AWS Certified Solutions Architect – Associate (SAA-C03): *in progress*

#### Projects

| Repo | What's in it |
|---|---|
| [aws-genai-platform](https://github.com/Krustytoe/aws-genai-platform) | RAG platform on Amazon Bedrock: Terraform for guardrails (enforced by IAM deny), S3 Vectors knowledge base, private endpoints and invocation audit logging; FastAPI service with PII redaction, citations and per-team cost metrics; promptfoo evals in CI |
| [azure-genai-platform](https://github.com/Krustytoe/azure-genai-platform) | Keyless RAG platform on Azure OpenAI + AI Search: Terraform for an APIM AI gateway with per-team token limits, Prompt Shields content filtering and private endpoints; same API and eval suite as the AWS build |
| [claude-code-skills](https://github.com/Krustytoe/claude-code-skills) | Claude Code plugin: Terraform plan risk review, alert authoring, incident triage, GovCloud readiness |
| [observability-as-code](https://github.com/Krustytoe/observability-as-code) | Prometheus rules with promtool unit tests, multi-burn-rate SLO alerts, Grafonnet dashboards, Terraform deploys |
| [terraform-aws-platform-modules](https://github.com/Krustytoe/terraform-aws-platform-modules) | Partition-aware Terraform modules (VPC baseline, GitHub OIDC role, encrypted SNS alerting) with offline `terraform test` suites |
| [terraform-azure-platform-modules](https://github.com/Krustytoe/terraform-azure-platform-modules) | Partition-aware Azure Terraform modules (VNet baseline, GitHub OIDC role, Monitor action group) with offline `terraform test` suites |
| [kubernetes-platform-modules](https://github.com/Krustytoe/kubernetes-platform-modules) | Terraform modules for EKS and AKS: private endpoints, IMDSv2, workload identity, KMS secrets encryption, offline `terraform test` suites |
| [platform-workflows](https://github.com/Krustytoe/platform-workflows) | Reusable GitHub Actions workflows (Terraform plan/apply, Trivy scan) and composite actions (AWS + Azure OIDC auth, Terraform setup) |

#### How I like to build

Git as the source of truth · validate → plan → approve → apply · tests for alerts, not just code · evals for AI, not just demos · least privilege by default · automate the second time, not the fifth.

#### Get in touch

💼 [LinkedIn](https://www.linkedin.com/in/tonyle214)
