# AWS Knowledge Map

The knowledge map is the main navigation layer for this repository. It organizes learning by engineering domain and connects articles, labs, diagrams, system designs, and interview preparation.

> During Phase 1, links lead to section indexes. Individual article links will be added only after the articles are reviewed and published.

## Learning Paths

### 📖 Learn

| Domain | Core Topics |
|---|---|
| [Fundamentals](01-fundamentals/) | Global infrastructure → Shared responsibility → Well-Architected Framework |
| [Compute](02-compute/) | EC2 → AMIs → Load balancing → Auto Scaling → Lambda |
| [Storage](03-storage/) | S3 → EBS → EFS → FSx → Storage Gateway |
| [Networking](04-networking/) | VPC → Subnets → Routing → Network security → Hybrid connectivity |
| [Security](05-security/) | IAM → Encryption → Secrets → Detection → Protection |
| [Governance & Monitoring](06-governance-monitoring/) | Organizations → Control Tower → CloudTrail → Config → CloudWatch → Systems Manager |
| [Databases](07-databases/) | RDS/Aurora → DynamoDB → Caching → Selection and recovery |
| [Backup & Disaster Recovery](08-backup-disaster-recovery/) | AWS Backup → RPO/RTO → Restore testing → DR strategies |
| [Migration & Hybrid Cloud](09-migration-hybrid-cloud/) | Assessment → Migration → Windows/AD → Hybrid operations → Modernization |
| [Containers, DevOps & IaC](10-containers-devops-iac/) | Terraform/CloudFormation → CI/CD → Docker → ECS/EKS |
| [AI on AWS](11-ai-on-aws/) | Bedrock → AI-assisted engineering → Responsible use |

### 🧪 Practice

[Hands-on Labs](13-hands-on-labs/)

**Build → Validate → Break safely → Troubleshoot → Recover → Clean up → Reflect**

### 🏗 Architecture

[System Design](12-system-design/)

**Requirements → Constraints → Options → Decision → Trade-offs → Failure analysis → Validation**

### 🎯 Prepare

[Interview Preparation](14-interview-preparation/)

**Explain → Compare → Apply → Troubleshoot → Defend the decision**

## Interconnected Specialization Paths

### Windows Workloads on AWS

Fundamentals  
↓  
EC2  
↓  
Amazon FSx for Windows File Server  
↓  
Active Directory on AWS  
↓  
Systems Manager  
↓  
Backup and recovery  
↓  
Migration and hybrid operations  
↓  
Windows architecture and interview scenarios

### Backup and Disaster Recovery

Storage fundamentals  
↓  
EBS, EFS, S3, and FSx  
↓  
AWS Backup  
↓  
IAM and KMS  
↓  
RPO and RTO  
↓  
Restore testing  
↓  
Multi-AZ and multi-Region design  
↓  
Disaster-recovery architecture

### Cloud Migration and Hybrid Infrastructure

AWS foundations  
↓  
VPC and hybrid connectivity  
↓  
Identity and DNS  
↓  
Migration strategies  
↓  
Application Migration Service  
↓  
Workload validation  
↓  
Operational integration  
↓  
Modernization decisions

### Solutions Architect Development

Service fundamentals  
↓  
Hands-on validation  
↓  
Service comparisons  
↓  
Architecture trade-offs  
↓  
Well-Architected thinking  
↓  
System design  
↓  
Interview communication  
↓  
Architecture decision records

## Article Difficulty

- 🟢 **Beginner** — foundational concepts and core use cases
- 🟡 **Intermediate** — integrations, operational concerns, and architecture choices
- 🔴 **Advanced** — complex design, governance, resilience, migration, scale, or deep troubleshooting

## Article Connections

Every published article will include **Related Articles**. Connections should represent genuine learning or architecture dependencies, such as:

AWS Backup  
↓  
AWS IAM  
↓  
AWS KMS  
↓  
Amazon EBS / Amazon S3 / Amazon FSx  
↓  
RPO vs RTO  
↓  
Disaster Recovery Strategies  
↓  
Restore Testing

## Progress and Status

Use the [Master Roadmap](ROADMAP.md) to see which topics are planned, in progress, validated through hands-on work, published, or due for review.

## Navigation

- [Repository Home](README.md)
- [Master Roadmap](ROADMAP.md)
- [Article Template](ARTICLE-TEMPLATE.md)
- [Contribution Standards](CONTRIBUTING.md)

