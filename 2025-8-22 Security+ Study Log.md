---
tags:
  - Domain4
---
# Security+ Study Log

**Date:** August 17, 2025
**Section/Module:** Security Techniques and Configuration Management
**Duration:** N/A
**Course Progress:** Objectives 4.1 & 4.5

-----

## 📚 Today's Material Covered

- [x] Group Policies and Security Templates
- [x] SELinux and Mandatory Access Control
- [x] Data Encryption Levels
- [x] Secure Baseline Establishment
- [x] Wireless Infrastructure Security
- [x] Wireless Security Settings and Protocols

| Term                                                | Definition                                                                                                                                       |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Group Policy**                                   | Set of rules/policies applied to users or computer accounts within operating system for security and configuration management                   |
| **Group Policy Object (GPO)**                     | Security template containing predefined rules for password policies, account lockouts, software restrictions                                    |
| **Group Policy Editor (gpedit)**                  | Windows tool for creating and managing local and domain-based policies                                                                          |
| **Security Template**                             | Group of policies loaded through single procedure in Group Policy Editor for system hardening                                                  |
| **AppLocker**                                     | Windows application control program creating allow rules (allowlisting) or deny rules (blocklisting)                                          |
| **Allow Rule (Allowlisting)**                     | Policy permitting specific applications, publishers, or file paths to execute                                                                   |
| **Deny Rule (Blocklisting)**                      | Policy preventing specific applications, publishers, or file paths from executing                                                               |
| **Baselining**                                    | Process of measuring changes in network, hardware, or software environments to establish normal operations                                      |
| **Deviation Analysis**                            | Comparing current activity against known baseline to identify abnormal or suspicious behavior                                                   |
| **SELinux**                                       | Security Enhanced Linux implementing Mandatory Access Control (MAC) created by NSA                                                             |
| **Mandatory Access Control (MAC)**                | System-enforced access control based on subject clearance and object labels                                                                     |
| **Discretionary Access Control (DAC)**            | Access control where object owner controls permissions using chown/chmod commands                                                               |
| **Context-Based Permissions**                     | Permission schemes defined by various file/process properties used together rather than isolation                                               |
| **AppArmor**                                      | Linux MAC system alternative to SELinux providing context-based permission control                                                             |
| **SELinux User Context**                          | Defines which users can access object (unconfined_u, user_u, sysadmin_u, root)                                                                |
| **SELinux Role Context**                          | Defines which roles can access object, with object_r applying to files/directories                                                             |
| **SELinux Type Context**                          | Most important MAC label for fine-grained access control, grouping objects with similar security requirements                                  |
| **SELinux Level Context**                         | Optional fourth context describing sensitivity level for multi-level security                                                                  |
| **SELinux Disabled Mode**                         | SELinux turned off, relying on default DAC file system permissions                                                                             |
| **SELinux Enforcing Mode**                        | All security policies enforced, processes cannot violate policies                                                                              |
| **SELinux Permissive Mode**                       | SELinux enabled but policies not enforced, allowing processes to bypass restrictions                                                           |
| **Targeted Policy**                               | Default SELinux policy where targeted processes run in confined domain, others in unconfined domain                                           |
| **Strict Policy**                                 | SELinux policy enforcing MAC on every subject and object in system                                                                             |
| **Full-Disk Encryption**                          | Encrypting entire hard drive/storage device to protect all stored data                                                                         |
| **BitLocker**                                     | Windows software full-disk encryption tool requiring PIN, password, or security key                                                            |
| **FileVault**                                     | macOS full-disk encryption equivalent to BitLocker                                                                                             |
| **Partition Encryption**                          | Encrypting specific partition while leaving others unencrypted for performance optimization                                                     |
| **VeraCrypt**                                     | Software tool for partition and volume encryption providing encrypted containers                                                                |
| **Volume Encryption**                             | Creating encrypted container/set space housing various files and folders                                                                       |
| **File-Level Encryption**                         | Encrypting individual files for email transmission or selective protection                                                                      |
| **GNU Privacy Guard (GPG)**                       | Software tool for file-level encryption enabling secure file sharing                                                                           |
| **Database Encryption**                           | Encrypting entire database spanning multiple storage devices or cloud environments                                                             |
| **Transparent Data Encryption (TDE)**             | SQL Server feature automatically encrypting database without application changes                                                                |
| **Record-Level Encryption**                       | Encrypting individual database records/rows for granular data protection                                                                       |
| **Secure Baseline**                               | Standard set of configurations and controls ensuring minimum security level across systems                                                      |
| **Baseline Establishment**                        | Thorough system assessment identifying data types, workflows, vulnerabilities, and compliance requirements                                      |
| **System Hardening**                              | Securing template system through formatting, OS installation, updates, configuration, and vulnerability scanning                              |
| **Image Creation**                                | Creating deployable template from hardened system for consistent secure installations                                                          |
| **Configuration Management**                       | Tracking and validating group policies and configurations before deployment                                                                     |
| **Baseline Deployment**                           | Applying secure configurations across organizational assets using automated tools and scripts                                                  |
| **Baseline Maintenance**                          | Ongoing process of system lockdown, monitoring, updates, and user training                                                                     |
| **Wireless Access Point (WAP)**                   | Device allowing wireless devices to connect to wired network using 802.11 standards                                                           |
| **Access Point Placement**                        | Strategic positioning for optimal performance and security, avoiding signal leakage                                                            |
| **Omnidirectional Antenna**                       | Antenna broadcasting signal 360 degrees in all directions                                                                                      |
| **Unidirectional Antenna**                        | Antenna broadcasting signal in single direction for focused coverage                                                                            |
| **Extended Service Set (ESS)**                    | Multiple access points working together creating large merged coverage zone                                                                     |
| **Co-Channel Interference**                       | Interference from overlapping access points using same channel/frequency                                                                       |
| **Adjacent Channel Interference**                  | Interference from insufficient spacing between channels causing frequency overlap                                                               |
| **Site Survey**                                   | Process of planning wireless network for required coverage, capacity, roaming, and QoS                                                        |
| **Heat Map**                                      | Graphical representation of wireless coverage, signal strength, and frequency utilization                                                      |
| **Dead Zone**                                     | Area with no wireless coverage requiring additional access points                                                                              |
| **Signal Leakage**                                | Wireless signal extending beyond facility boundaries enabling unauthorized access                                                               |
| **Wired Equivalent Privacy (WEP)**                | Outdated 1999 wireless security using static encryption keys, easily cracked in 3 minutes                                                     |
| **Wi-Fi Protected Access (WPA)**                  | 2003 interim security enhancement over WEP using Temporal Key Integrity Protocol (TKIP)                                                       |
| **Wi-Fi Protected Access 2 (WPA2)**               | 2004 802.11i standard using Advanced Encryption Standard (AES) and CCMP protocol                                                              |
| **Wi-Fi Protected Access 3 (WPA3)**               | Latest wireless security with SAE, Enhanced Open, updated cryptography, management frame protection                                            |
| **Temporal Key Integrity Protocol (TKIP)**        | WPA protocol dynamically generating new 128-bit key for each packet                                                                            |
| **Advanced Encryption Standard (AES)**            | Robust encryption algorithm replacing WEP's RC4 in WPA2/WPA3                                                                                  |
| **CCMP**                                          | Counter Cipher Mode with Block Chaining Message Authentication Code Protocol                                                                   |
| **Message Integrity Code (MIC)**                  | WPA2 integrity checking feature preventing data tampering                                                                                      |
| **Simultaneous Authentication of Equals (SAE)**   | WPA3 key establishment protocol replacing pre-shared key method, resistant to offline attacks                                                  |
| **Enhanced Open (OWE)**                          | WPA3 feature providing individualized encryption for open networks without authentication                                                       |
| **AES GCMP**                                      | Galois Counter Mode Protocol replacing AES CCMP in WPA3                                                                                        |
| **Management Frame Protection**                    | WPA3 feature protecting network management frames against key recovery attacks                                                                 |
| **RADIUS**                                        | Remote Authentication Dial-In User Service providing centralized AAA services                                                                 |
| **TACACS+**                                       | Terminal Access Controller Access-Control System Plus with separated AAA functions                                                            |
| **Extensible Authentication Protocol (EAP)**      | Authentication framework supporting multiple methods for wireless and point-to-point connections                                              |
| **Protected EAP (PEAP)**                          | Authentication protocol encapsulating EAP within encrypted TLS tunnel                                                                          |
| **EAP-TTLS**                                      | EAP Tunneled TLS requiring certificate only on server side                                                                                     |
| **EAP-FAST**                                      | Cisco's Flexible Authentication via Secure Tunneling using protected access credentials                                                        |

### Important Points

**Group Policy Implementation:**
- **Access Method**: Windows Run prompt → "gpedit" → Local Group Policy Editor launch
- **Policy Categories**: Password complexity, account lockout, software restrictions, application controls
- **Corporate Templates**: Predefined security rules based on organizational administrative policies
- **System Hardening**: GPOs used to create secure baseline for configuration management
- **Domain Integration**: Active Directory provides advanced Group Policy Editor functionality

**AppLocker Configuration Process:**
- **Location**: Computer Configuration → Windows Settings → Security Settings → Application Control Policies
- **Rule Types**: Executable, Windows installer, script, package application rules
- **Allow Rules**: Permit specific applications, publishers, paths, or file hashes
- **Deny Rules**: Block applications from temporary directories, untrusted publishers, known malware hashes
- **Conditions**: Publisher-based, path-based, or file hash-based blocking/allowing

**AppLocker Rule Creation:**
- **Wizard Process**: Right-click → Create New Rule → Allow/Deny selection → User scope → Condition type
- **Path Rules**: Block everything in %WINDIR%\Temp\* directory (common malware location)
- **Publisher Rules**: Block applications from compromised software vendors
- **Hash Rules**: Block known malicious files using MD5/SHA hash values
- **Default Rules**: Allow Program Files, Windows folder, administrator access
- **Exception Handling**: Add exceptions for trusted publishers or specific paths

**Baselining and Monitoring:**
- **Purpose**: Establish what normal network/system activity looks like for organization
- **Deviation Detection**: Compare current activity against baseline to identify anomalies
- **Investigation Triggers**: High activity during normally quiet periods (Saturday afternoons)
- **Data Breach Discovery**: Many breaches found through unexpected network utilization patterns
- **Categorization**: Classify deviations as acceptable/expected or requiring investigation

**SELinux Architecture:**
- **Creation**: Developed by National Security Agency (NSA) for enhanced Linux security
- **Default Distributions**: CentOS and Red Hat Enterprise Linux standard implementation
- **MAC Implementation**: System-enforced access control overriding user discretionary permissions
- **File System Protection**: Unauthorized processes cannot access, tamper, or bypass security mechanisms
- **Network Security**: Additional layer protecting against policy violations and untrusted programs

**SELinux Context System:**
- **User Context**: unconfined_u (all users), user_u (unprivileged), sysadmin_u (admins), root (superuser)
- **Role Context**: object_r for files/directories, user roles authorized for specific domains
- **Type Context**: Most critical for fine-grained control, grouping objects with similar security needs
- **Level Context**: Optional multi-level security for sensitivity-based access control
- **Context Format**: user:role:type:level (fourth component optional)

**SELinux Operating Modes:**
- **Disabled**: MAC turned off, relying on traditional DAC permissions
- **Enforcing**: All security policies enforced, process violations blocked
- **Permissive**: Policies enabled but not enforced, violations logged but allowed
- **Mode Selection**: Based on security requirements vs. application compatibility needs
- **Audit Logging**: Violations captured for policy tuning and security monitoring

**SELinux Policy Types:**
- **Targeted Policy**: Default for Red Hat/CentOS, confined domains for targeted processes only
- **Strict Policy**: MAC enforcement on every system subject and object
- **Configuration Complexity**: Targeted easier to implement, strict requires comprehensive planning
- **Process Domains**: Confined (restricted) vs unconfined (unrestricted) process execution
- **Policy Tuning**: Initial deployment may generate false positives requiring policy refinement

**Data Encryption Hierarchy:**
- **Full-Disk**: Entire storage device encrypted (BitLocker, FileVault, hardware-based)
- **Partition**: Specific partition encrypted while others remain unencrypted
- **Volume**: Encrypted container within storage device for flexible file housing
- **File-Level**: Individual file encryption for selective protection and sharing
- **Database**: Entire database encryption spanning multiple devices/cloud environments
- **Record-Level**: Granular encryption of specific database records or columns

**Encryption Tool Examples:**
- **Windows**: BitLocker for full-disk, built-in EFS for file-level
- **macOS**: FileVault for full-disk encryption
- **Cross-Platform**: VeraCrypt for partition/volume encryption
- **File Sharing**: GPG for individual file encryption and secure transmission
- **Database**: SQL Server TDE for transparent database encryption
- **Performance Consideration**: Encryption overhead vs. security requirements balance

**Secure Baseline Lifecycle:**
- **Establishment**: System assessment, vulnerability analysis, compliance alignment (ISO 27001, NIST 800-53)
- **Template Creation**: Format → Install → Update → Configure → Secure → Scan → Remediate
- **Application Installation**: Job-specific tools, office suites, EDR agents, browsers
- **Image Creation**: Template system converted to deployable image for consistent deployment
- **Deployment**: GPOs, automated scripts, cloud services (AWS Config) for uniform application
- **Maintenance**: System lockdown, continuous monitoring, regular updates, user training

**Wireless Access Point Placement:**
- **Security Considerations**: Avoid windows/external walls to prevent signal leakage
- **Central Positioning**: Maximize coverage while minimizing external access opportunities
- **Height Advantage**: Mount on ceilings or high shelves for optimal signal propagation
- **Antenna Selection**: Omnidirectional for internal coverage, unidirectional for focused beams
- **External Wall Requirements**: Use unidirectional antennas pointing inward

**Wireless Interference Management:**
- **Co-Channel**: Same frequency overlap causing signal collisions and retransmissions
- **Adjacent Channel**: Insufficient channel spacing creating frequency overlap
- **2.4 GHz Band**: 11 channels with 22 MHz width in 100 MHz spectrum
- **Channel Selection**: Use channels 1, 6, 11 for non-overlapping coverage
- **Channel Spacing**: Channel 6 operates at 2.437 GHz with ±11 MHz spread

**Wireless Network Planning:**
- **Site Survey**: RF interference testing, optimal AP location identification
- **Heat Map Creation**: Visual representation of coverage, signal strength, frequency utilization
- **Dead Zone Identification**: Areas requiring additional access points
- **Signal Leakage Detection**: Coverage extending beyond facility boundaries
- **ESS Configuration**: Multiple APs creating seamless roaming coverage

**Wireless Security Evolution:**
- **WEP (1999)**: 64/128-bit keys with 24-bit IV, RC4 encryption, easily cracked
- **WPA (2003)**: TKIP protocol, dynamic 128-bit keys, interim WEP replacement
- **WPA2 (2004)**: AES encryption, CCMP protocol, MIC integrity checking
- **WPA3 (Latest)**: SAE authentication, Enhanced Open, 192-bit AES, management frame protection
- **Security Progression**: Each version addresses previous vulnerabilities

**WPA3 Advanced Features:**
- **SAE Protocol**: Replaces four-way handshake with Diffie-Hellman key agreement
- **Offline Attack Resistance**: Captured handshake data cannot be used for password cracking
- **Enhanced Open**: Individual encryption for open networks without authentication
- **Updated Cryptography**: AES GCMP replacing CCMP, support for 192-bit enterprise encryption
- **Management Protection**: Required frames preventing key recovery and DoS attacks

**AAA Protocol Implementation:**
- **RADIUS**: Client-server model, comprehensive AAA services, enterprise authentication
- **TACACS+**: Separated AAA functions, granular control, TCP-based with full encryption
- **Centralized Management**: Single authentication server for multiple network resources
- **Policy Enforcement**: Predefined access rules based on user identity and role
- **Activity Monitoring**: Comprehensive logging for accountability and compliance

**EAP Protocol Variants:**
- **EAP Framework**: Message format definition, authentication method negotiation
- **PEAP**: TLS tunnel encapsulation, dual-sided certificate authentication
- **EAP-TTLS**: Server-side certificate only, client password authentication
- **EAP-FAST**: Cisco development, protected access credentials, secure roaming
- **Method Selection**: Based on certificate availability, security requirements, vendor compatibility

## 🏷️ Domain Tags

**#Domain4** - Security Operations
- Security techniques implementation
- Configuration management and baselines
- Wireless infrastructure security
- Access control and encryption methods