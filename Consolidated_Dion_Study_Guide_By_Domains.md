# Consolidated Security+ Study Guide - Jason Dion Course Notes
*Organized by Security+ Domains*

---

## Domain 1: General Security Concepts

### Security Control Categories
*From 2025-7-18 Study Log*

| Control Type | Definition |
|--------------|------------|
| **Technical Controls** | Technologies, hardware and software mechanisms to manage and reduce risks |
| **Managerial Controls (Administrative)** | Strategic planning and governance side of security |
| **Operational Controls** | Procedures and measures for day-to-day data protection through internal processes and human actions |
| **Physical Controls** | Tangible, real-world measures to protect assets |

### Security Control Types
*From 2025-7-18 Study Log*

| Control Type | Purpose |
|--------------|---------|
| **Preventive Controls** | Proactive measures to thwart potential security threats or breaches |
| **Deterrent Controls** | Discourage potential attackers by making efforts less appealing or more challenging |
| **Detective Controls** | Monitor and alert organizations to malicious activities as they occur |
| **Compensating Controls** | Alternative measures when primary security controls aren't feasible |
| **Directive Controls** | Rooted in policy/documentation, set standards for behavior |

### Key Authentication & Authorization Terms
*From 2025-7-18 Study Log*

- **Authorization**: Set of rules and policies dictating what actions users can perform once verified
- **Accounting**: Security measure ensuring all user activities are properly tracked and recorded
- **Audit Trail**: Chronological record of user activities for tracing changes and unauthorized access
- **Digital Signature** = Hash + Encryption

### Software Vulnerability Fundamentals
*From 2025-8-17 Race Conditions Study Log*

- **Race Condition**: Software vulnerability where execution outcome depends on unpredictable event timing
- **Dereferencing**: Programming operation breaking reference pairing between pointer and memory location
- **Mutex**: Mutually exclusive flag acting as gatekeeper for single-thread code execution
- **Deadlock**: Situation where processes cannot proceed because each waits for other to release resources

---

## Domain 2: Threats, Vulnerabilities & Mitigations

### Threat Actors
*From 2025-7-21 & 2025-7-22 Study Logs*

| Threat Actor Type | Description |
|------------------|-------------|
| **Unskilled Attackers** | Limited technical expertise using readily available tools |
| **Hacktivists** | Cyber attackers driven by political, social, or environmental ideologies |
| **Organized Crime** | Well-structured groups executing cyberattacks for financial gain (ransomware, identity theft) |
| **Nation-State Actors** | Highly skilled government-sponsored attackers for cyber espionage and warfare |
| **Insider Threats** | Security threats originating from within the organization |

**Advanced Persistent Threats (APT)**: Long-term persistence and stealth, previously synonymous with nation-state actors

**Notable Criminal Groups:**
- **FIN7**: Sophisticated cybercrime syndicate linked to high-profile data breaches
- **Carbanak**: Cybercrime syndicate stealing over $1 billion from banks worldwide

### Attack Vectors and Surfaces
*From 2025-7-22 Study Log*

**Threat Vectors**: Means or pathway for attackers to gain unauthorized access  
**Attack Surface**: All points where unauthorized users can try to enter or extract data

**Common Threat Vectors:**
- Messages, Images, Files, Voice calls, Removable Devices, Unsecured networks
- **BlueBorne**: Bluetooth vulnerabilities allowing device takeover and malware spread
- **BlueSmack**: DoS attack targeting Bluetooth-enabled devices

### Social Engineering
*From 2025-7-24, 2025-7-27 & 2025-7-28 Study Logs*

#### Motivational Triggers
- **Authority**: Pretending to be IRS or other authority figures
- **Urgency**: Creating sense of immediacy to bypass security procedures
- **Social Proof**: Using likes/shares to influence behavior
- **Scarcity**: Limited supplies or opportunities
- **Likability**: Building trust through attraction, friendship, or common interests
- **Fear**: Using threats like ransomware

#### Attack Types
| Attack Type | Description |
|-------------|-------------|
| **Phishing** | Fraudulent emails from trusted sources to steal information |
| **Spear Phishing** | Targeted phishing against specific individuals/organizations |
| **Whaling** | Targeting high-profile executives (CEOs, CFOs) |
| **Vishing** | Phone-based attacks using voice calls |
| **Smishing** | SMS-based phishing attacks |
| **Business Email Compromise (BEC)** | Taking over official accounts for malicious actions |

#### Impersonation Techniques
- **Brand Impersonation**: Pretending to represent legitimate companies
- **Typosquatting**: Registering domains similar to popular websites with typos
- **Watering Hole Attacks**: Compromising websites that targets regularly visit

### Malware
*From 2025-7-29 & 2025-7-30 Study Logs*

#### Virus Types
| Virus Type | Characteristics |
|------------|-----------------|
| **Boot Sector Virus** | Stored in first sector of hard drive, loaded during boot |
| **Macro Virus** | Embedded in documents, executed when document opens |
| **Program Virus** | Infects executable/application files |
| **Multipartite Virus** | Combination of boot sector and program virus |
| **Encrypted Virus** | Encrypts malicious code to avoid antivirus detection |
| **Polymorphic Virus** | Changes code each execution to evade detection |
| **Metamorphic Virus** | Completely rewrites itself before infecting files |
| **Armored Virus** | Has protection layer to confuse analysis |

#### Other Malware Types
- **Worms**: Self-replicating without user interaction, spread across networks
- **Trojans**: Appear legitimate but allow unauthorized access when executed
- **Ransomware**: Encrypts data and demands payment for decryption key
- **Rootkits**: Hide activities at OS level, allow ongoing privileged access
- **Keyloggers**: Record keystrokes to capture passwords and sensitive information
- **Spyware**: Secretly monitors and gathers user information

### Malicious Activity Analysis
*From 2025-8-20 Study Log*

#### DoS and DDoS Attacks
- **Flood Attacks**: Overwhelming servers with more packets than they can handle
- **SYN Flood**: TCP session initiation without completing handshake using spoofed IPs
- **DNS Amplification**: Small DNS queries generating large responses to victim
- **Permanent DoS**: Exploiting security flaws to permanently break devices

#### DNS Attacks
- **DNS Cache Poisoning**: Corrupting resolver cache with false information
- **DNS Tunneling**: Encapsulating non-DNS traffic over port 53
- **Domain Hijacking**: Unauthorized domain registration changes

#### Execution and Escalation
- **Directory Traversal**: Using ../ sequences to access files outside web document root
- **Privilege Escalation**: Gaining elevated access to normally protected resources
- **Arbitrary Code Execution**: Running attacker's own code on target system

#### Session Attacks
- **Session Hijacking**: Replacing legitimate session with attacker's machine
- **Replay Attacks**: Rebroadcasting captured valid data transmissions
- **On-Path Attacks**: Positioning between hosts to capture/modify communications

### Password Attacks
*From IAM Study Log 2025-8-17*

**Attack Methods:**
- **Brute Force**: Trying every possible character combination
- **Dictionary**: Using lists of common passwords and variations
- **Password Spraying**: Few common passwords against many accounts
- **Hybrid**: Combining dictionary words with systematic variations

### Indicators of Compromise
*From 2025-8-20 Study Log*

- **Account Lockouts**: Multiple failed login attempts
- **Concurrent Sessions**: Same account active from multiple locations
- **Impossible Travel**: Geographically impossible login timing
- **Resource Consumption**: Unusual CPU/memory/network usage spikes
- **Missing Logs**: Gaps suggesting attacker log tampering
- **Out-of-Cycle Logging**: Activities at unusual times

### Application Security
*From 2025-8-23 Study Log*

#### Application Security Best Practices:
- **Input Validation**: Security practice ensuring applications only process well-defined, uncontaminated data
- **Front-end vs Back-end Validation**: Client-side (bypassable) vs server-side (secure but resource-intensive)
- **Secure Cookies**: Use Secure, HttpOnly, SameSite attributes; avoid persistent cookies for sessions
- **Defense in Depth**: Multi-layered security approach, input validation not cure-all

#### Code Analysis Methods:
- **Static Code Analysis (SAST)**: Reviewing source code before execution to identify vulnerabilities
- **Dynamic Code Analysis (DAST)**: Testing applications while running to find runtime vulnerabilities  
- **Fuzzing**: Automated injection of malformed data to test for crashes and vulnerabilities
- **Stress Testing**: Evaluating system stability under extreme conditions
- **Manual Code Review**: Human review by different programmer than original author

#### Code Protection:
- **Code Signing**: Digital signature confirming software authenticity and integrity (doesn't guarantee no vulnerabilities)
- **Sandboxing**: Isolating programs to limit resource access and system changes

### Hardening
*From 2025-8-21 Study Log*

#### Core Hardening Practices:
- Apply patches and updates regularly
- Change insecure default configurations
- Disable unnecessary services and ports
- Implement application restrictions (allowlisting/blocklisting)
- Use encryption at multiple levels
- Apply secure baseline configurations

#### Changing Default Configurations:
- Replace manufacturer default passwords with long, complex, unique ones
- Enable MFA if available
- Disable unused ports/protocols (e.g., close Telnet port 23, replace HTTP 80 with HTTPS 443)
- Minimize open ports to reduce attack surface

#### Application Restrictions:
- **Allowlisting**: Most secure, everything blocked by default
- **Blocklisting**: Easier to manage but less secure
- Group Policy / Active Directory can enforce restrictions at scale

#### Trusted Operating Systems:
- Designed for secure environments (military, aviation, critical infrastructure)
- Example: Integrity-178B (used in fighter jets, EAL6 rated)
- SELinux enforces MAC at EAL4+ level
- Trusted Solaris adds auditing and process isolation

---

## Domain 3: Security Architecture

### Zero Trust Architecture
*From 2025-7-21 Study Log*

#### Control Plane Components:
- **Adaptive Identity**: Real-time validation using behavior, device, location
- **Threat Scope Reduction**: Limiting access to only what's needed
- **Policy-Driven Access Controls**: Managing access based on roles and responsibilities
- **Secured Zones**: Isolated environments for sensitive data

#### Data Plane Components:
- **Subject/System**: Individual/entity attempting access
- **Policy Enforcement Point**: Gateway controlling access to sensitive areas

### Cyber Resilience and Redundancy
*From 2025-8-12 Study Log*

#### High Availability Concepts:
- **Load Balancing**: Distributing workloads across multiple computing resources
- **Clustering**: Multiple computers working together as single system
- **Five Nines (99.999%)**: Maximum ~5 minutes downtime per year
- **Six Nines (99.9999%)**: Maximum ~31 seconds downtime per year

#### RAID Configurations:
| RAID Level | Description |
|------------|-------------|
| **RAID 0** | Data striping for performance, no redundancy |
| **RAID 1** | Data mirroring on two drives for redundancy |
| **RAID 5** | Striping with parity across minimum three drives |
| **RAID 6** | Striping with double parity across minimum four drives |
| **RAID 10** | Striped array of mirrored arrays |

### Backup and Recovery
*From 2025-8-16 Study Log*

#### Backup Strategies:
- **Onsite Backup**: Fast access but disaster risk
- **Offsite Backup**: Disaster resilience but slower access
- **Full Backup**: Complete data copy each time
- **Incremental**: Only changes since last backup
- **Differential**: All changes since last full backup

#### Site Types:
- **Hot Site**: Fully operational, instant cutover capability
- **Warm Site**: Partially equipped, operational in days
- **Cold Site**: Empty shell requiring setup, operational in weeks

### Cloud and Virtualization Security
*From 2025-8-16 Study Log*

#### Architecture Types:
- **On-Premises**: Local control and security, higher costs
- **Cloud**: Scalability and cost-effectiveness, vendor-managed infrastructure
- **Hybrid**: Balance between control and scalability

#### Virtualization Risks:
- **VM Escape**: Breaking isolation to reach hypervisor
- **Resource Reuse**: Old data leakage if not properly cleared
- **Shared Resource Vulnerabilities**: Multi-tenant cloud risks

#### Modern Architectures:
- **Serverless**: On-demand code execution (AWS Lambda)
- **Microservices**: Breaking applications into independent services
- **Containerization**: Isolated application containers sharing OS kernel

### Wireless Security Architecture
*From 2025-8-23 Study Log*

#### Wireless Security Evolution:
| Standard | Year | Key Features | Vulnerabilities |
|----------|------|--------------|-----------------|
| **WEP** | 1999 | 64/128-bit static keys, RC4 encryption | 24-bit IV weakness, crackable in 3 minutes |
| **WPA** | 2003 | TKIP, dynamic 128-bit keys per packet | TKIP vulnerabilities, insufficient data integrity |
| **WPA2** | 2004 | AES encryption with CCMP, MIC integrity | KRACK attacks (2016) |
| **WPA3** | Latest | SAE, Enhanced Open, AES GCMP, management frame protection | Current most secure standard |

#### WPA3 Advanced Features:
- **SAE (Simultaneous Authentication of Equals)**: Replaces pre-shared keys with Diffie-Hellman key agreement
- **Enhanced Open (OWE)**: Individual encryption for open networks without authentication
- **AES GCMP**: 128-bit for personal, 192-bit for enterprise networks
- **Management Frame Protection**: Required protection against key recovery attacks

#### Secure Protocol Selection:
*From 2025-8-23 Study Log*

**Always Choose Encrypted Versions:**
- **HTTPS (443)** over HTTP (80)
- **SFTP** over FTP (secure SSH tunnel vs plaintext)
- **SSH** over Telnet (encrypted vs plaintext remote access)
- **IMAPS (993)** over IMAP (143)
- **POP3S (995)** over POP3 (110)
- **SMTPS (587)** over SMTP (25)

**Transport Protocol Selection:**
- **TCP**: Connection-oriented, reliable delivery with error checking (web, email)
- **UDP**: Connectionless, fast transmission for real-time applications (streaming, gaming)

### Network Infrastructure
*From 2025-8-16 & 2025-8-17 Study Logs*

#### Separation Methods:
- **Physical (Air Gaps)**: Complete network isolation
- **Logical**: VLANs, firewalls, DMZ segmentation

#### Software-Defined Networking (SDN):
- **Control Plane**: Makes routing and traffic decisions
- **Data Plane**: Forwards packets based on control decisions
- **Application Plane**: Interfaces with controller for policy decisions

#### Infrastructure as Code (IaC):
- **Idempotence**: Same result regardless of execution frequency
- **Benefits**: Speed, consistency, auditability
- **Risks**: Complexity, skill requirements, misconfiguration

---

## Domain 4: Security Operations

### Access Control
*From 2025-7-23 Study Log*

#### Physical Access Controls:
- **Access Control Vestibules**: Double-door systems preventing piggybacking/tailgating
- **Biometric Authentication**: FAR (False Acceptance Rate), FRR (False Rejection Rate), EER (Equal Error Rate)
- **Access Badge Cloning**: RFID/NFC card data copying requiring scanning, extraction, writing, and usage

### Identity and Access Management (IAM)
*From 2025-8-17 IAM Study Log*

#### IAM Process:
1. **Identification**: User claims identity with unique identifier
2. **Authentication**: System verifies claimed identity
3. **Authorization**: Determines permissions for authenticated user
4. **Accounting**: Tracks and logs user activities

#### Multi-Factor Authentication Categories:
- **Knowledge Factors**: Passwords, PINs, security questions
- **Possession Factors**: Smart cards, hardware tokens, smartphones
- **Inherence Factors**: Biometrics (fingerprints, facial recognition)
- **Behavior Factors**: Keystroke patterns, mouse movement
- **Location Factors**: GPS tracking, IP verification

#### Access Control Models:
| Model | Description |
|-------|-------------|
| **MAC (Mandatory)** | System-enforced based on security labels |
| **DAC (Discretionary)** | Resource owner controls permissions |
| **RBAC (Role-Based)** | Permissions assigned to roles, not individuals |
| **ABAC (Attribute-Based)** | Dynamic decisions using multiple attributes |

### Asset Management
*From 2025-8-9 Study Log*

#### Mobile Device Deployment:
- **BYOD**: Employees use personal devices for work
- **COPE**: Company-owned, personally enabled devices
- **CYOD**: Employees choose from approved company options

#### Asset Lifecycle:
- **Assignment**: Clear ownership and accountability
- **Classification**: Function-based, value-based categorization
- **Monitoring**: Inventory maintenance and tracking
- **Disposal**: Sanitization, destruction, and certification

#### Data Sanitization Methods:
- **Overwriting**: Multiple passes to obscure original data
- **Degaussing**: Magnetic field disruption
- **Secure Erase**: Firmware-level deletion
- **Cryptographic Erase**: Destroying encryption keys instead of data

### Security Infrastructure
*From 2025-8-17 Study Log*

#### IoT and Embedded Systems:
- **IoT Components**: Hub/control system, smart devices, wearables, sensors
- **Security Challenges**: Weak defaults, poor configuration, unencrypted communication
- **ICS/SCADA**: Industrial control systems for electrical, water, oil, gas industries

#### Network Security Appliances:
- **Firewalls**: Packet filtering, stateful, proxy, next-generation
- **IDS/IPS**: Network, host-based, wireless intrusion detection/prevention
- **Load Balancers**: Traffic distribution and SSL termination
- **Proxies**: Caching, filtering, and bandwidth optimization

#### VPN Technologies:
- **Site-to-Site**: Branch office connections over Internet
- **Client-to-Site**: Individual remote access
- **IPSec**: Authentication header (AH) and encapsulating security payload (ESP)
- **Transport vs Tunnel Mode**: Original header vs encapsulated packet

### Security Techniques
*From 2025-8-22 Study Log*

#### Group Policy and Templates:
- **AppLocker**: Application control with allow/deny rules
- **Security Baselines**: Standard configurations ensuring minimum security
- **SELinux**: Mandatory Access Control implementation

#### Data Encryption Levels:
- **Full-Disk**: Entire storage device (BitLocker, FileVault)
- **Partition**: Specific partitions only
- **Volume**: Encrypted containers for file groups
- **File-Level**: Individual file protection (GPG)
- **Database**: Transparent Data Encryption (TDE)

### AAA Protocols and Authentication
*From 2025-8-23 Study Log*

#### AAA Protocol Comparison:
| Protocol | Description | Key Features |
|----------|-------------|--------------|
| **RADIUS** | Remote Authentication Dial-In User Service | Centralized AAA, client-server model, widely used enterprise |
| **TACACS+** | Terminal Access Controller Access-Control System Plus | Separates AAA functions, encrypts entire process, granular control |

#### EAP Authentication Methods:
- **EAP (Extensible Authentication Protocol)**: Framework supporting multiple authentication methods
- **PEAP**: Protected EAP encapsulated in TLS tunnel, requires dual-sided certificates
- **EAP-TTLS**: Tunneled TLS requiring only server-side certificate
- **EAP-FAST**: Cisco's secure tunneling for roaming authentication

### Network Access Control (NAC)
*From 2025-8-23 Study Log*

#### NAC Functionality:
- **Purpose**: Protect networks by scanning devices before allowing access
- **Virtual Holding Area**: Temporary quarantine during device inspection
- **Remediation Zone**: Digital quarantine for non-compliant devices
- **Standards**: Built on IEEE 802.1x port-based network access control

#### NAC Agent Types:
- **Persistent Agents**: Software installed on corporate-owned devices
- **Non-persistent Agents**: Temporary downloads via captive portals (BYOD environments)

#### NAC Policy Types:
- **Health Policy**: Antivirus status, patch levels, security configurations
- **Time-based**: Access restricted by schedule (9-5 business hours)
- **Location-based**: Geographic restrictions using IP geolocation/GPS
- **Role-based (Adaptive NAC)**: Dynamic authorization based on device role
- **Rule-based**: Complex policies using logical statements

### Web and DNS Filtering
*From 2025-8-23 Study Log*

#### Web Filtering Methods:
- **Agent-based**: Software on devices enforcing policies regardless of network
- **Centralized Proxy**: Server evaluating requests against organizational policies
- **URL Scanning**: Checking URLs against malicious website databases
- **Content Categorization**: Blocking categories (social media, gambling, adult content)
- **Block Rules**: Specific IP/domain blocking for incident response
- **Reputation-based**: Third-party reputation scoring for website access

#### DNS Filtering:
- **Mechanism**: Prevents domain name to IP address translation for blocked sites
- **Implementation**: DNS server doesn't provide IP for blacklisted domains
- **Use Cases**: Schools blocking inappropriate content, malware protection

### Email Security
*From 2025-8-23 Study Log*

#### Email Authentication Protocols:
| Protocol | Purpose | Implementation |
|----------|---------|----------------|
| **DKIM** | Domain Keys Identified Mail | Digital signature in headers, validates against DNS public key |
| **SPF** | Sender Policy Framework | Verifies sender IP against authorized list in DNS |
| **DMARC** | Domain-based Message Authentication | Uses DKIM/SPF to determine email handling policy |

#### Email Gateway Architecture:
- **On-premise**: Physical server in organization's data center (maximum control)
- **Cloud-based**: Third-party hosted service (scalability and maintenance)
- **Hybrid**: Combination of on-premise and cloud benefits

#### Spam Filtering Techniques:
- **Content Analysis**: Scanning for common spam keywords
- **Bayesian Filtering**: Statistical analysis of message patterns
- **DNS-based Blacklists**: Known malicious sender databases

### Endpoint Detection and Response (EDR/XDR)
*From 2025-8-23 Study Log*

#### EDR Six-Step Process:
1. **Data Collection**: System processes, registry changes, memory usage, network traffic
2. **Data Consolidation**: Centralized database for analysis (on-premise or cloud)
3. **Threat Detection**: Signature-based and behavior-based analysis techniques
4. **Alerts and Response**: Automated actions like endpoint isolation
5. **Threat Investigation**: Forensic data and timeline analysis tools
6. **Remediation**: Malware removal and system restoration to secure baseline

#### Technology Evolution:
- **EDR**: Focused on endpoints (computers, laptops, mobile devices)
- **XDR**: Extended across endpoints, network, cloud, email for correlation
- **File Integrity Monitoring (FIM)**: Hash-based validation against known baselines

### User Behavior Analytics (UBA/UEBA)
*From 2025-8-23 Study Log*

#### Core Functionality:
- **UBA**: User Behavior Analytics using big data and machine learning
- **UEBA**: Extends to User and Entity Behavior Analytics (includes devices, servers)
- **Baseline Creation**: Establishing normal user behavior patterns
- **Anomaly Detection**: Identifying deviations from established baselines

#### Detection Capabilities:
- **Early Threat Detection**: Identifying threats before significant damage
- **Insider Threat Detection**: Catching malicious activities from authorized users
- **Improved Incident Response**: Detailed behavioral information for security teams
- **Adaptive Learning**: Machine learning algorithms continuously updating baselines

### Vulnerability Management
*From 2025-8-24 Study Log*

#### Vulnerability Management Process:
- **Definition**: Systematic and ongoing process of identifying, evaluating, prioritizing, and mitigating vulnerabilities
- **Four-Step Lifecycle**: Planning → Testing → Implementation → Auditing
- **Continuous Process**: Ongoing monitoring and assessment to maintain security posture

#### Vulnerability Identification Methods:
| Method | Description | Tools/Techniques |
|--------|-------------|------------------|
| **Vulnerability Scanning** | Automated probing of networks, systems, applications | Nessus, OpenVAS, Qualys |
| **Static Analysis (SAST)** | Source code analysis without execution | Manual review, automated code scanners |
| **Dynamic Analysis (DAST)** | Real-time application testing | OWASP ZAP, Burp Suite, Peach Fuzzing |
| **Package Monitoring** | Dependency security monitoring | Snyk, Dependabot |
| **Penetration Testing** | Simulated real-world attacks | Manual testing, automated tools |
| **System Audits** | Comprehensive policy and procedure review | Configuration audits, compliance checks |

#### Threat Intelligence Sources:
- **Open-Source Intelligence (OSINT)**: Publicly available threat information
- **Proprietary/Third-Party Feeds**: Commercial services (FireEye, etc.)
- **Information Sharing Organizations**: Industry groups, government agencies
- **Dark Web Intelligence**: Criminal forum monitoring

#### Vulnerability Assessment Components:
- **Severity Assessment**: Standardized scoring systems for impact evaluation
- **Risk Prioritization**: Ranking based on exploitability and business context
- **Attack Vector Analysis**: Understanding exploitation methods
- **Business Impact Assessment**: Operational and reputational damage potential

#### Remediation Strategies:
- **Patching**: Vendor-provided fixes for known vulnerabilities
- **Configuration Changes**: System setting modifications to reduce exposure
- **Compensating Controls**: Alternative security measures when fixes unavailable
- **Risk Acceptance**: Formal acknowledgment with documentation
- **System Isolation**: Segregating vulnerable systems

#### Responsible Disclosure Programs:
- **Purpose**: Ethical framework for security researchers to report vulnerabilities
- **Bug Bounty Programs**: Financial incentives for vulnerability discovery
- **Coordination**: Time for organizations to develop fixes before public disclosure
- **Community Building**: Collaboration between researchers and organizations

### Alerting and Monitoring
*From 2025-8-28 Study Log*

#### Core Concepts:
- **Alerting**: Process of notifying personnel when potential security incidents occur
- **Monitoring**: Continuous observation of systems/networks to detect anomalies and threats
- **Baseline**: Established performance metrics representing normal system behavior
- **Alert Types**: True/False Positives, True/False Negatives (false negatives most dangerous)
- **Goal**: Maximize true positives while minimizing false positives to avoid alert fatigue

#### Monitoring Categories:
- **System Monitoring**: CPU utilization, memory consumption, disk usage, network performance
- **Application Monitoring**: Software performance, availability, errors, bottlenecks
- **Infrastructure Monitoring**: Physical and virtual infrastructure performance/availability
- **Automated vs Manual**: Software tools vs human analysis

#### Key Activities:
| Activity | Purpose |
|----------|---------|
| **Log Aggregation** | Collecting and consolidating log data from various sources into centralized location |
| **Scanning** | Regular examination for vulnerabilities, configuration issues, potential problems |
| **Reporting** | Generating summaries/detailed reports based on collected data |
| **Archiving** | Long-term data storage for compliance, analysis, troubleshooting |
| **Alert Response** | Investigation, escalation, predefined response procedures |
| **Remediation** | Resolving identified issues through patching, reconfiguration, code modification |
| **Validation** | Verifying remediation was successful |
| **Quarantining** | Isolating systems to prevent threat spread |
| **Alert Tuning** | Adjusting parameters to reduce false positives and improve relevance |

### SNMP (Simple Network Management Protocol)
*From 2025-8-28 Study Log*

#### Architecture Components:
- **SNMP Manager**: Collects and processes information from network devices
- **SNMP Agents**: Network devices sending information back to manager
- **MIB (Management Information Base)**: Translation file storing OID structure and details
- **OID (Object Identifier)**: Unique identifiers for variables readable/settable via SNMP

#### Message Types:
- **Set Request**: Manager to agent - change variable values
- **Get Request**: Manager to agent - retrieve variable values
- **Trap Messages**: Asynchronous agent to manager notifications (unsolicited)

#### Trap Types:
- **Granular Traps**: Each message with unique OID, bandwidth efficient
- **Verbose Traps**: Complete alert information as payload, resource intensive
- **Variable Binding**: Key-value pair data storage format

#### Security Evolution:
| Version | Security Features | Vulnerabilities |
|---------|------------------|-----------------|
| **SNMP v1/v2** | Plain text community strings (public/private) | Highly vulnerable to attacks |
| **SNMP v3** | Integrity (hashing), Authentication (source validation), Confidentiality (DES/3DES/AES) | Most secure, group-based access control |

### SIEM (Security Information and Event Management)
*From 2025-8-28 Study Log*

#### Core Functionality:
- **Purpose**: Real-time/near real-time analysis of security alerts from network hardware and applications
- **Correlation**: Connecting disparate events across different systems to identify suspicious patterns
- **Centralized Repository**: Single location for all security-related log data and analysis

#### Implementation Types:
- **Agent-Based**: Software installed on each system, provides detailed real-time data but requires maintenance
- **Agentless**: Direct collection via standard protocols (SNMP/WMI), easier management but less detailed

#### Critical Implementation Factors:
1. **Log Relevant Events**: Filter out irrelevant data
2. **Establish Event Scope**: Define what's included/excluded
3. **Develop Use Cases**: Define what constitutes threats and responses
4. **Plan Incident Response**: Pre-planned actions for different threat types
5. **Establish Ticketing**: Track flagged events through resolution
6. **Schedule Threat Hunting**: Proactive searching for missed threats
7. **Provide Audit Trails**: Evidence trail for auditors and analysts

#### Popular SIEM Solutions:
| Solution | Type | Key Features |
|----------|------|--------------|
| **Splunk** | Commercial | Market-leading big data analysis, Search Processing Language, extensive connectors |
| **ELK/Elastic Stack** | Open Source | Elasticsearch, Logstash, Kibana, Beats components |
| **ArcSight** | Commercial | Compliance reporting (HIPAA, SOX, PCI DSS) |
| **QRadar** | Commercial | IBM's analytics and compliance platform |

### Security Tools Data Integration
*From 2025-8-28 Study Log*

#### Data Source Types:
| Tool Type | Data Generated | Value |
|-----------|----------------|-------|
| **Antivirus** | Malware detection logs, scans, updates | Pattern identification, infection tracking |
| **DLP Systems** | Data leaks, policy violations, user activities | Data protection, insider threat detection |
| **NIDS/NIPS** | Network threats, blocked traffic, anomalies | Network-level threat detection/prevention |
| **Firewalls** | Allowed/blocked traffic, rule changes | Perimeter security, intrusion attempt identification |
| **Vulnerability Scanners** | Vulnerabilities, severity, remediation steps | Risk assessment, remediation prioritization |

### SCAP (Security Content Automation Protocol)
*From 2025-8-28 Study Log*

#### Framework Purpose:
- **SCAP**: Suite of open standards for automating vulnerability management, measurement, policy compliance
- **Standardization**: Common language across different tools and vendors
- **Automation**: Replacing manual checklists with machine-readable formats

#### Core Languages:
| Language | Purpose | Format |
|----------|---------|--------|
| **OVAL** | Open Vulnerability Assessment Language | XML schema for system security states |
| **XCCDF** | Extensible Configuration Checklist Description | XML for configuration checklists and auditing |
| **ARF** | Asset Reporting Format | XML for asset information and relationships |

#### Enumeration Methods:
- **CCE (Common Configuration Enumeration)**: Secure configuration checks across sources
- **CPE (Common Platform Enumeration)**: Hardware, OS, application identification
- **CVE (Common Vulnerabilities and Exposures)**: Unique identifiers for known vulnerabilities

#### CVSS Scoring:
| Score | Severity | Risk Level |
|-------|----------|------------|
| **0** | None | No risk |
| **0.1-3.9** | Low | Minimal impact |
| **4.0-6.9** | Medium | Moderate impact |
| **7.0-8.9** | High | Significant impact |
| **9.0-10.0** | Critical | Severe impact |

### Network Flow Analysis
*From 2025-8-28 Study Log*

#### Flow vs Packet Capture:
- **Full Packet Capture (FPC)**: Complete packets with headers and payloads, storage intensive
- **Flow Analysis**: Metadata and statistics only, significantly more storage efficient
- **Trade-off**: Storage savings vs content detail availability

#### Key Technologies:
| Technology | Description | Benefits |
|------------|-------------|----------|
| **NetFlow** | Cisco-developed flow reporting to structured database | Industry standard, widely supported |
| **IPFIX** | IP Flow Information Export, standardized NetFlow | Vendor-neutral standard |
| **Zeek** | Hybrid tool sampling data + logging interesting full packets | Best of both worlds approach |
| **MRTG** | Multi Router Traffic Grapher for interface monitoring | Visual trend identification, anomaly detection |

#### Flow Data Elements:
- Network protocol interface, IP version/type
- Source/destination IP addresses and ports
- Type of service, traffic volume and timing
- Pattern analysis for threat identification

### Single Pane of Glass
*From 2025-8-28 Study Log*

#### Core Concept:
- **Definition**: Central access point for all security information, tools, and systems
- **Purpose**: Unified view of security posture with simplified management

#### Implementation Steps:
1. **Define Requirements**: Identify needed information, tools, systems
2. **Integrate Data Sources**: APIs, webhooks, plugins, connectors
3. **Customize Interface**: User-friendly design, organized layout
4. **Develop SOPs**: Standard operating procedures and documentation
5. **Continuous Monitoring**: Regular review, adjustments, security maintenance

#### Key Benefits:
- **Simplified Management**: Single location eliminates multiple system logins
- **Improved Efficiency**: Automation of repetitive tasks
- **Enhanced Collaboration**: Better information sharing within security teams
- **Compliance Support**: Easier report generation for regulatory requirements

### Incident Response Process
*From 2025-8-28 Study Log*

#### Seven-Phase Model:
| Phase | Key Activities | Focus |
|-------|----------------|--------|
| **Preparation** | System hardening, policy creation, communication plans, training | Proactive readiness |
| **Detection** | Incident identification, categorization, severity assessment | Event recognition |
| **Analysis** | Thorough examination, scope understanding, stakeholder notification | Deep investigation |
| **Containment** | Limiting incident scope, data security, business impact minimization | Damage control |
| **Eradication** | Removing malicious activity after containment | Threat elimination |
| **Recovery** | System restoration to normal secured state | Operational restoration |
| **Post-Incident** | Root cause analysis, lessons learned, after-action reporting | Continuous improvement |

#### Root Cause Analysis Process:
1. **Define/Scope Incident**: Clear incident boundaries identification
2. **Determine Causal Relationships**: Event chain leading to incident
3. **Identify Effective Solutions**: Appropriate remediation strategies
4. **Implement and Track**: Deploy fixes and monitor resolution

#### Team Structure:
- **Core Team**: Cybersecurity professionals with incident response experience
- **Temporary Members**: Subject matter experts for specific incidents
- **Leadership Support**: Funding, resources, critical business decisions
- **Outsourcing Option**: Specialized expertise but expensive and requires network learning

#### Wireless Security:
| Standard | Year | Key Features |
|----------|------|--------------|
| **WEP** | 1999 | Outdated, easily cracked |
| **WPA** | 2003 | Interim solution with TKIP |
| **WPA2** | 2004 | AES encryption standard |
| **WPA3** | Latest | SAE, Enhanced Open, management frame protection |

### Advanced Security Operations
*From 2025-8-29 Study Log*

#### Threat Hunting
- **Proactive Defense**: Cybersecurity technique for detecting threats not discovered by normal monitoring
- **Hypothesis-Driven**: Based on threat modeling determining highest likelihood/impact events
- **Intelligence Integration**: Combines threat intelligence with internal data for actionable insights
- **TTPs Evolution**: Threat actors modify tactics when they become well-known, requiring adaptation
- **Advisories and Bulletins**: Vendor/researcher publications about new vulnerabilities and TTPs

#### Root Cause Analysis Process
- **Four Steps**: 1) Define scope 2) Determine causal relationships 3) Identify solutions 4) Implement/track
- **No-Blame Approach**: Focus on systemic issues rather than individual fault (encourages transparency)
- **Systematic Investigation**: Identifies broader organizational vulnerabilities beyond single incidents
- **Prevention Focus**: Primary goal is preventing recurrence through process improvement

#### Incident Response Training and Testing
| Method | Description | Benefits | Limitations |
|--------|-------------|----------|-------------|
| **Training** | Education on processes, procedures, priorities | Knowledge transfer | Theory only |
| **Testing** | Practical exercise of IR procedures | Skills validation | Resource intensive |
| **Tabletop (TTX)** | Theoretical scenario discussions | Cost-effective | No hands-on experience |
| **Penetration Testing** | Real network intrusion with rules of engagement | Realistic assessment | Requires clear methodology |
| **Simulation** | Comprehensive realistic hands-on exercises | Most complete validation | Most expensive |

#### Digital Forensic Procedures
**Four-Phase Process:**
1. **Identification**: Scene security, contamination prevention, evidence scope determination
2. **Collection**: Proper authorization, acquisition procedures, order of volatility, chain of custody
3. **Analysis**: Repeatable methods/tools, systematic evidence examination
4. **Reporting**: Methods documentation, findings, conclusions for legal proceedings

#### Order of Volatility (NIST SP 800-86)
1. **System Memory**: Processor cache, system RAM (most volatile)
2. **System State**: Configurations, active sessions, obtainable data
3. **Storage Devices**: Hard drives, SSDs, non-volatile storage
4. **Network Traffic/Logs**: Network activity reconstruction data
5. **Archive Data**: Backups, cloud storage, external devices (least volatile)

#### Digital Forensic Ethics
- **Avoiding Bias**: Analysis based solely on evidence, not personal prejudices
- **Repeatable Actions**: Processes others can perform to achieve same results
- **Evidence Preservation**: Preventing contamination/modification during investigation
- **Chain of Custody**: Documented tracking of evidence handling from collection to court
- **Legal Hold**: Formal preservation notice for potentially relevant electronic data

#### Data Collection Procedures
- **Authorization Required**: Warrant (law enforcement) or executive approval (internal)
- **Data Acquisition**: Creating forensically sound copies using proper methods/tools
- **Write Blockers**: Preventing storage media modification during imaging
- **Hashing**: Cryptographic verification of data integrity (MD5, SHA-1, SHA-256)
- **Digital Crime Scene**: Different considerations than physical scenes (live vs dead analysis)

#### Investigative Data Sources
**Log File Types:**
- **Network**: Router/switch traffic tracking
- **System**: Host/server activity records
- **Application**: Individual application monitoring
- **Security**: Authentication and security events
- **Web**: Server access and proxy activities
- **DNS**: Request/response logging
- **Authentication**: Login success/failure tracking
- **Dump Files**: System crash memory contents
- **VoIP**: Call metadata and recordings

**Centralized Logging Systems:**
- **Syslog/Rsyslog/Syslog-ng**: Multi-platform log aggregation
- **Journalctl**: Linux systemd logging utility
- **NXLog**: Cross-platform log management tool

**Network Flow Analysis:**
| Technology | Description | Purpose |
|------------|-------------|---------|
| **NetFlow** | Cisco flow reporting protocol | Bandwidth monitoring, pattern analysis |
| **SFlow** | Sampled Flow, open-source alternative | Network traffic sampling |
| **IPFIX** | IP Flow Information Export standard | Service provider billing/accounting |
| **Zeek** | Hybrid sampling with full packet logging | Best of both worlds approach |

**Metadata Analysis:**
- **Definition**: Data describing other data (file timestamps, email headers, call records)
- **Applications**: Email forensics, mobile analysis, web activity, file investigation
- **Value**: Provides context and patterns without full content analysis

#### Windows Registry Forensics
- **Location**: Most registry stored on disk, but HKLM\Hardware only in memory
- **Evidence Value**: Records all connected/removed storage devices
- **Collection Priority**: Memory dump required for hardware hive analysis
- **Forensic Significance**: Reveals USB drives, external storage usage patterns

---

## Domain 5: Governance, Risk & Compliance

### Risk Management
*From 2025-8-8 Study Log*

#### Risk Analysis Methods:
- **Qualitative**: Subjective assessment using high/medium/low scales
- **Quantitative**: Numerical measurements using SLE, ARO, ALE calculations

**Risk Calculation Formulas:**
- **SLE = Asset Value × Exposure Factor**
- **ALE = SLE × ARO**

#### Risk Management Strategies:
- **Transfer**: Shifting risk through insurance or contracts
- **Accept**: Acknowledging risk without mitigation
- **Avoid**: Eliminating risk through planning changes
- **Mitigate**: Reducing likelihood or impact through controls

### Vendor Management
*From 2025-8-8 Study Log*

#### Third-Party Risk Assessment:
- **Due Diligence**: Rigorous evaluation beyond surface credentials
- **Vendor Assessment**: Security, reliability, and performance evaluation
- **Supply Chain Analysis**: Entire vendor supply chain security review

#### Contract Types:
- **SLA**: Service Level Agreement with specific metrics
- **MOA/MOU**: Formal/informal agreement documents
- **MSA/SOW**: Master service agreement with project-specific work
- **NDA**: Non-disclosure agreement for confidentiality

### Governance Framework
*From 2025-8-8 & 2025-8-9 Study Logs*

#### GRC Components:
- **Governance**: Strategic leadership and organizational structures
- **Risk**: Uncertainty management and mitigation strategies
- **Compliance**: Regulatory adherence and legal requirements

#### Policy Hierarchy:
1. **Guidelines**: Recommended practices
2. **Policies**: High-level commitments and principles
3. **Standards**: Mandatory technical requirements
4. **Procedures**: Step-by-step implementation instructions

#### Compliance Considerations:
- **Regulatory**: Industry-specific requirements (GDPR, HIPAA, PCI DSS)
- **Legal**: Contract law, intellectual property, employment law
- **Industry**: Technical standards and best practices
- **Geographic**: Local, regional, national, and global regulations

### Audits and Assessments
*From 2025-8-10 Study Log*

#### Audit Types:
- **Internal**: Conducted by organization's audit team
- **External**: Independent third-party evaluation
- **Regulatory**: Compliance with specific laws and regulations

#### Penetration Testing:
- **Physical**: Testing locks, access cards, security cameras
- **Offensive (Red Team)**: Actively exploiting vulnerabilities
- **Defensive (Blue Team)**: Strengthening systems and detection
- **Integrated (Purple Team)**: Collaborative approach

#### Testing Environments:
- **Known**: Detailed infrastructure information provided
- **Partially Known**: Limited information, hybrid approach
- **Unknown**: Minimal information, real-world simulation

### Change Management
*From 2025-8-9 Study Log*

#### Change Process:
1. **Need Identification**: Impact assessment and planning
2. **Implementation**: Staged deployment with rollback plans
3. **Review**: Effectiveness measurement and documentation

**Change Advisory Board (CAB)**: Representatives evaluating change impacts across organization

---

*This consolidated study guide organizes all key concepts, definitions, and important points from Jason Dion Security+ study logs by the five main Security+ domains. Each section includes date references from original study logs for cross-referencing.*