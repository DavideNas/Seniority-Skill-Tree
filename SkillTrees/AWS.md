## ☁️ Senior AWS Cloud Engineer – Skill Stack (2025)

---

### 🧠 1. **Fondamenta AWS**

| Area                      | Dettagli                                                                  |
| ------------------------- | ------------------------------------------------------------------------- |
| AWS Well‑Architected      | ✅✅✅ (5 pilastri: affidabilità, performance, sicurezza, cost‑opt, ecc.) |
| Global Infrastructure     | ✅✅✅ (regioni, AZ, edge locations, Local Zones)                         |
| AWS Shared Responsibility | ✅✅✅ (chizione responsabilità AWS vs cliente)                           |

---

### ⚙️ 2. **Compute & Container**

| Servizio          | Dettagli                                                   |
| ----------------- | ---------------------------------------------------------- |
| EC2               | ✅✅✅ (AMI, Auto Scaling, placement groups)               |
| ECS / Fargate     | ✅✅✅ (cluster, task definitions, service auto‑scaling)   |
| EKS / Kubernetes  | ✅✅ (managed K8s, node groups, helm, CNI)                 |
| Lambda            | ✅✅✅ (event‑driven functions, layers, cold start tuning) |
| Elastic Beanstalk | ✅ (PaaS rapido per deploy)                                |

---

### 🗺️ 3. **Networking**

| Area                      | Dettagli                                            |
| ------------------------- | --------------------------------------------------- |
| VPC                       | ✅✅✅ (subnet publics/private, NACL, route tables) |
| Transit Gateway / Peering | ✅✅ (multi‑VPC connectivity)                       |
| ELB (ALB, NLB, CLB)       | ✅✅✅ (listener rules, TLS termination)            |
| Direct Connect / VPN      | ✅✅ (site‑to‑site VPN, DX links)                   |
| Route 53                  | ✅✅✅ (DNS, health checks, latency routing)        |

---

### 💾 4. **Storage & Database**

| Servizio         | Dettagli                                         |
| ---------------- | ------------------------------------------------ |
| S3               | ✅✅✅ (lifecycle rules, versioning, encryption) |
| EBS / EFS / FSx  | ✅✅ (block vs file storage, performance modes)  |
| RDS              | ✅✅✅ (Multi‑AZ, read replicas, backups)        |
| DynamoDB         | ✅✅✅ (on‑demand vs provisioned, global tables) |
| Aurora / Neptune | ✅ (serverless Aurora, graph DB)                 |

---

### 🔐 5. **Sicurezza & Identity**

| Area                       | Dettagli                                               |
| -------------------------- | ------------------------------------------------------ |
| IAM                        | ✅✅✅ (policies, roles, groups, STS, least privilege) |
| AWS KMS / ACM              | ✅✅ (key management, envelope encryption, TLS certs)  |
| Security Hub / GuardDuty   | ✅✅ (threat detection, compliance checks)             |
| WAF / Shield               | ✅✅ (web ACL, DDoS protection)                        |
| AWS Config / Audit Manager | ✅ (compliance rules, drift detection)                 |

---

### 🔧 6. **Infra as Code & Automation**

| Tool / Servizio    | Dettagli                                                  |
| ------------------ | --------------------------------------------------------- |
| AWS CloudFormation | ✅✅ (nested stacks, macros, drift detection)             |
| AWS CDK            | ✅✅✅ (TypeScript/Python constructs, stage synth/deploy) |
| Terraform          | ✅✅✅ (modules, state backend, workspaces)               |
| AWS CLI / SDK      | ✅✅ (automation scripts, boto3, aws‑cli v2)              |
| Systems Manager    | ✅✅ (Parameter Store, Run Command, Patch Manager)        |

---

### 🔄 7. **CI/CD & DevOps Pipeline**

| Strumento                     | Dettagli                                             |
| ----------------------------- | ---------------------------------------------------- |
| AWS CodePipeline              | ✅✅ (stages, actions, custom plugins)               |
| CodeBuild / CodeDeploy        | ✅✅✅ (buildspec, appspec, blue/green deployments)  |
| GitHub Actions ↔ AWS          | ✅✅ (OIDC authentication, deploy to EKS/ECS/Lambda) |
| AWS CodeArtifact / CodeCommit | ✅ (artifact repo, source repo)                      |

---

### 📈 8. **Monitoring, Logging & Observability**

| Servizio                  | Dettagli                                         |
| ------------------------- | ------------------------------------------------ |
| CloudWatch Metrics / Logs | ✅✅✅ (alarms, dashboards, log groups, filters) |
| X‑Ray                     | ✅✅ (distributed tracing, service map)          |
| CloudTrail                | ✅✅✅ (API auditing, event history)             |
| OpenTelemetry on AWS      | ✅ (Lambda + ECS tracing, propagazione contesto) |

---

### 🧪 9. **Serverless & Eventing**

| Servizio       | Dettagli                                                  |
| -------------- | --------------------------------------------------------- |
| EventBridge    | ✅✅✅ (event buses, schedules, schema registry)          |
| SNS / SQS      | ✅✅✅ (pub/sub, DLQ, FIFO queues)                        |
| Step Functions | ✅✅ (orchestrazione workflow, express vs standard)       |
| API Gateway    | ✅✅✅ (REST & HTTP APIs, WebSocket APIs, custom domains) |

---

### 🧑‍🤝‍🧑 10. **Soft Skills & Leadership**

| Area                         | Dettagli                                                 |
| ---------------------------- | -------------------------------------------------------- |
| Architecture Decision Record | ✅✅ (documentare trade‑off, soluzioni)                  |
| Mentoring & Review           | ✅✅✅ (condivisione best practice, code review)         |
| Cost Management              | ✅✅ (Reserved Instances, Spot Instances, Savings Plans) |
| Incident Response            | ✅✅✅ (runbooks, on‑call, post‑mortem culture)          |

---

## 🏁 Sei un **Senior AWS Cloud Engineer** se:

✅ Hai progettato e gestito infrastrutture AWS complesse e resilienti  
✅ Usi IaC (CDK, CloudFormation, Terraform) per deploy ripetibili  
✅ Monitori e ottimizzi costi, performance e sicurezza in produzione  
✅ Hai implementato microservizi serverless e containerizzati su AWS  
✅ Mentori il team e prendi decisioni architetturali consapevoli

---

## 🎁 Starter Kit consigliato:

📦 **AWS Cloud Playground**

- 🏗️ **Terraform modules** per VPC, subnets, security groups
- 🐳 **ECS Fargate + ECR** demo con microservice Node.js
- ⚙️ **Lambda + API Gateway** demo con Terraform + Prism
- 🔐 **IAM roles & policies** minimali + AWS SSO example
- 📈 **CloudWatch dashboard** + **X‑Ray** tracing integrato
- 🎛️ **EventBridge + Step Functions** workflow di esempio
- 🚀 **GitHub Actions** con deploy su AWS (via OIDC)
- 📄 Documentazione C4 + README dettagliato

---

## 📘 Risorse & Libri x studiare:

- **YouTube**: [Angular Full Course - FreeCodeCamp](https://www.youtube.com/watch?v=htPYk6QxacQ) ▶️
- **Libri**:
  1. _"Pro Angular 9"_ di Adam Freeman 📚
  2. _"Angular Up and Running"_ di Shyam Seshadri 📚
