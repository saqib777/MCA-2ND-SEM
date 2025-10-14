
 ##🌩️ CLOUD COMPUTING NOTES


📘 5 MARKS QUESTIONS


1️⃣ Define Cloud Computing. Write Its Advantages. (Q1, Q7, Q12)
Cloud computing is the on-demand delivery of computing services—including servers, storage, databases, networking, software, and analytics—over the Internet on a pay-as-you-go basis.

Advantages:
• Cost Reduction: Lowers CapEx by removing the need for physical hardware.
• Scalability: Quickly scales up or down based on demand.
• High Availability & Reliability: Ensures uptime and disaster recovery across multiple data centers.
• Flexibility: Access services from anywhere through network connectivity.


2️⃣ Characteristics of Cloud Computing. (Q2, Q8, Q13)
According to NIST, the five essential characteristics are:
1. On-Demand Self-Service
2. Broad Network Access
3. Resource Pooling
4. Rapid Elasticity
5. Measured Service


3️⃣ Characteristics of PaaS Model. (Q3)
PaaS provides a complete cloud platform (hardware + OS + tools) for developing and managing apps.
• Focus on Development – Provider manages infrastructure.
• Affordable Access – Reduces cost of maintaining local tools.
• Faster Time to Market – Quick environment provisioning.
• Cost-Effective Scalability – Scales app resources easily.


4️⃣ Define Virtualization. How It Works in Cloud. (Q4)
Virtualization creates virtual versions of hardware, OS, or storage using a hypervisor.
• Function: Hypervisor divides hardware into multiple isolated VMs.
• Enables resource pooling and rapid elasticity, forming the base of cloud computing.

---
5️⃣ What is Cloud SLA? Explain. (Q5)
A Cloud Service Level Agreement defines the guaranteed service level between provider and customer.
• Metrics: Uptime, latency, support responsiveness.
• Breach & Redress: Compensation (usually service credits) if guarantees are not met.

---
6️⃣ Virtualization vs Cloud Computing. (Q6, Q10)
Feature | Virtualization | Cloud Computing
Definition | Abstracts hardware into VMs | Delivers virtual resources over the Internet
Scope | Single server or cluster | Global distributed resources
Necessity | Enables cloud computing | Uses virtualization as base
Payment Model | Fixed CapEx | Pay-as-you-go OpEx
Access | Local/private | Internet-based

---
7️⃣ Characteristics of IaaS Model. (Q9)
IaaS provides virtual infrastructure (VMs, storage, networking).
• Highest Level of Control
• Pay-per-Use
• High Reliability
• Ideal for high-performance computing, migrations, and hosting apps.

---
8️⃣ Characteristics of SaaS Model. (Q14)
SaaS delivers ready-to-use software via the Internet.
• Access via Browser
• Multitenant Architecture
• Provider manages all layers
• Easy Scalability
• Examples: Gmail, Salesforce, Google Workspace.

---
9️⃣ Cloud Monitoring vs Infrastructure Monitoring. (Q11)
Feature | Cloud Monitoring | Infrastructure Monitoring
Scope | Cloud-based services | On-premises hardware
Key Metrics | SLA, cost, app performance | CPU, uptime, logs
Goal | Optimize usage, manage costs | Maintain on-prem systems
Adaptability | Auto-scales with demand | Manual scalability

---
🔟 What is Cloud Monitoring? (Q15)
Cloud monitoring observes and analyzes cloud resource performance and security.
• Works via tools collecting metrics, logs, and traces.
• Ensures visibility, SLA compliance, and cost optimization.

---
11️⃣ What is Cloud Management Platform? (Q16)
CMP is software for managing and monitoring multi-cloud/hybrid environments.
• Purpose: Centralized management, consistency, and compliance.
• Functions: Cost control, policy enforcement, and self-service provisioning.

---
12️⃣ What is Cloud Orchestration? (Q17)
Cloud orchestration automates and coordinates multiple automated tasks into workflows.
• Links tasks like VM creation, database setup, and networking.
• Goal: Streamline operations and ensure consistency across resources.

---────────
📗 10 MARKS QUESTIONS
---────────

1️⃣ Types of Hardware Virtualization
• Type 1 (Bare-Metal): Runs directly on hardware. Examples: ESXi, Hyper-V.
• Type 2 (Hosted): Runs inside a host OS. Examples: VirtualBox.
• Paravirtualization: Modified guest OS communicates directly with hypervisor.

---
2️⃣ Cloud Computing Architecture
Divided into Frontend (Client) and Backend (Provider).
Frontend: Devices, browsers, user interface.
Backend: Infrastructure, virtualization, platforms, and applications.
Layers: Infrastructure → Platform → Application.
Managed by a Cloud Management Platform enabling elasticity and security.

---
3️⃣ Advantages and Disadvantages of SLA
✅ Advantages:
• Risk Mitigation
• Clarity & Trust
• Accountability
• Financial Compensation
❌ Disadvantages:
• Complexity
• Limited Downtime Coverage
• Vendor Lock-in
• Focus on uptime over performance metrics.

---
4️⃣ Applications of Edge Computing (Q4, Q9)
• Autonomous Vehicles
• Industrial IoT / Smart Factories
• Smart Retail
• Telesurgery / Remote Healthcare
• Content Delivery Networks (CDNs)

---
5️⃣ Types of Cloud Cost Models (Q5, Q10, Q14)
1. Pay-As-You-Go: Pay for actual usage.
2. Reserved Model: Commit to long-term usage for discounts.
3. Spot Instances: Bid for unused capacity (cheaper, interruptible).

---
6️⃣ Cloud Monitoring Tools
• APM Tools – New Relic, Dynatrace.
• Cloud-Native Tools – AWS CloudWatch, GCP Monitoring.
• Infrastructure Tools – Prometheus, SolarWinds.
• Cost Management – CloudHealth, CloudCheckr.

---
7️⃣ Capabilities of Cloud Management Platform
1. Multi-Cloud/Hybrid Management
2. Cost Optimization
3. Automation & Orchestration
4. Security & Compliance
5. Self-Service Portal

---
8️⃣ Benefits of Cloud Orchestration
• Operational Efficiency
• Faster Deployment
• Consistency & Governance
• Improved Security
• Automated Scalability

---
9️⃣ Total Cost of Ownership (TCO)
TCO = Total cost (direct + indirect) over lifecycle.
Phases:
1. On-Prem Costs: Hardware, software, staff.
2. Migration Costs: Labor, downtime.
3. Cloud Costs: Compute, storage, networking, management.
Helps validate migration, uncover hidden costs, and optimize expenses.

---────────
📙 15 MARKS QUESTIONS
---────────

1️⃣ Types of Cloud Computing (Q1, Q5, Q9)
A. Service Models:
• IaaS – Infrastructure resources
• PaaS – Development platforms
• SaaS – Ready-to-use apps
B. Deployment Models:
• Public Cloud
• Private Cloud
• Hybrid Cloud
• Community Cloud

---
2️⃣ Architecture of Cloud Computing (Q2, Q6, Q10)
Frontend – User interface, access.
Backend – Infrastructure, virtualization, management, and service layers.
Layers include:
• Resource Layer (Hardware)
• Virtualization Layer
• Management Layer (CMP)
• Service Layer (IaaS/PaaS/SaaS)

---
3️⃣ Types of Virtualization
• Hardware/Platform Virtualization
• OS Virtualization (Containers – Docker, Kubernetes)
• Network Virtualization (SDN, NFV)
• Storage Virtualization (Pooled Logical Storage)

---
4️⃣ Emerging Cloud Technologies (Q4, Q8, Q12)
• Serverless Computing – FaaS, event-driven execution.
• Edge Computing – Localized processing for IoT.
• Cloud-Native / Kubernetes – Microservices-based design.
• Cloud AI/ML Services – Pre-built intelligent APIs.

---
5️⃣ Cloud Orchestration Tools
• IaC Tools – Terraform, AWS CloudFormation.
• Container Orchestration – Kubernetes.
• CMPs – CloudBolt, VMware vRealize.
• Workflow Automation – AWS Step Functions, Jenkins.

---
6️⃣ VMware Infrastructure
Components:
• ESXi – Type 1 hypervisor managing VMs.
• vCenter Server – Central management system.
• VMFS – VMware file system for VMs.
Key Services:
• vMotion – Live VM migration.
• DRS – Dynamic resource balancing.
• HA – Automatic failover.
• vSAN – Software-defined storage.
• NSX – Software-defined networking.

---────────
📘 END NOTES
---────────
✅ Virtualization is the foundation of cloud computing.
✅ CMP and orchestration ensure automation and governance.
✅ SLAs and monitoring guarantee accountability.
✅ TCO and cost models help manage spending efficiently.
✅ Edge and serverless computing represent the next phase of cloud evolution.
---────────
