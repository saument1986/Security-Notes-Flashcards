---
tags:
  - Domain4
---

# Security+ Study Log

**Date:** August 28, 2025  
**Section/Module:** Alerting and Monitoring (Objective 4.4)  
**Duration:** N/A  
**Course Progress:** Complete Alerting and Monitoring Section  

-----

## 📚 Today's Material Covered

- [x] Alerting and Monitoring Overview
- [x] Monitoring Resources (Systems, Applications, Infrastructure)
- [x] Alerting and Monitoring Activities (Log Aggregation, Alerting, Scanning, Reporting, Archiving, Alert Response)
- [x] Simple Network Management Protocol (SNMP)
- [x] Security Information and Event Management (SIEM)
- [x] Data from Security Tools
- [x] Security Content Automation Protocol (SCAP)
- [x] NetFlow and Flow Analysis
- [x] Single Pane of Glass
- [x] Incident Response Overview and Process

-----

## 🔑 Key Concepts & Definitions

### Alerting and Monitoring Fundamentals

| Term | Definition | Domain |
|------|------------|---------|
| **Alerting** | Process of notifying relevant personnel when a potential security incident occurs | 4 |
| **Monitoring** | Continuous observation of a system or network to detect anomalies, intrusions, and other potential security threats | 4 |
| **Baseline** | Set of established performance metrics and data points representing typical or expected behavior of a system under normal operating conditions | 4 |
| **True Positive** | Alert that correctly identifies a legitimate issue or threat | 4 |
| **False Positive** | Alert that incorrectly indicates presence of a threat when there isn't one | 4 |
| **True Negative** | Absence of alert when there is indeed no issue or threat (system correctly recognized safety) | 4 |
| **False Negative** | System fails to create alert when there is a real issue or threat (most dangerous scenario) | 4 |

### Monitoring Categories

| Category | Purpose | Domain |
|----------|---------|---------|
| **System Monitoring** | Observing performance of computer systems (CPU utilization, memory consumption, disk usage, network performance) | 4 |
| **Application Monitoring** | Managing and monitoring performance and availability of software applications by tracking errors, bottlenecks, and issues | 4 |
| **Infrastructure Monitoring** | Observing performance and availability of organization's physical and virtual infrastructure | 4 |
| **Automated Monitoring** | Using software tools to automatically scan and analyze network logs, system logs, network traffic for malicious activity | 4 |
| **Manual Monitoring** | Using human personnel to actively review and analyze system data to detect potential security issues | 4 |

### Alerting and Monitoring Activities

| Activity | Description | Domain |
|----------|-------------|---------|
| **Log Aggregation** | Process of collecting and consolidating log data from various sources into a centralized location | 4 |
| **Alerting** | Setting up notifications to inform relevant stakeholders when specific events or conditions occur | 4 |
| **Scanning** | Regularly examining systems, networks, or applications to identify vulnerabilities, configuration issues, or other potential problems | 4 |
| **Reporting** | Generating summaries or detailed reports based on collected and analyzed data | 4 |
| **Archiving** | Storing data for long retention periods or future reference | 4 |
| **Alert Response** | Taking appropriate actions in response to alerts, including investigation, escalation, or initiating predefined response procedures | 4 |
| **Remediation** | Steps used to resolve identified issues or vulnerabilities (patching, reconfiguring services, modifying source code) | 4 |
| **Validation** | Verifying that remediation implemented was successful and effectively addressed the vulnerability or issue | 4 |
| **Quarantining** | Isolating a system, network, or application to prevent spread of threat and limit potential impact | 4 |
| **Alert Tuning** | Adjusting alert parameters to reduce errors, false positives, and improve overall relevance of alerts | 4 |

### SNMP Protocol Components

| Component | Function | Domain |
|-----------|----------|---------|
| **SNMP Manager** | Machine running SNMP protocol to collect and process information from network devices | 4 |
| **SNMP Agent** | Network devices sending information about themselves over the network back to manager | 4 |
| **Management Information Base (MIB)** | Translation file consolidating and storing individual OIDs with structure and details | 4 |
| **Object Identifier (OID)** | Unique identifier for variables that can be read or set via SNMP | 4 |
| **Set Request** | Manager to agent request to change the value of a variable or list of variables | 4 |
| **Get Request** | Manager to agent request to retrieve the value of a variable or list of variables | 4 |
| **Trap Message** | Asynchronous notifications sent from agent to manager without being requested | 4 |

### SNMP Versions and Security

| Version | Security Features | Vulnerabilities | Domain |
|---------|------------------|----------------|---------|
| **SNMP v1** | Plain text community strings (public read-only, private read-write) | Highly insecure, vulnerable to attack | 4 |
| **SNMP v2** | Plain text community strings | Same vulnerabilities as v1 | 4 |
| **SNMP v3** | Integrity (hashing), Authentication (source validation), Confidentiality (DES/3DES/AES encryption) | Most secure version | 4 |

### SNMP Trap Types

| Trap Type | Description | Domain |
|-----------|-------------|---------|
| **Granular Traps** | Each SNMP trap message sent with unique OID, consolidated in MIB, bandwidth efficient | 4 |
| **Verbose Traps** | Contains all information about alert/event as payload, uses more resources and bandwidth | 4 |
| **Variable Binding** | Key-value pair configuration for storing data in SNMP traps | 4 |

### SIEM (Security Information and Event Management)

| Component | Purpose | Domain |
|-----------|---------|---------|
| **SIEM** | Solution providing real-time or near real-time analysis of security alerts generated by network hardware and applications | 4 |
| **Agent-Based SIEM** | Small software installed on each system to collect log data and send to SIEM for processing | 4 |
| **Agentless SIEM** | Directly collects log data from systems using standard protocols like SNMP or WMI | 4 |
| **Correlation** | SIEM's ability to connect disparate events from different systems to identify suspicious patterns | 4 |

### Popular SIEM Solutions

| Solution | Description | Domain |
|----------|-------------|---------|
| **Splunk** | Market-leading big data information-gathering and analysis tool with proprietary Search Processing Language | 4 |
| **ELK/Elastic Stack** | Collection of free and open source tools: Elasticsearch, Logstash, Kibana, Beats | 4 |
| **ArcSight** | SIEM log management and analytics software for compliance reporting (HIPAA, SOX, PCI DSS) | 4 |
| **QRadar** | IBM's SIEM log management analytics and compliance reporting platform | 4 |

### Security Tools Data Sources

| Tool Type | Data Generated | Domain |
|-----------|----------------|---------|
| **Antivirus Software** | Malware detection logs, system scans, updates | 4 |
| **Data Loss Prevention (DLP)** | Potential data leaks, policy violations, suspicious user activities | 4 |
| **Network Intrusion Detection (NIDS)** | Detected threats, network anomalies (passive identification) | 4 |
| **Network Intrusion Prevention (NIPS)** | Blocked traffic, prevented threats (proactive blocking) | 4 |
| **Firewalls** | Allowed/blocked traffic, rule changes, detected threats | 4 |
| **Vulnerability Scanners** | Identified vulnerabilities, severity levels, remediation recommendations | 4 |

### SCAP (Security Content Automation Protocol)

| Component | Purpose | Domain |
|-----------|---------|---------|
| **SCAP** | Suite of open standards enhancing automation of vulnerability management, measurement, and policy compliance evaluation | 4 |
| **OVAL** | Open Vulnerability and Assessment Language - XML schema for describing system security states | 4 |
| **XCCDF** | Extensible Configuration Checklist Description Format - XML schema for developing and auditing best-practice configuration checklists | 4 |
| **ARF** | Asset Reporting Format - XML schema for expressing information about assets and relationships between assets and reports | 4 |

### SCAP Enumeration Methods

| Method | Purpose | Domain |
|--------|---------|---------|
| **CCE (Common Configuration Enumeration)** | Scheme for provisioning secure configuration checks across multiple sources | 4 |
| **CPE (Common Platform Enumeration)** | Scheme for identifying hardware devices, operating systems, and applications | 4 |
| **CVE (Common Vulnerabilities and Exposures)** | List of records with unique identifiers for publicly known vulnerabilities | 4 |

### CVSS (Common Vulnerability Scoring System)

| Score Range | Severity Level | Domain |
|-------------|----------------|---------|
| **0** | None | 4 |
| **0.1 - 3.9** | Low | 4 |
| **4.0 - 6.9** | Medium | 4 |
| **7.0 - 8.9** | High | 4 |
| **9.0 - 10.0** | Critical | 4 |

### Flow Analysis and NetFlow

| Concept | Description | Domain |
|---------|-------------|---------|
| **Flow Analysis** | Recording metadata and statistics about network traffic rather than recording each frame | 4 |
| **Full Packet Capture (FPC)** | Capturing entire packet including header and payload (storage intensive) | 4 |
| **NetFlow** | Cisco-developed means of reporting network flow information to structured database | 4 |
| **IPFIX** | IP Flow Information Export - standardized version of NetFlow | 4 |
| **Flow Collector** | Means of recording metadata and statistics about network traffic, samples network traffic | 4 |
| **Zeek** | Hybrid tool that passively monitors network and logs full packet captures based on data of potential interest | 4 |
| **MRTG** | Multi Router Traffic Grapher - creates graphs showing network traffic flows through network interfaces | 4 |

### Single Pane of Glass

| Aspect | Description | Domain |
|--------|-------------|---------|
| **Single Pane of Glass** | Central point of access for all information, tools, and systems security team needs to monitor, manage, and secure IT environment | 4 |
| **Benefits** | Simplifies management, improves efficiency, enhances collaboration, aids compliance | 4 |
| **Implementation Steps** | 1) Define requirements 2) Identify/integrate data sources 3) Customize interface 4) Develop SOPs 5) Continuous monitoring/maintenance | 4 |

### Incident Response Process

| Phase | Activities | Domain |
|-------|------------|---------|
| **Preparation** | Making systems resilient, hardening systems/networks, writing policies/procedures, creating communication plans, training | 4 |
| **Detection** | Determining whether security incident has occurred, categorizing and assessing potential incident severity | 4 |
| **Analysis** | Thoroughly examining and evaluating incident, understanding scope and impact, notifying stakeholders | 4 |
| **Containment** | Limiting scope and magnitude of incident, securing data, minimizing impact on business operations | 4 |
| **Eradication** | Removing malicious activity from system or network after incident is contained | 4 |
| **Recovery** | Restoring affected systems and services to normal secured state, implementing configuration updates | 4 |
| **Post-Incident Activity** | Analyzing incident and response, identifying improvements, conducting root cause analysis, lessons learned, after-action report | 4 |

### Root Cause Analysis Process

| Step | Description | Domain |
|------|-------------|---------|
| **1. Define/Scope Incident** | Clearly identify and define the boundaries of the incident | 4 |
| **2. Determine Causal Relationship** | Identify the chain of events that led to the incident | 4 |
| **3. Identify Effective Solution** | Develop appropriate remediation strategies | 4 |
| **4. Implement and Track Solutions** | Deploy fixes and monitor to ensure incident is fully resolved | 4 |

-----

## 📌 Important Points

### Alert Classification Strategy
- **Goal**: Maximize true positives while minimizing false positives
- **False Negative Risk**: Most dangerous scenario - real threats go undetected
- **Alert Fatigue**: Too many false positives can cause security personnel to ignore alerts
- **Tuning Necessity**: Regular adjustment of alert thresholds and conditions

### SNMP Security Evolution
- **Version 1 & 2**: Plain text community strings make them highly vulnerable
- **Default Strings**: "public" (read-only) and "private" (read-write) are major security risks
- **Version 3 Benefits**: Added integrity (hashing), authentication (source validation), and confidentiality (encryption)
- **Group-Based Security**: SNMP v3 allows creation of groups with different authorization levels

### SIEM Implementation Considerations
- **Seven Critical Factors**: 1) Log relevant events 2) Establish event scope 3) Develop use cases 4) Plan incident response 5) Establish ticketing 6) Schedule threat hunting 7) Provide audit trails
- **Correlation Power**: Ability to connect events across disparate systems (e.g., VPN login from Asia + physical badge access in NYC)
- **Implementation Options**: Software, hardware appliances, or outsourced managed service
- **Agent Trade-offs**: Agent-based provides more detail and real-time data but requires maintenance; agentless is easier but less detailed

### SCAP Benchmarking
- **Purpose**: Standardized approach to maintaining system security through automation
- **XCCDF Benefits**: Machine-readable format replacing lengthy manual checklists
- **Vendor Neutrality**: Works across different tools and platforms
- **Popular Benchmarks**: Red Hat Enterprise Linux, CIS Microsoft Windows 10 Enterprise

### Flow Analysis vs Full Packet Capture
- **Storage Efficiency**: Flow analysis saves significant storage space by collecting metadata only
- **Content Limitation**: Flow analysis doesn't capture actual packet contents, only information about the data
- **Pattern Recognition**: Excellent for identifying trends, patterns, and anomalies in network traffic
- **Zeek Advantage**: Best of both worlds - samples data like flow analysis but logs full packets for interesting events

### Incident Response Team Structure
- **Core Team**: Cybersecurity professionals with incident response experience
- **Temporary Members**: Subject matter experts brought in for specific incidents (e.g., database administrators)
- **Leadership Requirements**: Management must provide funding, resources, expertise, and make critical business decisions
- **Outsourcing Considerations**: Specialized expertise but expensive and requires network learning time

### Single Pane of Glass Benefits
- **Unified Visibility**: All security information in one location eliminates multiple system logins
- **Automation Opportunities**: Reduces repetitive tasks, allows focus on critical activities
- **Collaboration Enhancement**: Improves information sharing and coordination within security teams
- **Compliance Support**: Easier generation of required reports and documentation

-----

## 🏷️ Domain Tags

**#Domain4** - Security Operations  
- Alerting and monitoring concepts and implementation
- SNMP protocol versions and security considerations
- SIEM architecture and correlation capabilities
- Security tool data integration and analysis
- SCAP standards for vulnerability management automation
- Network flow analysis and traffic monitoring
- Centralized security operations management
- Incident response process and team structure