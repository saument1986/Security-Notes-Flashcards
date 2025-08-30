---
tags:
  - Domain2
  - Domain3
  - Domain4
---

# Security+ Study Log

**Date:** August 23, 2025  
**Section/Module:** Wireless Security, Application Security, Network Access Control, Web/DNS Filtering, Email Security, EDR, User Behavior Analytics, Secure Protocols  
**Duration:** N/A  
**Course Progress:** Multiple Objectives Covered  

-----

## 📚 Today's Material Covered

- [x] Wireless Security Settings (WEP, WPA, WPA2, WPA3)
- [x] AAA protocols (RADIUS, TACACS+)
- [x] EAP authentication protocols
- [x] Application Security (Input validation, Secure cookies, Static/Dynamic code analysis, Code signing, Sandboxing)
- [x] Network Access Control (NAC)
- [x] Web and DNS Filtering
- [x] Email Security (DKIM, SPF, DMARC, Email gateways, Spam filtering)
- [x] Endpoint Detection and Response (EDR/XDR/FIM)
- [x] User Behavior Analytics (UBA/UEBA)
- [x] Selecting Secure Protocols (HTTPS vs HTTP, SFTP vs FTP, SSH vs Telnet)

-----

## 🔑 Key Concepts & Definitions

### Wireless Security Standards

| Term | Definition | Domain |
|------|------------|---------|
| **WEP (Wired Equivalent Privacy)** | Outdated 1999 wireless security standard using static 64/128-bit keys, easily cracked in 3 minutes | 4 |
| **WPA (Wi-Fi Protected Access)** | 2003 interim security enhancement using TKIP, but still vulnerable to cryptographic attacks | 4 |
| **WPA2** | 2004 standard using AES encryption with CCMP, vulnerable to KRACK attacks | 4 |
| **WPA3** | Latest wireless security standard with SAE, Enhanced Open, updated cryptographic protocols, and management frame protection | 4 |
| **SAE (Simultaneous Authentication of Equals)** | WPA3 key establishment protocol replacing pre-shared keys, uses Diffie-Hellman key agreement | 4 |
| **Enhanced Open (OWE)** | WPA3 feature providing individualized encryption for open networks without authentication | 4 |
| **AES GCMP** | WPA3's Galois Counter Mode protocol supporting 128-bit (personal) and 192-bit (enterprise) encryption | 4 |
| **Management Frame Protection** | WPA3 requirement to protect against key recovery attacks and network disruption | 4 |

### AAA Protocols

| Term | Definition | Domain |
|------|------------|---------|
| **RADIUS** | Remote Authentication Dial-In User Service - centralized AAA protocol for network access | 4 |
| **TACACS+** | Terminal Access Controller Access-Control System Plus - separates AAA functions, encrypts entire process | 4 |
| **EAP (Extensible Authentication Protocol)** | Authentication framework supporting multiple methods for wireless and point-to-point connections | 4 |
| **PEAP** | Protected EAP - encapsulates EAP within encrypted TLS tunnel, requires dual-sided certificates | 4 |
| **EAP-TTLS** | EAP Tunneled TLS - requires certificate only on server side, encapsulates second protocol | 4 |
| **EAP-FAST** | EAP Flexible Authentication via Secure Tunneling - Cisco protocol for secure roaming | 4 |

### Application Security

| Term | Definition | Domain |
|------|------------|---------|
| **Input Validation** | Security practice ensuring applications only process well-defined, uncontaminated data | 2 |
| **Front-end Validation** | Client-side data validation before submission (can be bypassed) | 2 |
| **Back-end Validation** | Server-side data validation (more secure but resource-intensive) | 2 |
| **Secure Cookies** | Cookies transmitted over HTTPS with proper security attributes (Secure, HttpOnly, SameSite) | 2 |
| **Static Code Analysis (SAST)** | Reviewing source code before execution to identify vulnerabilities | 2 |
| **Dynamic Code Analysis (DAST)** | Testing applications while running to find runtime vulnerabilities | 2 |
| **Fuzzing** | Automated injection of malformed data to test for crashes and vulnerabilities | 2 |
| **Stress Testing** | Evaluating system stability under extreme conditions | 2 |
| **Code Signing** | Digital signature confirming software authenticity and integrity | 2 |
| **Sandboxing** | Isolating programs to limit resource access and system changes | 2 |

### Network Access Control

| Term | Definition | Domain |
|------|------------|---------|
| **Network Access Control (NAC)** | Security system scanning devices before allowing network access | 4 |
| **Persistent Agents** | Software installed on devices for continuous NAC monitoring | 4 |
| **Non-persistent Agents** | Temporary software downloaded for one-time device scanning | 4 |
| **802.1x** | IEEE standard for port-based network access control | 4 |
| **Adaptive NAC** | Dynamic reevaluation of device authorization based on behavior | 4 |
| **Time-based Access** | Network access restricted by time schedules | 4 |
| **Location-based Access** | Network access evaluated by geographic location | 4 |
| **Role-based Access** | Access permissions based on device/user role | 4 |

### Web and DNS Filtering

| Term | Definition | Domain |
|------|------------|---------|
| **Web Filtering** | Content filtering technique restricting internet access based on policies | 4 |
| **Agent-based Filtering** | Software installed on devices to enforce web policies | 4 |
| **Centralized Proxy** | Server acting as intermediary to evaluate and filter web requests | 4 |
| **URL Scanning** | Analyzing website URLs against databases of known malicious sites | 4 |
| **Content Categorization** | Classifying websites by content type for filtering policies | 4 |
| **Reputation-based Filtering** | Blocking/allowing sites based on third-party reputation scores | 4 |
| **DNS Filtering** | Preventing domain name resolution to IP addresses for blocked sites | 4 |

### Email Security

| Term | Definition | Domain |
|------|------------|---------|
| **DKIM** | Domain Keys Identified Mail - digital signature in email headers for authenticity | 4 |
| **SPF** | Sender Policy Framework - prevents email spoofing by verifying sender IP authorization | 4 |
| **DMARC** | Domain-based Message Authentication, Reporting & Conformance - email validation using DKIM/SPF | 4 |
| **Email Gateway** | Server managing email transfer between internet and local network | 4 |
| **SMTP** | Simple Mail Transfer Protocol - for sending emails (port 25 insecure, 587 secure) | 4 |
| **Spam Filtering** | Process detecting unwanted emails using content analysis and Bayesian filtering | 4 |

### Endpoint Detection and Response

| Term | Definition | Domain |
|------|------------|---------|
| **EDR (Endpoint Detection and Response)** | Security tools monitoring endpoints for threats with automated response capabilities | 4 |
| **XDR (Extended Detection and Response)** | Integrated security platform correlating data across multiple security layers | 4 |
| **File Integrity Monitoring (FIM)** | Validates integrity of system files using hash comparison against known baselines | 4 |
| **Data Collection** | First EDR step gathering endpoint data (processes, registry, memory, network traffic) | 4 |
| **Data Consolidation** | Centralized storage and analysis of collected endpoint data | 4 |
| **Threat Detection** | Using signature-based and behavior-based detection techniques | 4 |
| **Automated Response** | System-initiated actions like endpoint isolation or threat containment | 4 |

### User Behavior Analytics

| Term | Definition | Domain |
|------|------------|---------|
| **UBA (User Behavior Analytics)** | Cybersecurity strategy using big data and ML to analyze user behaviors and detect anomalies | 4 |
| **UEBA** | User and Entity Behavior Analytics - extends UBA to include devices, routers, servers | 4 |
| **Behavioral Baseline** | Established pattern of normal user activity for comparison | 4 |
| **Anomaly Detection** | Identifying deviations from established behavioral patterns | 4 |
| **Insider Threat Detection** | Identifying malicious activities from authorized users | 4 |
| **Machine Learning Algorithms** | Automated systems learning normal behavior patterns over time | 4 |

### Secure Protocol Selection

| Term | Definition | Domain |
|------|------------|---------|
| **HTTPS vs HTTP** | Secure (port 443) vs insecure (port 80) web protocols | 4 |
| **SFTP vs FTP** | Secure file transfer via SSH tunnel vs plaintext file transfer | 4 |
| **SSH vs Telnet** | Secure shell (encrypted) vs plaintext remote administration | 4 |
| **IMAPS vs IMAP** | Secure (port 993) vs insecure (port 143) email retrieval | 4 |
| **POP3S vs POP3** | Secure (port 995) vs insecure (port 110) email retrieval | 4 |
| **SMTPS vs SMTP** | Secure (port 587) vs insecure (port 25) email sending | 4 |
| **TCP vs UDP** | Connection-oriented reliable vs connectionless fast transport protocols | 4 |

-----

## 📌 Important Points

### Wireless Security Evolution
- **WEP**: 24-bit initialization vector weakness, crackable in 3 minutes
- **WPA**: TKIP implementation vulnerabilities, lack of sufficient data integrity checks
- **WPA2**: AES CCMP encryption, vulnerable to KRACK attacks (2016)
- **WPA3**: SAE authentication, Enhanced Open, AES GCMP, management frame protection

### Application Security Best Practices
- **Defense in Depth**: Multi-layered security approach, input validation not cure-all
- **Cookie Security**: Use Secure, HttpOnly, SameSite attributes; avoid persistent cookies for sessions
- **Code Analysis**: Static (SAST) before execution, Dynamic (DAST) during runtime
- **Code Signing**: Confirms authenticity, doesn't guarantee absence of vulnerabilities

### NAC Implementation Strategies
- **Corporate Environment**: Persistent agents for organization-owned devices
- **BYOD Environment**: Non-persistent agents via captive portals
- **Zero Trust**: NAC supports zero trust architecture through continuous verification
- **Adaptive Control**: Real-time reevaluation based on behavior, location, time, role

### Email Security Configuration
- **DMARC Policy**: Instructs receiving servers on handling DKIM/SPF failures
- **Triple Protection**: DKIM (authenticity) + SPF (authorization) + DMARC (policy enforcement)
- **Gateway Types**: On-premise (control), cloud-based (scalability), hybrid (balance)

### EDR vs XDR Comparison
- **EDR Scope**: Focused on endpoints (computers, laptops, mobile devices)
- **XDR Scope**: Comprehensive across endpoints, network, cloud, email
- **Integration**: XDR consolidates multiple security solutions into single platform

### Protocol Security Selection Rules
- **Always Choose Encrypted Versions**: HTTPS over HTTP, SFTP over FTP, SSH over Telnet
- **Port Security**: Open only necessary ports, follow principle of least privilege
- **Transport Method**: TCP for accuracy, UDP for speed in real-time applications

-----

## 🏷️ Domain Tags

**#Domain2** - Threats, Vulnerabilities & Mitigations  
- Application security vulnerabilities and countermeasures
- Input validation and secure coding practices
- Malicious activity detection and prevention

**#Domain3** - Security Architecture  
- Wireless security standards and protocols
- Secure protocol selection and implementation
- Network segmentation and access controls

**#Domain4** - Security Operations  
- Network Access Control implementation and management
- Email security configuration and monitoring
- Endpoint detection and response systems
- User behavior analytics and anomaly detection
- Web and DNS filtering operations
- AAA protocol configuration and management