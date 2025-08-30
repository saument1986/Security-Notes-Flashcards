---
tags:
  - Domain3
---
# Security+ Study Log

**Date:** August 16, 2025  
**Section/Module:** Data Backups, Continuity of Operations, Redundant Sites, Resilience Testing, Security Architecture, Cloud Security, Virtualization, Serverless, Microservices, Network Infrastructure, SDN, IaC, Centralized vs Decentralized  
**Duration:** N/A  
**Course Progress:** Objective 3.4  
**Domain:** 3 – Security Architecture  

-----

## 📚 Today’s Material Covered

- [x] Data Backups (onsite, offsite, RPO, encryption, snapshots, recovery, replication, journaling)  
- [x] Continuity of Operations Plans (BCP/DRP)  
- [x] Redundant Site Considerations (hot, warm, cold, mobile, virtual, platform diversity)  
- [x] Resilience & Recovery Testing (tabletop, failover, simulations, parallel processing)  
- [x] Security Architecture (on-prem, cloud, hybrid)  
- [x] Cloud Security Vulnerabilities (shared resources, VM isolation, access management, policies)  
- [x] Virtualization & Containerization (hypervisors, VM escape, resource reuse)  
- [x] Serverless Computing (FaaS, benefits, risks, vendor lock-in)  
- [x] Microservices (benefits, challenges, Netflix case study)  
- [x] Network Infrastructure (physical separation/air gapping, logical separation/VLANs)  
- [x] Software-Defined Networking (SDN planes, benefits, Google/AT&T case studies)  
- [x] Infrastructure as Code (IaC, idempotence, benefits, risks)  
- [x] Centralized vs Decentralized Architectures (benefits, risks, scalability, resiliency)  

-----

## 🔑 Key Concepts & Definitions

| Term | Definition |
| ---- | ---------- |
| Onsite Backup | Backup stored locally at same facility (quick access, disaster risk). |
| Offsite Backup | Backup stored in geographically separate site/cloud (disaster resilience). |
| Cloud Backup | Backup to remote servers via internet. |
| Backup Tape | Removable media for backups, often shipped offsite. |
| RPO (Recovery Point Objective) | Maximum acceptable data loss measured in time. |
| RTO (Recovery Time Objective) | Maximum acceptable downtime before restoration. |
| Snapshot | Point-in-time frozen copy of data capturing changes since prior snapshot. |
| Full/Traditional Backup | Backup type that copies all data each time. |
| Incremental Backup | Captures only changes since the last backup. |
| Differential Backup | Captures all changes since the last full backup. |
| Data-at-Rest Encryption | Protects stored backup data from unauthorized access. |
| Data-in-Transit Encryption | Protects backup data during transfer across networks. |
| Data Recovery | Restoring lost or corrupted data from backups. |
| Validation | Ensures restored data matches original data integrity. |
| Replication | Real-time/near real-time duplication of data across systems. |
| Journaling | Recording all data changes for rollback/audit. |
| Audit Trail | Chronological record of actions or changes. |
| Retention Policy | Defines how long backups/journals are stored. |
| Business Continuity Plan (BCP) | Organization’s plan to maintain operations during disruptions. |
| Disaster Recovery Plan (DRP) | Subset of BCP focusing on recovery after disasters. |
| Hot Site | Fully equipped redundant site, instant cutover capability. |
| Warm Site | Partially equipped site, can be operational in days. |
| Cold Site | Empty shell facility requiring setup, recovery in weeks. |
| Mobile Site | Portable/tent-based facility for recovery (e.g., DJC2). |
| Virtual Site | Cloud-based redundant environment for rapid scalability. |
| Platform Diversity | Using different vendors/OS/hardware to reduce single point of failure risk. |
| Tabletop Exercise | Scenario-based discussion of incident response. |
| Failover Test | Controlled test of switching to backup systems. |
| Simulation | Virtual attack/incident environment to test response. |
| Parallel Processing | Running primary and backup systems together for testing. |
| On-Premises Infrastructure | Local servers/data centers managed directly by org. |
| Cloud Computing | Delivery of computing services over the internet. |
| Hybrid Cloud | Combination of on-prem + cloud solutions. |
| Responsibility Matrix | Defines shared security responsibilities between provider & customer. |
| Third-Party Vendor | External service providers supporting cloud operations. |
| Shared Resource Vulnerability | Multi-tenant cloud risk if isolation fails. |
| Virtual Machine (VM) | Emulated computer running an OS on shared physical hardware. |
| Hypervisor (Type 1) | Bare-metal hypervisor running directly on host hardware. |
| Hypervisor (Type 2) | Hosted hypervisor running within an OS. |
| VM Escape | Exploit allowing attacker to break isolation and reach hypervisor. |
| Privilege Escalation | Gaining higher-level rights (e.g., admin) illegitimately. |
| Live VM Migration | Moving VMs between hosts without downtime. |
| Resource Reuse Vulnerability | Leakage of old data if resources not cleared properly. |
| Containerization | Running apps in isolated containers sharing same OS kernel. |
| Docker | Popular containerization platform. |
| Kubernetes | Container orchestration framework. |
| Serverless | Cloud computing model where provider manages servers (e.g., AWS Lambda). |
| Function-as-a-Service (FaaS) | Event-driven serverless execution of code. |
| Vendor Lock-in | Dependency on one provider’s ecosystem. |
| Microservices | Architectural style breaking apps into independent services. |
| API (Application Programming Interface) | Standard communication method between microservices. |
| Air Gap | Physically isolated system with no network connection. |
| VLAN (Virtual LAN) | Logically separated network segment on shared physical hardware. |
| DMZ (Demilitarized Zone) | Segmented subnet for external-facing services. |
| SDN (Software Defined Networking) | Centralized, programmable network architecture. |
| Control Plane | SDN component making routing/traffic decisions. |
| Data Plane | SDN component forwarding packets. |
| Application Plane | SDN apps interfacing with controller to dictate policies. |
| Infrastructure as Code (IaC) | Managing infrastructure through scripts/templates. |
| Idempotence | Ensures IaC produces same result no matter how many times run. |
| Centralized Architecture | All computing/data controlled from single server/authority. |
| Decentralized Architecture | Computing spread across multiple nodes, no single control point. |

-----

## 📌 Important Points

### Data Backups
- Onsite backups = fast access, disaster risk.  
- Offsite backups = resilience against local loss.  
- RPO determines backup frequency.  
- Encrypt backups at rest & in transit.  
- Snapshots capture point-in-time efficiently.  
- Recovery must be tested monthly.  
- Replication = continuous availability.  
- Journaling provides auditability & granular recovery.  

### Continuity of Operations (BCP/DRP)
- BCP = overarching continuity planning.  
- DRP = subset focused on disaster recovery.  
- Senior management drives BCP/DRP.  
- Committees include IT, legal, comms, ops.  
- Must define recovery priorities, scope, and acceptable risks.  

### Redundant Site Considerations
- **Hot Site**: Fully operational, instant cutover, costly.  
- **Warm Site**: Partially ready, operational in days.  
- **Cold Site**: Empty shell, operational in weeks.  
- **Mobile Site**: Portable recovery unit.  
- **Virtual Site**: Cloud-based flexible recovery.  
- Platform diversity prevents systemic failures (e.g., Cisco vuln).  

### Resilience & Recovery Testing
- **Tabletop**: Discussion exercise.  
- **Failover Test**: Execute cutover.  
- **Simulation**: Virtualized/live-fire exercise.  
- **Parallel Processing**: Run both systems together to test.  
- Regular testing required, not one-time.  

### Security Architecture: On-Prem vs Cloud vs Hybrid
- On-prem: control & security, higher cost.  
- Cloud: scalability, cost-effective, vendor-managed infra.  
- Hybrid: balance between control and scalability.  
- Responsibility matrix defines provider vs customer duties.  

### Cloud Security
- Risks: shared resources, weak VM isolation, weak access mgmt.  
- Solutions: strong multi-tenancy, hypervisor hardening, MFA.  
- Data remnants a risk if deletion incomplete.  
- Policies must be clear and updated regularly.  

### Virtualization & Containerization
- Hypervisors: Type 1 = bare metal, Type 2 = hosted.  
- Containers: lightweight, share OS kernel.  
- VM Escape: attacker breaks isolation.  
- Privilege escalation on hypervisors dangerous.  
- Resource reuse leaks old data.  
- VM sprawl = too many untracked VMs → risk.  
- Mitigation: patching, segmentation, encryption, isolation.  

### Serverless
- Code runs on-demand (AWS Lambda, GCP Functions).  
- Benefits: no infra mgmt, cost savings, auto scaling.  
- Risks: vendor lock-in, evolving best practices.  

### Microservices
- Break monolithic apps into small services.  
- Benefits: scalability, resilience, independent deployment.  
- Risks: network latency, complexity, data consistency.  
- Netflix migrated to microservices to scale globally.  

### Network Infrastructure
- **Physical separation (Air Gaps)**: Military/ICS networks.  
- **Logical separation**: VLANs, firewalls, DMZ.  
- Air gaps most secure, but not infallible (e.g., Stuxnet).  

### SDN (Software Defined Networking)
- Separates planes: control, data, application.  
- Centralized programmability → more efficient mgmt.  
- Google B4: used SDN to optimize global data centers.  
- AT&T Domain 2.0: cost reduction, automation.  

### Infrastructure as Code (IaC)
- Infrastructure defined in YAML/JSON/HCL templates.  
- Ensures consistency across environments.  
- **Idempotence** = runs produce identical outcomes.  
- Benefits: speed, consistency, auditability.  
- Risks: complexity, skill requirements, misconfiguration.  

### Centralized vs Decentralized Architectures
- **Centralized**: efficiency, consistency, single point of failure.  
- **Decentralized**: resilient, scalable, but harder to manage.  
- Choice depends on org priorities (control vs flexibility).  

-----

## 🏷️ Domain Tags

**#Domain3** – Security Architecture  
- Data backups and replication  
- Continuity of operations and disaster recovery  
- Redundant site considerations  
- Resilience and recovery testing methods  
- Cloud vs on-premises security architecture  
- Cloud security vulnerabilities  
- Virtualization and containerization risks  
- Serverless & microservices design tradeoffs  
- Network infrastructure separation methods  
- Software-Defined Networking (SDN)  
- Infrastructure as Code (IaC) principles  
- Centralized vs decentralized architectures  
