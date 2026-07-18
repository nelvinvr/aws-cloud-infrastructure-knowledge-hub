# AWS Cloud Infrastructure Knowledge Hub

> **Learn deeply. Build deliberately. Explain clearly.**

Welcome to my personal cloud engineering knowledge base—a long-term collection of AWS concepts, hands-on experiments, architecture decisions, troubleshooting lessons, and interview-ready explanations.

This is not an “AWS notes” repository. It is a growing record of how I learn to think like a cloud infrastructure engineer and, ultimately, an AWS Solutions Architect.

---

## Welcome

I built this repository to connect three things that are often kept separate:

- **Learning** — understanding why AWS services exist and how they work
- **Practice** — testing concepts through hands-on labs and failure scenarios
- **Engineering judgment** — deciding when to use a service, when to avoid it, and which trade-offs matter

The goal is to create material that remains useful long after an exam: during interviews, architecture discussions, migrations, troubleshooting, and real production work.

## About Me

I'm **Nelvin Robinson**, an infrastructure professional building my career in AWS cloud engineering and Solutions Architecture.

My technical foundation comes from enterprise infrastructure environments, including:

- Windows Server administration
- Active Directory, Group Policy, DNS, and DHCP
- VMware vSphere and Hyper-V
- Server provisioning and troubleshooting
- Backup, restore, patching, and IT operations
- Enterprise-scale Windows workloads

I am now extending that foundation into AWS architecture, cloud operations, security, automation, migration, resilience, and AI-assisted infrastructure engineering.

My professional direction is:

> **AWS Cloud Infrastructure professional building Solutions Architect skills, specializing in Windows workloads, backup and disaster recovery, cloud migration, and hybrid enterprise environments.**

## Why This Repository Exists

AWS documentation explains what a service can do. Certification material helps organize what to study. This repository serves a different purpose: it captures how I understand and apply the technology.

Every topic is designed to answer questions such as:

- Why does this service exist?
- What problem does it solve?
- When should I use it—and when should I avoid it?
- What does it replace or complement?
- What are the security, reliability, operational, and cost trade-offs?
- How does it compare with similar choices?
- How would I explain it in an interview?
- How does it relate to Windows and enterprise infrastructure?
- What mistakes do beginners commonly make?
- What changed in my understanding after using it?

Over time, this repository will become both a technical reference and evidence of my engineering growth.

## Learning Philosophy

### Understand the problem before the service

I do not want to memorize a list of AWS features. I want to understand the customer or engineering problem that made the service necessary.

### Learn by building and breaking

A lab is more valuable when it tests behavior, failure, security, recovery, and troubleshooting—not only successful deployment.

### Think in trade-offs

There is rarely one universally “best” AWS service. The right decision depends on workload requirements, team capabilities, cost, security, availability, recovery objectives, and operational complexity.

### Explain concepts in my own words

If I cannot explain a concept simply, compare it with alternatives, and apply it to a scenario, I do not understand it deeply enough yet.

### Connect cloud learning to prior experience

Windows Server, Active Directory, virtualization, backup, and enterprise operations are not a past career to discard. They are the foundation from which I understand cloud infrastructure.


## AWS Learning Roadmap

This roadmap describes the direction of my learning rather than promising a fixed completion date.

### Phase 1 — Cloud infrastructure foundations

- AWS global infrastructure and shared responsibility
- IAM and account security
- VPC networking
- EC2, storage, load balancing, and scaling
- Monitoring, logging, governance, and cost awareness

### Phase 2 — Resilience, operations, and enterprise workloads

- Windows workloads on AWS
- Backup and disaster recovery
- High availability and multi-Region thinking
- Systems Manager and operational automation
- Hybrid identity, networking, storage, and management
- Migration assessment and modernization decisions

### Phase 3 — Infrastructure engineering

- Terraform and Infrastructure as Code
- CI/CD and GitHub Actions
- Containers, Docker, ECS, and Kubernetes
- Observability and incident response
- Security automation and policy-driven governance

### Phase 4 — Solutions Architecture

- Requirements discovery
- Architecture trade-off analysis
- AWS Well-Architected reviews
- System design
- Architecture decision records
- Cost, security, reliability, performance, and operational excellence

### Phase 5 — Specialization and modernization

- AWS security
- Windows and hybrid-cloud architecture
- Backup, disaster recovery, and business continuity
- Cloud migration and modernization
- AI-assisted cloud operations and generative AI on AWS

## Repository Structure

| Area | Purpose |
|---|---|
| [01-fundamentals](01-fundamentals/) | AWS foundations, cloud concepts, accounts, and global infrastructure |
| [02-compute](02-compute/) | EC2, Lambda, scaling, and load balancing |
| [03-storage](03-storage/) | S3, EBS, EFS, FSx, and storage decisions |
| [04-networking](04-networking/) | VPC, routing, connectivity, DNS, and content delivery |
| [05-security](05-security/) | Identity, encryption, detection, and application protection |
| [06-governance-monitoring](06-governance-monitoring/) | Organizations, logging, compliance, observability, and cost governance |
| [07-databases](07-databases/) | Relational, NoSQL, caching, and database selection |
| [08-backup-disaster-recovery](08-backup-disaster-recovery/) | Backup, restore, RPO, RTO, resilience, and recovery strategies |
| [09-migration-hybrid-cloud](09-migration-hybrid-cloud/) | Migration, Windows workloads, hybrid identity, networking, and storage |
| [10-containers-devops-iac](10-containers-devops-iac/) | Containers, CI/CD, Terraform, CloudFormation, and automation |
| [11-ai-on-aws](11-ai-on-aws/) | AWS AI services and AI-assisted cloud engineering |
| [12-system-design](12-system-design/) | Architecture patterns, design exercises, and decision records |
| [13-hands-on-labs](13-hands-on-labs/) | Build guides, validation evidence, failure tests, and retrospectives |
| [14-interview-preparation](14-interview-preparation/) | Interview explanations, scenarios, and question sets |
| [assets](assets/) | Architecture diagrams and supporting repository assets |

## Explore the Knowledge Hub

### 📖 Learn

- [Fundamentals](01-fundamentals/)
- [Compute](02-compute/)
- [Storage](03-storage/)
- [Networking](04-networking/)
- [Security](05-security/)
- [Governance & Monitoring](06-governance-monitoring/)
- [Databases](07-databases/)
- [Backup & Disaster Recovery](08-backup-disaster-recovery/)
- [Migration & Hybrid Cloud](09-migration-hybrid-cloud/)
- [Containers, DevOps & IaC](10-containers-devops-iac/)
- [AI on AWS](11-ai-on-aws/)

### 🧪 Practice

- [Hands-on Labs](13-hands-on-labs/)
- Failure testing and troubleshooting
- Restore and recovery validation
- Infrastructure as Code exercises

### 🏗 Architecture

- [System Design](12-system-design/)
- Architecture decision records
- Service comparison guides
- Resilience and migration patterns

### 🎯 Prepare

- [Interview Preparation](14-interview-preparation/)
- Scenario-based questions
- 30-second service explanations
- Architecture trade-off discussions

### 📝 Track Progress

- [Master Roadmap](ROADMAP.md)
- Article status
- Lab completion
- Publication and review status

## Topic Index

The [AWS Knowledge Map](knowledge-map.md) is the main navigation layer. It organizes content by engineering domain and connects related topics so that the repository reads like documentation rather than a folder of isolated notes.

Each article will carry a learning level:

- 🟢 **Beginner** — foundational concepts and core use cases
- 🟡 **Intermediate** — architecture choices, integrations, and operational trade-offs
- 🔴 **Advanced** — complex design, scale, governance, resilience, and deep troubleshooting

Articles will also include **Related Articles** so learning can continue naturally across connected services and engineering concepts.

## Hands-on Labs

Labs will document more than deployment steps. Where appropriate, each lab will include:

- Objective and architecture
- Prerequisites and estimated cost
- Implementation steps
- Security controls
- Validation tests
- Failure introduced intentionally
- Troubleshooting evidence
- Cleanup steps
- Lessons learned
- Improvements for a production design

A lab will only be marked complete when the result has been validated—not merely deployed.

## System Design

The system-design library will develop my ability to move from individual AWS services to complete solutions.

Design work will consider:

- Functional and non-functional requirements
- Availability and failure boundaries
- Security and identity
- Data flow and integration
- Backup, recovery, RPO, and RTO
- Scalability and performance
- Cost and operational complexity
- Migration constraints
- Windows and hybrid-enterprise dependencies
- Alternatives and rejected decisions

The goal is to show the reasoning behind an architecture, not only the final diagram.

## Interview Preparation

Interview preparation will be integrated with technical learning rather than maintained as disconnected question memorization.

Topics will include:

- Clear 30-second explanations
- “When would you use it?” questions
- Comparison and trade-off questions
- Troubleshooting scenarios
- Windows-to-AWS migration scenarios
- Backup and disaster-recovery discussions
- Architecture whiteboarding
- Lessons from hands-on failures

## Lessons from the Field

Relevant articles will include personal reflections such as:

- What confused me initially
- The misconception I corrected
- What finally made the concept click
- What surprised me during the lab
- The mistake I made
- How my enterprise infrastructure experience changed my interpretation
- What I would do differently in production

These reflections will be based on my own learning and experience. They are not presented as universal rules or copied course material.

## Distinctive Article Perspectives

### 💼 Windows & Enterprise Perspective

Where relevant, articles will connect AWS concepts to Windows Server, Active Directory, VMware, Hyper-V, backup platforms, enterprise operations, hybrid connectivity, and migration.

### 🧠 Architect's Thinking

Articles will move beyond “what the service does” to examine requirements, decision criteria, alternatives, trade-offs, failure modes, and operational ownership.

These sections will appear only where they add genuine value.

## Certifications

My certification direction supports the engineering roadmap; certifications are milestones, not the final goal.

- Build strong AWS foundations and hands-on project evidence
- Develop Solutions Architect-level design capability
- Target **AWS Certified Solutions Architect – Professional**
- Pursue **AWS Certified Security – Specialty** as the specialization most aligned with my long-term direction
- Consider an AWS AI certification later as a complementary modernization track

Certification status and completed milestones will be updated honestly as progress is made.

## Current Project Status

🚀 **Phase 1 — Foundation**

Current priorities:

- Professional repository homepage
- Scalable folder and navigation structure
- Master learning and publishing roadmap
- Consistent article template
- Contribution and quality standards
- AWS Knowledge Map

Quality is more important than speed. The repository will grow only as concepts are understood, validated, and documented responsibly.

## Ground Rules

- Everything is written in my own words.
- Technical concepts are supported by current official AWS documentation or my own hands-on evidence.
- Claims about projects, experience, and certifications remain accurate.
- Every article should remain useful six months later.
- Security, cost, reliability, and operational trade-offs are part of the explanation.
- Hands-on work includes validation and cleanup.
- Pages receive review dates because AWS services change.
- Quality always takes priority over publishing volume.

## Disclaimer

This repository is a personal learning and engineering portfolio. It is not official AWS documentation and is not affiliated with or endorsed by Amazon Web Services.

AWS service behavior, pricing, limits, features, and certification requirements can change. Readers should verify implementation decisions against current [official AWS documentation](https://docs.aws.amazon.com/) and their organization's technical, security, legal, and compliance requirements.

All company names, product names, and trademarks belong to their respective owners.

## Contact & LinkedIn

I welcome thoughtful conversations about AWS infrastructure, Windows workloads, backup and disaster recovery, migration, hybrid cloud, and Solutions Architecture.

- GitHub: [@nelvinvr](https://github.com/nelvinvr)
- LinkedIn: Link to be added before the Phase 1 release

---

> This repository is designed to grow with my career—from my first AWS cloud infrastructure role to designing secure, resilient, and practical enterprise solutions as an AWS Solutions Architect.

