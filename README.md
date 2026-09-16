# Brandon Graham

LinkedIn: https://www.linkedin.com/in/brgraham/

## Professional Summary

Principal-level infrastructure and platform engineer with 20+ years building internal developer platforms, CI/CD systems, and production infrastructure across AWS, bare metal, and on-premises customer environments. Currently the sole infrastructure engineer at a hardware design platform serving defense, aerospace, and semiconductor customers, running hosted AWS tenants and self-hosted Linux deployments under SOC 2 and AWS GovCloud.

## Technical Competencies

**Platform Engineering and Automation:** Internal Developer Platforms | Self-Service Provisioning | Account Vending | Terraform (Cloud Enterprise, Atlantis) | Ansible | GitOps (Argo CD, Kargo) | Helm | Kustomize | just | GitHub Actions | CI/CD Pipeline Design | Infrastructure-as-Code | Air-Gapped Delivery (Replicated, Zarf)

**Cloud and Infrastructure:** AWS (EC2, EKS, ECS, S3, RDS, Lambda@Edge, CloudFront, WAF, Control Tower, Organizations, VPC, Transit Gateway, Direct Connect, Route53, GovCloud) | GCP (GKE, CloudSQL) | Kubernetes (EKS, GKE, k3s, bare metal) | Docker | Docker Swarm | Enterprise Linux at Scale | Bare Metal Provisioning | Hybrid and Multi-Cloud Architecture

**Observability and Reliability:** Grafana | Alloy | Loki | Mimir | Prometheus | VictoriaMetrics | Vector | OpenTelemetry | Monitoring and Alert Design | Noise Reduction | On-Call and Incident Response | Capacity Planning | Cost Optimization

**Networking, Security, and Compliance:** VPC Architecture | Transit Gateway | VPC Endpoints | Load Balancing (F5 BIG-IP, ALB, NLB, HAProxy) | WAF and Bot Mitigation | Cloudflare Workers | Tailscale | Secrets Management (HashiCorp Vault, HSM Key Custody) | LDAP | Active Directory | Entra ID | Okta | SAML | OIDC | SOC 2 Type I and Type II | Vulnerability Management

**AI Infrastructure, Data, and Languages:** Amazon Bedrock | Amazon SageMaker | Containerized Inference Services | Open-Weight Model Deployment (Qwen, DeepSeek) | GPU Benchmarking (NVIDIA RTX PRO 6000 Blackwell) | PostgreSQL (CloudNativePG, PgPool, sharding) | MySQL | DynamoDB | Python | Go | Bash | Terraform HCL

## Professional Experience

### Principal Infrastructure Engineer | AllSpice
April 2026 – Present

- Own infrastructure, security, and customer deployment end to end as the only infrastructure engineer, supporting 20 engineers across AWS-hosted tenants and customer self-hosted Linux installations in defense, aerospace, and semiconductor manufacturing, including AWS GovCloud.
- Automated per-tenant AWS account provisioning with Terraform, Ansible, and just, cutting new customer deployment from one full day to two hours.
- Cut paging from more than two pages per week to four per month while deployed infrastructure doubled, rebuilding alerting around conditions that predict customer impact and moving operator remediation onto the instances.
- Containerized DRCY, a production AI design review agent, replacing per-invocation source builds inside the GitHub Actions runner with a prebuilt container, then built a SageMaker evaluation pipeline on RTX PRO 6000 Blackwell GPUs comparing open-weight and frontier models.
- Ran the company's second SOC 2 audit end to end across Type I and Type II, verifying control enforcement rather than documentation and remediating Secureframe findings across the fleet.

### Senior DevOps Engineer | Monad Foundation
April 2025 – January 2026

- Operated hybrid bare-metal and AWS EKS Kubernetes infrastructure across four providers, supporting a distributed team spanning US, EU, and Asia timezones.
- Refactored the Terraform codebase into a data-driven architecture with input validation, environment isolation, and GitOps deployment through Atlantis, catching misconfiguration before runtime and preventing partial applies.
- Engineered a node observability pipeline on Vector, VictoriaMetrics, and Grafana with Python-based enrichment, covering 300+ nodes and becoming the primary health view for the DevOps team and leadership.
- Troubleshot operator failures at the packet level with tcpdump, diagnosing MTU fragmentation, asymmetric UDP flows, and firewall misconfiguration for hundreds of external node operators.

### Principal Site Reliability Engineer | Edge and Node
August 2024 – March 2025

- Analyzed Google CloudSQL usage across 10TB+ sharded PostgreSQL instances and designed a resizing and pruning strategy projected to save $360K annually with zero production impact.
- Migrated IPFS infrastructure off three self-hosted clusters to a managed provider, cutting monthly cost from $6,000 to $500. Built a Cloudflare Worker abstraction layer preserving the full RPC surface so the dependent stack required no changes.

### Co-Founder and Lead Consultant | VeriHash
December 2021 – Present

- Designed and operated 8 bare metal and cloud Kubernetes clusters across US, EU, and Asia, managed with Terraform, Helm, and a custom Tailscale mesh network predating the official Tailscale Kubernetes operator.
- Redesigned a single-cloud Kubernetes deployment into a multi-cloud architecture, reducing infrastructure cost by approximately 30%, and operated self-hosted PostgreSQL with offline encrypted key storage and HSM-backed remote signing.

### Technical Lead Cloud Engineer | Redfin
March 2022 – June 2024 (Position eliminated in re-org)

- Led the on-premises to AWS migration of a Java monolith, finishing 35 days ahead of schedule and $150K under budget, with AWS presenting as another datacenter so the application needed no changes.
- Consolidated 50+ AWS accounts into Control Tower with OU-based governance, baseline security enforcement, and Okta single sign-on, then replaced inter-VPC Transit Gateway routing with VPC endpoints at zero downtime.
- Reverse-engineered undocumented F5 BIG-IP logic controlling bot detection and traffic routing, translating the ruleset into AWS WAF rules, IP lists, and bot controls deployed through Terraform and Lambda@Edge.
- Restructured AWS resource allocation for $340K in annual savings, and instituted Infrastructure-as-Code practices that reduced ongoing cloud management effort by roughly 1 FTE per year.

### Principal Infrastructure Engineer | SurveyMonkey
August 2018 – November 2021

- Built a data-driven internal developer platform on Terraform and Terraform Cloud Enterprise, where infrastructure owned the modules encoding security posture, sizing ranges, and cost constraints, and development teams selected blessed configurations through validated data inputs without needing Terraform internals.
- Integrated the platform with an account vending machine provisioning AWS accounts with secure-by-default baselines, cost controls, and per-service data isolation enforced through defined REST APIs.
- Scaled platform adoption to five teams running pre-production and production environments at departure, with the framework remaining in service well past that point.
- Deployed the multi-region Transit Gateway backbone connecting 30+ AWS accounts across two US regions, EU, and Asia, live in production on day one of the cloud migration.

### Earlier Experience

Infrastructure Engineering Lead at **Saildrone** (April 2016 – August 2018), first infrastructure hire, moved production onto AWS EKS and raised availability from 90.6% to 99.4%. Senior Infrastructure Engineer at **Funding Circle US** (October 2015 – April 2016), Mesos and Chef in the early container orchestration era. Senior DevOps Engineer at **MyFitnessPal** (October 2014 – June 2015), MySQL Galera and SaltStack. Site Reliability Engineer at **Pinterest** (July 2013 – July 2014), Puppet configuration management across a 200+ node MySQL fleet. Network, Security, and Lead Hadoop Infrastructure Engineer at **Intel** (June 2008 – July 2013), F5 BIG-IP optimization, datacenter migrations under formal change control, and Hadoop on Linux. Systems Administrator at **Lowe's** (March 2007 – June 2008) and **Providence Health** (August 2005 – August 2006). Founder of **Graham and Associates** (January 1999 – March 2007), a regional IT consultancy serving 15 clients.

## Education

Southern Oregon University, Bachelor of Science, Computer Science. Concentration: Computer Security and Information Assurance
