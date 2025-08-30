---
tags:
  - Domain3
  - Domain4
---
# Security+ Study Log

**Date:** August 17, 2025
**Section/Module:** Security Infrastructure & Specialized Systems
**Duration:** N/A
**Course Progress:** Objectives 3.2 & 4.5

-----

## 📚 Today's Material Covered

- [x] Internet of Things (IoT) Architecture
- [x] Industrial Control Systems (ICS) and SCADA
- [x] Embedded Systems and RTOS
- [x] Security Infrastructure Overview
- [x] Ports and Protocols (Review)
- [x] Firewall Types and Configuration
- [x] Intrusion Detection and Prevention Systems
- [x] Network Appliances
- [x] Port Security and 802.1x
- [x] Securing Network Communications
- [x] SD-WAN and SASE
- [x] Infrastructure Considerations
- [x] Infrastructure Controls Selection

| Term                                                | Definition                                                                                                                                       |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Internet of Things (IoT)**                       | Network of physical devices, vehicles, appliances embedded with sensors, software, and connectivity enabling data exchange                      |
| **IoT Hub/Control System**                         | Central point connecting all IoT devices, collects/processes/analyzes data and sends commands back to devices                                   |
| **Smart Devices**                                  | Everyday objects enhanced with computing capabilities and Internet connectivity for autonomous operation                                          |
| **Wearables**                                      | IoT devices designed to be worn on body for health monitoring, notifications, and hands-free interfaces                                         |
| **IoT Sensors**                                    | Devices detecting environmental changes and converting them to processable data (temperature, humidity, motion, etc.)                           |
| **Industrial Control Systems (ICS)**               | Control systems monitoring and controlling industrial processes in electrical, water, oil, gas, and data industries                             |
| **SCADA (Supervisory Control and Data Acquisition)**| ICS type monitoring/controlling geographically dispersed industrial processes like power distribution and pipelines                           |
| **Distributed Control Systems (DCS)**              | ICS controlling production systems within single location                                                                                        |
| **Programmable Logic Controllers (PLC)**           | ICS controlling specific processes like assembly lines in factories                                                                              |
| **Embedded Systems**                               | Specialized computing components performing dedicated functions within larger mechanical/electrical structures                                    |
| **Real-Time Operating System (RTOS)**             | OS designed for real-time applications processing data without buffer delays in predictable, timely manner                                      |
| **Network Segmentation**                          | Security measure dividing network into multiple segments/subnets with separate rules and policies                                               |
| **Wrappers (IPSec)**                              | Protective measures encrypting data transfer, showing only entry/exit points to interceptors                                                    |
| **Firmware Code Control**                         | Managing and controlling low-level device software through secure coding, reviews, and cryptographic signatures                                 |
| **Port**                                           | Logical communication endpoint on computer/server for network connections                                                                        |
| **Inbound Port**                                   | Port used when computer/server listens for connections (e.g., web server port 443)                                                            |
| **Outbound Port**                                  | Port opened by computer to connect to given server (random high number ports)                                                                   |
| **Well-Known Ports**                              | Ports 0-1023 designated by IANA for commonly used protocols                                                                                     |
| **Registered Ports**                              | Ports 1024-49151 used by vendors for proprietary protocols, registered with IANA                                                               |
| **Dynamic/Private Ports**                         | Ports 49152-65535 used by applications without registration, typically for temporary outbound connections                                        |
| **Protocol**                                       | Defined set of rules governing communication and data exchange between devices/systems                                                           |
| **Firewall**                                       | Network security device/software monitoring and controlling traffic based on predetermined security rules                                       |
| **Screened Subnet (DMZ)**                         | Protective barrier between external untrusted and internal trusted networks using packet-filtering firewall                                     |
| **Packet Filtering Firewall**                     | Firewall inspecting only packet headers (IP address, port number) - Layer 4 operation                                                          |
| **Stateful Firewall**                             | Firewall tracking connection states and requests, remembering outbound requests to allow return traffic                                         |
| **Proxy Firewall**                                | Firewall placed between connections making connections on behalf of endpoints (circuit level or application level)                             |
| **Kernel Proxy Firewall**                         | Fifth-generation firewall with minimal performance impact while conducting full packet inspection at every layer                               |
| **Next-Generation Firewall (NGFW)**               | Application-aware firewall overcoming traditional limitations with deep packet inspection and signature-based protection                        |
| **Unified Threat Management (UTM)**               | Single device providing multiple security functions: firewall, IPS, antivirus, VPN, content filtering, load balancing                         |
| **Web Application Firewall (WAF)**                | Specialized firewall inspecting HTTP/HTTPS traffic using rule sets to prevent web application attacks                                          |
| **Access Control List (ACL)**                     | Rule set on firewall/router permitting or denying traffic through particular interface                                                          |
| **Intrusion Detection System (IDS)**              | System detecting unauthorized network access/attacks, verifying and reporting threats without stopping them                                     |
| **Intrusion Prevention System (IPS)**             | System detecting and actively stopping malicious activity by blocking suspicious traffic                                                        |
| **Network IDS (NIDS)**                            | Standalone device monitoring traffic coming into/out of network via SPAN port or mirrored port                                                 |
| **Host-based IDS (HIDS)**                         | Software on server/endpoint monitoring suspicious traffic and processes on single system                                                        |
| **Wireless IDS (WIDS)**                           | System detecting wireless denial of service attacks like flooding, disassociation, de-authentication                                           |
| **Signature-based Detection**                     | Analysis based on defined signatures of previously identified attacks in database                                                               |
| **Anomaly-based Detection**                       | Analysis comparing traffic to normal baseline to identify threats (behavioral-based detection)                                                  |
| **Load Balancer**                                 | Device distributing network/application traffic across multiple servers to enhance efficiency and prevent overload                             |
| **Application Delivery Controller (ADC)**         | Advanced load balancer providing SSL termination, HTTP compression, content caching beyond simple distribution                                 |
| **Proxy Server**                                  | Intermediary between client and server providing caching, filtering, and login management                                                       |
| **Network Sensor**                               | Device monitoring, detecting, and analyzing traffic/data flow to identify unusual activities and security breaches                             |
| **Jump Server (Jump Box)**                       | Dedicated gateway for administrators to securely access devices in different security zones                                                     |
| **Port Security**                                 | Network switch feature restricting device connections to specific ports based on MAC addresses                                                  |
| **MAC Flooding**                                  | Attack causing MAC address overflow in CAM table, making switch fail open and act like hub                                                     |
| **CAM Table**                                     | Content Addressable Memory table storing MAC addresses and associated switch ports                                                              |
| **Sticky MAC**                                   | Dynamic association of first MAC address connected to switch port as authorized address                                                         |
| **802.1x Authentication**                         | Standardized framework for port-based authentication on wired and wireless networks                                                            |
| **Supplicant**                                    | Device/user requesting network access in 802.1x authentication                                                                                 |
| **Authenticator**                                 | Device through which supplicant attempts network access (switch, AP, VPN concentrator)                                                         |
| **Authentication Server**                         | Centralized device performing authentication, usually RADIUS or TACACS+ server                                                                 |
| **Extensible Authentication Protocol (EAP)**      | Framework allowing multiple authentication methods including passwords, certificates, and PKI                                                   |
| **EAP-MD5**                                       | EAP variant using simple passwords and challenge handshake authentication (one-way authentication)                                             |
| **EAP-TLS**                                       | EAP using PKI with digital certificates on both client and server (mutual authentication)                                                      |
| **EAP-TTLS**                                      | EAP requiring certificate on server but password on client                                                                                      |
| **EAP-FAST**                                      | Flexible Authentication via Secure Tunneling using protected access credential instead of certificate                                          |
| **PEAP (Protected EAP)**                         | EAP supporting mutual authentication using server certificate and Active Directory database                                                     |
| **LEAP (Lightweight EAP)**                       | Cisco proprietary EAP protocol working only on Cisco devices                                                                                   |
| **Virtual Private Network (VPN)**                | Extension of private network across public network allowing secure data transmission                                                            |
| **Site-to-Site VPN**                             | VPN interconnecting two sites as inexpensive alternative to dedicated leased lines                                                             |
| **Client-to-Site VPN**                           | VPN connecting single host (laptop, phone) directly to headquarters office                                                                      |
| **Clientless VPN**                               | VPN using web browser for secure connections without requiring dedicated client software                                                        |
| **Full Tunnel VPN**                              | VPN routing and encrypting all network requests through VPN connection regardless of destination                                               |
| **Split Tunnel VPN**                             | VPN dividing traffic - corporate traffic through VPN, Internet traffic directly to destination                                                 |
| **Transport Layer Security (TLS)**               | Cryptographic protocol providing security at upper OSI layers (5, 6, 7) using TCP                                                            |
| **Datagram TLS (DTLS)**                          | UDP-based version of TLS providing same security with less overhead for faster connections                                                      |
| **Internet Protocol Security (IPSec)**           | Secure network protocol suite providing authentication and encryption for VPN creation                                                         |
| **IKE Phase 1**                                  | Internet Key Exchange phase authenticating parties and establishing secure negotiation channel                                                  |
| **IKE Phase 2**                                  | Phase negotiating security association parameters and establishing secure tunnel                                                                |
| **Transport Mode**                                | IPSec mode using original IP header, used for client-to-site VPNs                                                                             |
| **Tunneling Mode**                                | IPSec mode encapsulating entire packet with new header, used for site-to-site VPNs                                                           |
| **Authentication Header (AH)**                   | IPSec component providing integrity and authentication without confidentiality                                                                 |
| **Encapsulating Security Payload (ESP)**         | IPSec component providing authentication, integrity, replay protection, and confidentiality                                                    |
| **Software-Defined WAN (SD-WAN)**                | Virtual WAN architecture leveraging multiple transport services with centralized software control                                              |
| **Secure Access Service Edge (SASE)**            | Framework combining network security and WAN capabilities into single cloud-based service                                                      |
| **Security Zone**                                | Distinct network segment with devices having similar security requirements and trust levels                                                     |
| **Attack Surface**                               | Sum of all potential vulnerabilities and risk points where unauthorized users can enter or extract data                                        |
| **Active Device**                                | Network device (like IPS) monitoring and acting on traffic by influencing data flows                                                          |
| **Passive Device**                               | Network device (like IDS) observing and reporting without intervening in data flow                                                            |
| **Inline Device**                                | Device positioned directly in network traffic path with capability to influence or block traffic                                              |
| **Tap/Monitor**                                  | Device placed outside direct network path, listening to activity without impacting traffic                                                     |
| **Fail-Open**                                    | Failure mode allowing traffic to pass without inspection during device malfunction                                                             |
| **Fail-Closed**                                 | Failure mode blocking all traffic during device malfunction to maintain security                                                               |
| **Control**                                      | Measure or safeguard implemented to mitigate potential risks and protect organizational assets                                                  |

### Important Points

**IoT Architecture Components:**
- **Hub/Control System**: Central management point (Amazon Echo, Google Home, software platforms)
- **Smart Devices**: Computing-enhanced objects (refrigerators, washing machines, industrial robots, drones)
- **Wearables**: Body-worn devices (smartwatches, fitness trackers, VR headsets, AR glasses)
- **Sensors**: Environmental detection (temperature, humidity, light, motion, pressure, chemical composition)
- **Security Risks**: Weak defaults, poorly configured services, open ports, unencrypted communication
- **Mitigation**: Separate network segmentation, change default credentials, disable unnecessary services

**ICS and SCADA Security:**
- **ICS Types**: DCS (single location control), PLC (specific process control), SCADA (geographically dispersed)
- **Industry Applications**: Electrical, water, oil, gas distribution; manufacturing automation
- **Security Evolution**: Originally isolated systems, now connected and exposed to cyber threats
- **Vulnerabilities**: Unauthorized access, malware attacks, lack of updates, physical threats
- **Protection Methods**: Strong access controls, regular updates, firewalls, IDS, security audits, employee training

**Embedded Systems Protection:**
- **RTOS Characteristics**: Real-time processing, predictable execution, time-sensitive applications
- **Application Areas**: Consumer electronics, automotive systems, medical devices, industrial automation
- **Security Challenges**: Hardware failure, software bugs, security vulnerabilities, outdated systems
- **Protection Strategies**: Network segmentation, wrappers (IPSec), firmware code control, patching difficulties
- **Update Methods**: Over-the-air updates with security measures, secure boot mechanisms

**Port and Protocol Knowledge:**
- **Well-Known Ports**: FTP (21), SSH/SCP/SFTP (22), Telnet (23), SMTP (25), DNS (53), HTTP (80), HTTPS (443)
- **Security Considerations**: Telnet (insecure) vs SSH (secure), HTTP vs HTTPS, encrypted vs unencrypted protocols
- **Protocol Characteristics**: TCP (reliable, connection-oriented) vs UDP (faster, connectionless)
- **Registered Ports**: Microsoft SQL (1433), RDP (3389), RADIUS (1812/1813), LDAP (389), LDAPS (636)

**Firewall Types and Characteristics:**
- **Packet Filtering**: Layer 4 operation, header inspection only, fast but limited security
- **Stateful**: Connection state tracking, remembers outbound requests, better security than packet filtering
- **Proxy**: Circuit level (Layer 5) or application level (Layer 7), deeper inspection, performance impact
- **NGFW**: Application awareness, signature-based protection, full-stack visibility, complex management
- **UTM**: Multiple security functions in single device, cost-effective but single point of failure
- **WAF**: HTTP/HTTPS focused, prevents XSS and SQL injection, inline or out-of-band deployment

**Access Control List Configuration:**
- **Rule Structure**: Traffic type, source, destination, action (permit/deny)
- **Processing Order**: Top-down execution, specific rules first, generic rules last
- **Best Practices**: Implicit deny at end, logging all actions, regular review and updates
- **Hardware vs Software**: Router/switch ACLs vs host-based firewalls (Windows Defender, Mac firewall)

**IDS vs IPS Capabilities:**
- **Detection Methods**: Signature-based (known attacks) vs anomaly-based (behavioral analysis)
- **Deployment Types**: NIDS (network-wide), HIDS (single host), WIDS (wireless-specific)
- **Response Differences**: IDS detects/alerts, IPS detects/blocks/responds
- **Placement Strategy**: NIDS on SPAN ports, NIPS inline near border, multiple devices for large networks
- **Performance Impact**: Deep inspection vs throughput trade-offs

**Network Appliance Functions:**
- **Load Balancers**: Traffic distribution, health checks, server redundancy, SSL termination (ADC)
- **Proxy Servers**: Content caching, request filtering, bandwidth optimization, attack protection
- **Sensors**: Traffic monitoring, anomaly detection, performance analysis, security alerting
- **Jump Servers**: Secure administrative access, centralized management, activity logging, tool hosting

**Port Security Implementation:**
- **MAC Filtering**: Specific MAC address to port association, prevent unauthorized device access
- **Sticky MAC**: Dynamic learning of first connected MAC address as authorized
- **802.1x Framework**: Supplicant (device), authenticator (switch/AP), authentication server (RADIUS/TACACS+)
- **EAP Variants**: MD5 (password), TLS (certificates), TTLS (server cert + password), FAST (PAC), PEAP (AD), LEAP (Cisco)
- **Limitations**: MAC spoofing bypasses, requires additional security layers

**VPN Technologies:**
- **Site-to-Site**: Branch office connections, encrypted tunnels over Internet, cost-effective alternative to leased lines
- **Client-to-Site**: Individual remote access, full tunnel (all traffic) vs split tunnel (selective routing)
- **Clientless**: Browser-based using HTTPS/TLS, no dedicated software required
- **IPSec Process**: Key exchange request, IKE Phase 1 (authentication), IKE Phase 2 (tunnel establishment), data transfer, termination
- **Transport vs Tunnel**: Original header (client-to-site) vs encapsulated packet (site-to-site)
- **AH vs ESP**: Authentication/integrity only vs authentication/integrity/confidentiality

**Modern Network Architectures:**
- **SD-WAN Benefits**: Centralized control, multiple transport options, application awareness, cloud optimization
- **SASE Components**: Network security + WAN capabilities, cloud-native service, zero trust access
- **Cloud Integration**: AWS VPC, Azure Virtual WAN/ExpressRoute, Google Cloud Interconnect/VPN

**Infrastructure Design Considerations:**
- **Device Placement**: Optimal data flow, minimize latency, strategic security positioning
- **Security Zones**: Similar trust levels, access controls, policy enforcement
- **Attack Surface**: Minimize exposure points, regular vulnerability assessment, proactive risk management
- **Connectivity Methods**: Wired stability vs wireless flexibility, hybrid approaches for redundancy
- **Device Attributes**: Active vs passive monitoring, inline vs tap deployment
- **Failure Modes**: Fail-open (availability priority) vs fail-closed (security priority)

**Control Selection Methodology:**
- **Key Principles**: Least privilege, defense in depth, risk-based approach, lifecycle management, open design
- **Selection Process**: Current state assessment, gap analysis, clear objectives, benchmarking, cost-benefit analysis
- **Best Practices**: Comprehensive risk assessment, framework alignment (NIST, ISO), customization, stakeholder engagement
- **Continuous Improvement**: Regular review cycles, threat landscape adaptation, control effectiveness monitoring

## 🏷️ Domain Tags

**#Domain3** - Security Architecture
- Security zones and screened subnets
- Device placement and connectivity considerations
- Infrastructure controls selection
- Attack surface minimization

**#Domain4** - Security Operations
- IoT and embedded systems security
- ICS/SCADA protection measures
- Network appliance deployment
- Monitoring and detection systems