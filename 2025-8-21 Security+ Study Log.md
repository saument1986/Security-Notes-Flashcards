---
tags:
  - Domain2
  - Domain4
---
# Security+ Study Log

**Date:** August 21, 2025  
**Section/Module:** Hardening  
**Duration:** N/A  
**Course Progress:** Objectives 2.5, 4.1, 4.5  

-----

## 📚 Today's Material Covered

- [x] Hardening concepts (definition & purpose)
- [x] Changing default configurations
- [x] Restricting applications (allowlisting vs blocklisting)
- [x] Unnecessary services
- [x] Trusted operating systems (TOS, EAL ratings, SELinux, Trusted Solaris)
- [x] Updates & patches
- [x] Patch management processes

| Term                        | Definition                                                                                                                                          |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Hardening**               | Process of securing system, application, or network by reducing vulnerabilities through patches, configs, and best practices                        |
| **Default Configurations**  | Factory settings for devices/software (passwords, ports, protocols) often insecure and must be changed                                               |
| **Default Passwords**       | Manufacturer-supplied login credentials (commonly admin/admin) that should be immediately changed to complex, unique passwords                       |
| **Application Restriction** | Security approach allowing only approved applications (allowlist) or blocking specific applications (blocklist)                                      |
| **Least Functionality**     | Principle of configuring systems with only required apps/services to reduce attack surface                                                           |
| **Allowlisting**            | Only explicitly approved applications can run on system                                                                                              |
| **Blocklisting**            | Specific disallowed applications are blocked; less secure than allowlisting                                                                          |
| **Unnecessary Services**    | Background processes not needed for operations; should be disabled to conserve resources and reduce attack surface                                   |
| **Trusted OS**              | OS with enhanced security controls, often with MAC and high EAL ratings (e.g., Integrity-178B, Trusted Solaris, SELinux)                             |
| **EAL (Evaluation Assurance Level)** | Common Criteria security assurance rating from EAL1 (lowest) to EAL7 (highest); Windows/macOS/Linux typically rated EAL4/EAL4+              |
| **Mandatory Access Control (MAC)** | Security model restricting access based on system policy rather than user discretion                                                           |
| **Updates**                 | Software modifications that improve features, stability, or fix bugs                                                                                |
| **Patch**                   | Specific software update addressing security vulnerabilities                                                                                       |
| **Hotfix**                  | Urgent patch applied immediately to fix security vulnerability                                                                                      |
| **Service Pack**            | Bundle of patches, hotfixes, and updates released together for convenience                                                                          |
| **Patch Management**        | Process of identifying, testing, deploying, and auditing patches for systems, apps, and firmware                                                    |
| **Firmware Management**     | Updating firmware (e.g., Cisco IOS) to fix vulnerabilities and maintain secure network devices                                                       |
| **Patch Rings**             | Deployment method pushing patches in stages (small group → larger groups → entire org) to minimize risk                                             |

### Important Points

**Hardening Core Practices:**
- Apply patches and updates
- Change insecure defaults (passwords, ports, protocols)
- Disable unnecessary services
- Restrict apps with allowlisting/blocklisting
- Use encryption (disk, file, DB, volume levels)
- Apply secure baselines for configs

**Changing Default Configurations:**
- Replace manufacturer default passwords with long, complex, unique ones
- Enable MFA if available
- Disable unused ports/protocols (e.g., close Telnet port 23, replace HTTP 80 with HTTPS 443)
- Minimize open ports to reduce attack surface

**Application Restrictions:**
- Allowlisting: Most secure, everything blocked by default
- Blocklisting: Easier to manage but less secure
- Group Policy / Active Directory can enforce restrictions at scale

**Unnecessary Services:**
- Disable background services not needed for business ops
- Can be done via Windows Services (services.msc), `sc` or `net stop` commands, Activity Monitor (Mac), or `kill` in Linux
- Reduces resources used and closes potential attack vectors

**Trusted Operating Systems:**
- Designed for secure environments (military, aviation, critical infrastructure)
- Example: Integrity-178B (used in fighter jets, EAL6 rated)
- SELinux enforces MAC at EAL4+ level
- Trusted Solaris adds auditing and process isolation
- Higher assurance levels (EAL6/EAL7) mainly in embedded/purpose-built OS

**Updates & Patches:**
- Critical to fix vulnerabilities before attackers exploit them
- Patch categories: Hotfix (urgent security), Update (features/bug fixes), Service Pack (bundle of patches)
- Missing patches = major cause of breaches

**Patch Management:**
- Four-step cycle: Planning → Testing → Implementation → Auditing
- Use automation tools (e.g., Microsoft Endpoint Configuration Manager, MDM for mobile devices)
- Patch rings mitigate risk by staged deployment
- Firmware updates required for network devices (switches, routers, firewalls)

**Takeaway:**  
Hardening is the ongoing process of reducing risk by proactively eliminating default weaknesses, enforcing least functionality, applying patches, and maintaining secure baselines across all systems.

## 🏷️ Domain Tags

**#Domain2** - Threats, Vulnerabilities & Mitigations  
**#Domain4** - Security Operations & Controls
