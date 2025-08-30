---
tags:
  - Domain4
---

# Security+ Study Log

**Date:** August 29, 2025  
**Section/Module:** Security Operations - Threat Hunting, Root Cause Analysis, Training & Testing, Digital Forensics, Data Collection, Investigation (Domain 4)  
**Duration:** N/A  
**Course Progress:** Complete Security Operations Advanced Topics  

-----

## 📚 Today's Material Covered

- [x] Threat Hunting
- [x] Root Cause Analysis
- [x] Incident Response Training and Testing
- [x] Digital Forensic Procedures
- [x] Data Collection Procedures
- [x] Disk Imaging and Analysis
- [x] Investigating an Incident
- [x] Investigative Data

-----

## 🔑 Key Concepts & Definitions

### Threat Hunting

| Term | Definition | Domain |
|------|------------|---------|
| **Threat Hunting** | Cybersecurity technique designed to detect presence of threats that have not been discovered by normal security monitoring - proactive defense vs reactive | 4 |
| **Hypothesis** | Initial assumption about potential threats based on threat modeling and intelligence | 4 |
| **Threat Modeling** | Process of determining what potential events have highest likelihood and highest impact | 4 |
| **Threat Intelligence** | External information about threat actors, TTPs, and campaigns | 4 |
| **TTPs** | Tactics, Techniques, and Procedures used by threat actors | 4 |
| **Advisories and Bulletins** | Published information by vendors and security researchers about new TTPs and vulnerabilities | 4 |
| **Intelligence Fusion** | Using SIEM and threat analysis platforms to efficiently identify items of concern within logs | 4 |

### Root Cause Analysis

| Term | Definition | Domain |
|------|------------|---------|
| **Root Cause Analysis** | Systematic process to identify initial source of incident and prevent it from occurring again | 4 |
| **No-Blame Approach** | Investigation method that focuses on identifying causes rather than assigning blame to individuals | 4 |
| **Four-Step Process** | 1) Define scope 2) Determine causal relationships 3) Identify effective solution 4) Implement and track solution | 4 |

### Incident Response Training and Testing

| Term | Definition | Domain |
|------|------------|---------|
| **Training** | Education to ensure employees understand processes, procedures, and priorities during incident response | 4 |
| **Testing** | Practical exercise of incident response procedures to ensure knowledge application | 4 |
| **Tabletop Exercise (TTX)** | Exercise using incident response scenario against framework of controls - theoretical discussion | 4 |
| **Penetration Test** | Red team attempts intrusion into network using specific scenario based on threat modeling | 4 |
| **Simulation Exercise** | Realistic hands-on scenarios that mimic actual incidents in controlled environment | 4 |
| **Red Team** | Attackers in testing scenarios | 4 |
| **Blue Team** | Defenders in testing scenarios | 4 |
| **Rules of Engagement** | Clear methodology and guidelines that must be agreed upon before penetration testing | 4 |

### Digital Forensic Procedures

| Term | Definition | Domain |
|------|------------|---------|
| **Digital Forensics** | Systematic process of investigating and analyzing digital devices and data to uncover evidence for legal purposes | 4 |
| **Identification** | Securing scene, preventing evidence contamination, determining scope of evidence collection | 4 |
| **Collection** | Gathering evidence following proper authorization and acquisition procedures | 4 |
| **Analysis** | Using repeatable methods and tools for examination of evidence | 4 |
| **Reporting** | Documenting methods, tools, actions, findings, and conclusions | 4 |
| **Order of Volatility** | Systematic approach dictating sequence of data collection based on susceptibility to modification/loss | 4 |
| **Chain of Custody** | Documented verifiable record tracking handling, transfer, and preservation of digital evidence | 4 |
| **Disk Imaging** | Creating bit-by-bit or logical copy of storage device preserving entire content | 4 |
| **File Carving** | Extracting files and data fragments from storage media without relying on file system | 4 |
| **Legal Hold** | Formal notification instructing employees to preserve all potentially relevant electronic data | 4 |
| **E-discovery** | Process of identifying, collecting, and producing electronically stored information for legal proceedings | 4 |

### Order of Volatility (NIST SP 800-86)

| Step | Data Type | Description | Domain |
|------|-----------|-------------|---------|
| **1** | System Memory | Processor cache and system RAM | 4 |
| **2** | System State | System/network configurations, active sessions, data obtainable without altering system state | 4 |
| **3** | Storage Devices | Hard drives, SSDs, other non-volatile storage | 4 |
| **4** | Network Traffic/Logs | Data to reconstruct network activities and events | 4 |
| **5** | Remotely Stored Archive Data | Backups, cloud storage, external devices, printouts | 4 |

### Digital Forensic Ethics

| Principle | Description | Domain |
|-----------|-------------|---------|
| **Avoiding Bias** | Analysis performed without prejudice, based solely on evidence | 4 |
| **Repeatable Actions** | Using processes that others can perform to get same results | 4 |
| **Evidence Preservation** | Ensuring evidence is not changed or manipulated during investigation | 4 |

### Data Collection Procedures

| Term | Definition | Domain |
|------|------------|---------|
| **Data Acquisition** | Method and tools used to create forensically sound copy of data from source device | 4 |
| **Authorization** | Legal permission required before collecting evidence (warrant for law enforcement, executive approval for internal) | 4 |
| **Write Blocker** | Device preventing modification of storage media during forensic imaging | 4 |
| **Hashing** | Creating cryptographic fingerprint of data to verify integrity (MD5, SHA-1, SHA-256) | 4 |

### Investigative Data Sources

| Source Type | Description | Domain |
|-------------|-------------|---------|
| **SIEM** | Security Information and Event Management system providing real-time analysis of security alerts | 4 |
| **Log Files** | Records of events occurring in operating systems, software, or user communications | 4 |
| **Syslog/Rsyslog/Syslog-ng** | Systems permitting logging of data from different systems into central repository | 4 |
| **Journalctl** | Linux command line utility for querying and displaying logs from journald daemon | 4 |
| **NXLog** | Multi-platform log management tool for identifying security risks and policy breaches | 4 |
| **NetFlow** | Cisco protocol system collecting active IP network traffic flowing through interfaces | 4 |
| **SFlow** | Sampled Flow - open-source version of NetFlow providing truncated packet export | 4 |
| **IPFIX** | Internet Protocol Flow Information Export - universal standard for flow information export | 4 |
| **Metadata** | Data that describes other data - information about file creation, access times, etc. | 4 |

### Types of Log Files

| Log Type | Purpose | Domain |
|----------|---------|---------|
| **Network Logs** | Track traffic through routers and switches | 4 |
| **System Logs** | Record host/server activities | 4 |
| **Application Logs** | Monitor individual application activities | 4 |
| **Security Logs** | Monitor authentication events and security-related activities | 4 |
| **Web Logs** | Track web server access and proxy activities | 4 |
| **DNS Logs** | Record DNS server requests and responses | 4 |
| **Authentication Logs** | Track login/logout success and failures | 4 |
| **Dump Files** | Memory contents written to disk during system crashes | 4 |
| **VoIP Logs** | Voice over IP call metadata and recordings | 4 |

-----

## 📌 Important Points

### Threat Hunting Process
- **Proactive vs Reactive**: Threat hunting is proactive defense looking for threats within network instead of waiting for exploitation
- **Hypothesis-Driven**: Begins with threat modeling to determine highest likelihood/impact events
- **Intelligence Integration**: Combines threat intelligence with internal data for actionable insights  
- **Assumption of Failure**: Begins with assumption that existing rules have failed to create alerts for malicious activity
- **Continuous Evolution**: Threat actors modify TTPs when they become well-known, requiring constant adaptation

### Root Cause Analysis Best Practices
- **No-Blame Culture**: Focus on identifying systemic issues rather than individual fault
- **Four-Step Process**: Define scope → Determine causality → Identify solutions → Implement/track
- **Systematic Weaknesses**: Often reveals broader organizational vulnerabilities beyond single incident
- **Documentation Critical**: Thorough documentation enables others to verify and repeat analysis
- **Prevention Focus**: Primary goal is preventing recurrence, not punishment

### Training vs Testing vs Simulation
- **Training**: Educational process teaching what to do
- **Testing**: Practical verification that people know how to do it  
- **Simulation**: Comprehensive realistic exercises testing all aspects
- **Tabletop**: Cost-effective theoretical discussion but lacks hands-on experience
- **Penetration Testing**: Actual network intrusion with specific goals and rules of engagement
- **Full-Scale Exercise**: Most expensive but most comprehensive validation of capabilities

### Digital Forensic Chain of Custody
- **Documentation Critical**: Every evidence handling must be meticulously recorded
- **Integrity Verification**: Hashing used to verify evidence hasn't been altered
- **Legal Admissibility**: Proper procedures ensure evidence can withstand legal scrutiny
- **Defense Attorney Challenge**: Improper procedures can make evidence inadmissible in court
- **Liaison Importance**: Legal knowledge essential for maintaining proper procedures

### Order of Volatility Priorities
- **Most Volatile First**: Collect processor cache and RAM before they're overwritten
- **System State**: Capture configurations and active sessions without altering system
- **Storage Devices**: Image hard drives and SSDs while maintaining write protection
- **Network Data**: Collect traffic logs and network-related evidence
- **Archives Last**: Backups and static data have lowest collection priority

### Data Acquisition Considerations
- **Authorization Required**: Legal permission essential before evidence collection
- **Digital Crime Scene**: Different considerations than physical crime scenes
- **Live vs Dead Analysis**: Some data only available when system is running, some only when powered off
- **Windows Registry**: HKLM\Hardware hive only exists in memory, not on disk
- **Write Protection**: Use write blockers to prevent evidence contamination

### SIEM and Log Analysis
- **Sensor Sensitivity**: Configure appropriate logging levels to balance detail vs performance
- **Correlation Power**: Connect disparate events across multiple systems for pattern recognition
- **Trend Analysis**: Graphical analysis reveals patterns like increasing failed authentication attempts
- **Alert Tuning**: Balance between false positives and false negatives
- **Time Synchronization**: Critical for correlating events across different systems (use UTC)

### Flow Analysis vs Full Packet Capture
- **Storage Efficiency**: Flow analysis captures metadata only, significantly reducing storage requirements
- **Pattern Recognition**: Excellent for identifying bandwidth usage patterns and anomalies
- **Content Limitation**: Cannot see actual packet contents, only information about the data
- **Billing Applications**: IPFIX designed for service provider billing and accounting
- **Hybrid Approach**: Tools like Zeek sample traffic but capture full packets for interesting events

-----

## 🏷️ Domain Tags

**#Domain4** - Security Operations  
- Threat hunting methodologies and intelligence integration
- Root cause analysis and no-blame investigation approaches
- Incident response training, testing, and simulation exercises
- Digital forensic procedures and evidence handling
- Data collection techniques and order of volatility
- Investigative data sources and log analysis
- SIEM correlation and alert management
- Flow analysis and network traffic monitoring