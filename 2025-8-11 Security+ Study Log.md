---
tags:
  - Domain5
---
# Security+ Study Log

**Date:** August 10, 2025
**Section/Module:** Audits & Assessments
**Duration:** N/A
**Course Progress:** N/A

-----

## 📚 Today's Material Covered

- [x] Internal Audits and Assessments
	•	External Audits and Assessments
	•	Regulatory Compliance and Examinations
	•	Penetration Testing Types (Physical, Offensive, Defensive, Integrated)
	•	Reconnaissance in Penetration Testing
	•	Penetration Testing Environments (Known, Partially Known, Unknown)
	•	Practical Penetration Testing with Metasploit
	•	Attestation of Findings

| Term                                                | Definition                                                                                                                                       |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Audits**                                          | Systematic evaluation of organizational information systems, applications, and security controls to ascertain efficiency and effectiveness       |
| **Internal Audit**                                  | Systematic evaluation conducted by organization's own audit team to assess effectiveness of internal controls and compliance                     |
| **External Audit**                                  | Independent evaluation performed by third-party entities to verify organization's financial statements and compliance                            |
| **Assessments**                                     | Detailed analysis of organization's security systems to identify vulnerabilities and risks, often performed before implementing new systems      |
| **Compliance**                                      | Process ensuring organization's information systems and security practices adhere to established standards, regulations, and laws                |
| **Audit Committee**                                 | Group of individuals (typically board members) who oversee organization's audit and compliance activities                                        |
| **Self-Assessment**                                 | Internal evaluation conducted by organization to assess compliance with specific standards or regulations                                        |
| **Regulatory Compliance**                           | Adherence to laws and regulations dictating how organizations must manage security of IT systems and data                                        |
| **Examination**                                     | Detailed inspection of organization's security infrastructure conducted externally, may include personnel testing and certification verification |
| **Independent Third-Party Audit**                   | Unbiased evaluation providing external perspective on organization's security posture to identify overlooked weaknesses                          |
| **Penetration Testing (Pentesting)**                | Simulated cyber attack against computer system, network, or web application to identify exploitable vulnerabilities                              |
| **Physical Penetration Testing**                    | Testing physical security measures including locks, access cards, security cameras, and physical access controls                                 |
| **Offensive Penetration Testing (Red Teaming)**     | Actively seeking vulnerabilities and attempting to exploit them using same techniques as real attackers                                          |
| **Defensive Penetration Testing (Blue Teaming)**    | Reactive approach focusing on strengthening systems, detecting attacks, and improving incident response times                                    |
| **Integrated Penetration Testing (Purple Teaming)** | Combines offensive and defensive testing with red and blue teams working together to improve overall security                                    |
| **Reconnaissance**                                  | Initial phase where attacker gathers information about target system to plan attack and increase success rate                                    |
| **Active Reconnaissance**                           | Attacker directly engages with target system (ping, port scan, connection attempts) with higher detection risk                                   |
| **Passive Reconnaissance**                          | Gathering information without directly engaging target system (WHOIS, OSINT, traffic observation) with lower detection risk                      |
| **Known Environment**                               | Penetration test where testers provided with detailed infrastructure information before test commences                                           |
| **Partially Known Environment**                     | Hybrid approach where testers given limited information, simulating partial insider knowledge scenario                                           |
| **Unknown Environment**                             | Penetration test with minimal/no target information, simulating real-world external attacker scenario                                            |
| **Metasploit**                                      | Multipurpose computer security and penetration testing framework containing tools for reconnaissance through post-exploitation                   |
| **Exploit**                                         | Code or software that delivers payload and performs attack on target by leveraging specific vulnerabilities                                      |
| **Payload**                                         | Code that exploits deliver and run to give control over machine or elevated permissions                                                          |
| **Auxiliary**                                       | Non-exploit features including scanners, sniffers, fuzzers, spoofers within penetration testing frameworks                                       |
| **Post-Exploitation**                               | Additional tasks performed on compromised host to maintain persistence, cover tracks, or gather information                                      |
| **Encoder**                                         | Tool ensuring payloads reach destination undetected by bypassing security systems like IDS or firewalls                                          |
| **Attestation of Findings**                         | Formal written declaration or confirmation of audit/assessment results with evidence proving validity                                            |
| **Letter of Attestation**                           | Official document proving penetration test occurred and findings are valid, required for compliance purposes                                     |
| **Software Attestation**                            | Validating software integrity by checking it hasn't been tampered with using cryptographic signature verification                                |
| **Hardware Attestation**                            | Validating hardware component integrity using tools like TPM to verify system hasn't been tampered with                                          |
| **System Attestation**                              | Validating security posture of entire system, often for compliance standards like ISO 27001 or SOC 2                                             |

### Important Points

**Audit Framework:**
- **Internal vs External**: Internal (own team, internal controls focus) vs External (third-party, unbiased perspective)
- **Audit Scope**: Data protection, network security, access controls, incident response procedures
- **Compliance Focus**: GDPR, HIPAA, PCI DSS requirements validation and gap identification
- **Committee Structure**: Board-level oversight with financial reporting, audit performance, compliance monitoring responsibilities

**Internal Assessment Process:**
- **Self-Assessment Tools**: Cybersecurity checklists (MCIT example), yes/no questionnaires, action item tracking
- **Cross-Functional Teams**: Administration, IT staff, cybersecurity professionals working together
- **Documentation Requirements**: Responsible parties, comments, action items, task assignments for accountability
- **Risk Identification**: Incident history, response plans, business continuity, device security, mobile policies

**External Assessment Requirements:**
- **Independence**: Third-party perspective, objective evaluation, unbiased security posture assessment
- **Regulatory Mandates**: GDPR, HIPAA, PCI DSS requiring regular external validation
- **Evidence Collection**: File links, documentation proof, compliance demonstration materials
- **Comprehensive Coverage**: Administrative, physical, technical safeguards across all regulatory domains

**Examination vs Assessment:**
- **Assessment Focus**: System evaluation, vulnerability identification, policy review
- **Examination Scope**: Personnel testing, certification verification, knowledge-based exams (nuclear power example)
- **Industry Requirements**: High-security environments (1-5 year cycles), operational procedure validation
- **Compliance Validation**: Regulatory adherence, security infrastructure inspection, policy effectiveness

**Penetration Testing Categories:**
- **Physical Testing**: Lock bypass, access card cloning, tailgating, security camera evasion
- **Red Team (Offensive)**: Vulnerability exploitation, real-world attack simulation, funding justification
- **Blue Team (Defensive)**: System strengthening, attack detection, incident response improvement
- **Purple Team (Integrated)**: Collaborative red/blue approach, comprehensive security assessment, skill development

**Reconnaissance Strategies:**
- **Active Methods**: Direct system engagement (Nmap port scans), higher information yield, detection risk
- **Passive Methods**: WHOIS queries, OSINT research, traffic observation, stealth advantage
- **Environment Impact**: Known (minimal reconnaissance), Partially Known (gap filling), Unknown (extensive reconnaissance)
- **Planning Importance**: Target identification, vulnerability discovery, attack success rate improvement

**Metasploit Framework:**
- **Module Types**: Exploits (2200+), Auxiliaries (1100+), Payloads (600+), Post-exploitation (400+)
- **Usage Pattern**: Module type → Platform → Service → Module name structure
- **Configuration**: Options setting (RHOST, RPORT, LHOST, LPORT), payload selection, parameter validation
- **Session Management**: Multiple concurrent sessions, background operations, session switching capabilities
- **Post-Exploitation**: File manipulation, persistence maintenance, privilege escalation, lateral movement

**Practical Penetration Testing:**
- **Target Identification**: Network scanning (Nmap), service fingerprinting, vulnerability assessment
- **Exploitation Process**: Vulnerability research, exploit selection, payload configuration, execution
- **Real-world Example**: EternalBlue (MS17-010), UnrealIRC backdoor, bind shell establishment
- **Evidence Collection**: Command execution proof, file system access, administrative privilege demonstration
- **Session Control**: Background sessions, multiple targets, exploit chaining capabilities

**Attestation Requirements:**
- **Compliance Context**: GLBA, HIPAA, SOX, PCI DSS requiring formal validation
- **Evidence Standards**: Proof of testing occurrence, finding validation, exploit demonstration
- **Documentation**: Summary of findings, assessment period verification, third-party proof
- **Report vs Attestation**: Reports show findings/remediation, attestation provides evidence/proof
- **Validation Types**: Software (signature verification), Hardware (TPM integrity), System (compliance standards)

**Assessment Methodologies:**
- **Threat Modeling**: Potential threat identification (SQL injection, XSS, DoS attacks)
- **Vulnerability Assessment**: Automated scanning, manual testing, systematic weakness identification
- **Risk Assessment**: Impact evaluation, likelihood analysis, cost-benefit mitigation strategies
- **Mitigation Planning**: Code fixes, security controls, architectural changes, remediation priorities

**Regulatory Compliance Framework:**
- **Industry Standards**: Healthcare (HIPAA), Financial (PCI DSS), General (GDPR)
- **Consolidated Approach**: NIST Cybersecurity Framework as umbrella compliance mechanism
- **Regular Validation**: Quarterly/annual external audits, continuous monitoring requirements
- **Documentation Standards**: Policy maintenance, procedure updates, control effectiveness demonstration

**Quality Assurance:**
- **Independent Validation**: Third-party perspective, bias elimination, objective assessment
- **Stakeholder Confidence**: Customer trust, investor confidence, regulatory acceptance
- **Continuous Improvement**: Gap identification, weakness remediation, security posture enhancement
- **Transparency**: Operational clarity, accountability demonstration, trust building mechanisms

## 🏷️ Domain Tags

**#Domain5** - Governance, Risk & Compliance
- Types and purposes of audits and assessments
- Internal vs external audit methodologies
- Regulatory compliance validation processes
- Attestation and evidence requirements