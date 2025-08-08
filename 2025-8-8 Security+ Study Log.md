# Security+ Study Log

**Date:** August 7, 2025
**Section/Module:** Risk Analysis, Vendor Management & Governance
**Duration:** N/A
**Course Progress:** N/A

-----

## 📚 Today's Material Covered

- [x] Qualitative Risk Analysis (Likelihood & Impact Assessment)
- [x] Quantitative Risk Analysis (SLE, ARO, ALE, EF Calculations)
- [x] Risk Management Strategies (Transfer, Accept, Avoid, Mitigate)
- [x] Risk Monitoring and Reporting
- [x] Third-party Vendor Risk Assessment
- [x] Supply Chain Risk Management
- [x] Supply Chain Attack Types and Mitigation
- [x] Vendor Assessment and Due Diligence
- [x] Vendor Selection and Monitoring Processes
- [x] Contract Types and Agreements
- [x] Governance Frameworks and Structures
- [x] Security Policies and Standards

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                                     | Definition                                                                                                                                |
| ---------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Qualitative Risk Analysis**            | Method of assessing risk based on potential impact and likelihood using descriptive scales (high/medium/low) rather than numerical values |
| **Quantitative Risk Analysis**           | Method of evaluating risk using numerical measurements and probabilistic analysis for financial, safety, and scheduling decisions         |
| **Single Loss Expectancy (SLE)**         | Monetary value expected to be lost in a single event, calculated as Asset Value × Exposure Factor                                         |
| **Exposure Factor (EF)**                 | Proportion of an asset lost in an event, expressed as percentage between 0% (no loss) and 100% (total loss)                               |
| **Annualized Rate of Occurrence (ARO)**  | Estimated frequency with which a threat is expected to occur within a year                                                                |
| **Annualized Loss Expectancy (ALE)**     | Expected annual loss from a risk, calculated as SLE × ARO                                                                                 |
| **Risk Transfer**                        | Strategy involving shifting risk from organization to another party through insurance or contract clauses                                 |
| **Risk Acceptance**                      | Strategy acknowledging risk exists and deciding to deal with it if/when it occurs without mitigation measures                             |
| **Risk Avoidance**                       | Strategy involving changing plans/strategies to eliminate risk entirely                                                                   |
| **Risk Mitigation**                      | Strategy taking steps to reduce likelihood or impact of risk through controls and countermeasures                                         |
| **Residual Risk**                        | Likelihood and impact remaining after specific mitigation, transference, or acceptance measures have been applied                         |
| **Control Risk**                         | Measure of how much less effective a security control has become over time                                                                |
| **Third-party Vendor Risk**              | Potential security and operational challenges introduced by external entities like vendors, suppliers, service providers                  |
| **Supply Chain Attack**                  | Attack targeting weaker link in supply chain to gain access to primary target                                                             |
| **Chip Washing**                         | Repackaging microchip contents with less expensive components or ones containing embedded malware                                         |
| **CHIPS Act**                            | US federal statute providing $280 billion funding to boost semiconductor research and manufacturing domestically                          |
| **Vendor Assessment**                    | Process evaluating security, reliability, and performance of external entities organization relies upon                                   |
| **Due Diligence**                        | Rigorous evaluation going beyond surface credentials, vetting vendor's financial stability, operational history, practices                |
| **Right to Audit Clause**                | Contract provision granting organization right to evaluate vendor's internal processes and compliance                                     |
| **Supply Chain Analysis**                | Deep dive into vendor's entire supply chain to assess security and reliability of each link                                               |
| **Vendor Questionnaire**                 | Comprehensive document potential vendors fill out offering insights into operations, capabilities, compliance                             |
| **Rules of Engagement**                  | Guidelines dictating terms of interaction between organization and potential vendors                                                      |
| **Performance Review**                   | Periodic evaluation assessing vendor's deliverables against agreed-upon standards and objectives                                          |
| **Feedback Loop**                        | Two-way communication channels where both organization and vendor share feedback                                                          |
| **Service Level Agreement (SLA)**        | Contract defining standard of service client can expect from provider with specific metrics and penalties                                 |
| **Memorandum of Agreement (MOA)**        | Formal document outlining specific responsibilities and roles of parties involved                                                         |
| **Memorandum of Understanding (MOU)**    | Less binding declaration of mutual intent expressing broad partnership intentions                                                         |
| **Master Service Agreement (MSA)**       | Blanket agreement covering general terms of engagement across multiple transactions                                                       |
| **Statement of Work (SOW)**              | Document specifying details for particular project including deliverables, timeline, milestones                                           |
| **Non-disclosure Agreement (NDA)**       | Commitment to privacy ensuring sensitive information shared during negotiations remains confidential                                      |
| **Business Partnership Agreement (BPA)** | Document outlining partnership nature, profit sharing, decision-making structures, exit strategies                                        |
| **Governance**                           | Strategic leadership, structures, and processes ensuring organization's IT infrastructure aligns with business objectives                 |
| **Compliance**                           | Adherence to laws, regulations, standards, and policies that apply to organization's operations                                           |
| **Board of Directors**                   | Group of individuals elected by shareholders to oversee management and set strategic direction                                            |
| **Acceptable Use Policy (AUP)**          | Document outlining do's and don'ts for users interacting with organization's IT systems and resources                                     |
| **Information Security Policy**          | Cornerstone document outlining how organization protects information assets from internal/external threats                                |
| **Business Continuity Policy**           | Plan outlining how organization will continue critical operations during and after disruption                                             |
| **Disaster Recovery Policy**             | Specific plan for recovering IT systems and data after disaster, including backup and restoration procedures                              |
| **Incident Response Policy**             | Plan for handling security incidents including detection, reporting, assessment, response, and learning                                   |
| **SDLC Policy**                          | Guidelines for software development covering all stages from requirements to maintenance                                                  |
| **Change Management Policy**             | Governance of how changes to IT systems and processes are handled in controlled manner                                                    |
| **Password Standards**                   | Requirements dictating complexity and management of passwords including length, characters, rotation                                      |
| **Access Control Standards**             | Specifications determining who has access to what resources using DAC, MAC, or RBAC models                                                |
| **Physical Security Standards**          | Requirements covering physical measures to protect organization's assets including perimeter security, surveillance                       |
| **Encryption Standards**                 | Requirements ensuring data security through approved encryption methods like AES or RSA                                                   |

### Important Points

**Risk Analysis Methods:**
- **Qualitative Approach**: Subjective, relies on expertise, uses categories (high/medium/low), faster and simpler
- **Quantitative Approach**: Objective, uses numerical values, provides concrete financial impact, more complex
- **Risk Formula**: SLE = Asset Value × Exposure Factor; ALE = SLE × ARO
- **Cost-Benefit Analysis**: Compare ALE with mitigation costs to determine if countermeasures are worthwhile
- **Impact Categories**: Low (minor damage, functions operational), Medium (significant damage/loss), High (major damage, essential functions cannot be performed)
- **Likelihood Assessment**: Based on past experience, statistical analysis, expert judgment

**Risk Management Strategies:**
- **Transfer Methods**: Insurance (most common), contract indemnity clauses, risk shifting to third parties
- **Acceptance Types**: Exemption (excluded from rules), Exception (avoid rules under specific circumstances)
- **Avoidance Examples**: Not launching risky products, avoiding unstable markets, eliminating threat sources
- **Mitigation Activities**: Safety training, security investments, implementing controls, reducing probability/impact
- **Strategy Selection**: Based on cost vs. potential loss, organizational risk appetite, regulatory requirements

**Risk Monitoring & Reporting:**
- **Continuous Process**: Track identified risks, monitor residual risks, identify new risks, evaluate effectiveness
- **Stakeholder Communication**: Tailored reports for different audiences, manage expectations, demonstrate control
- **Regulatory Requirements**: Many industries mandate risk reporting for compliance purposes
- **Decision Support**: Information enables resource allocation, timeline adjustments, strategic direction changes
- **Control Effectiveness**: Monitor how security controls degrade over time (e.g., antivirus signature effectiveness)

**Third-party Vendor Risks:**
- **Risk Spectrum**: Hardware vulnerabilities, software backdoors, service provider data access, MSP security protocols
- **Vendor Types**: Vendors (goods/services), Suppliers (production components), MSPs (managed IT services)
- **Assessment Methods**: Penetration testing, contract reviews, audit rights, internal/external audit evidence
- **Due Diligence Areas**: Financial stability, operational history, client testimonials, on-ground practices
- **Conflict of Interest**: Personal/financial relationships that could bias vendor selection decisions

**Supply Chain Security:**
- **Hardware Risks**: Counterfeit components, chip washing, overseas manufacturing, secondary market purchases
- **Software Risks**: Licensing issues, authenticity verification, vulnerability scanning, malware detection
- **Service Provider Risks**: Data confidentiality/integrity, cybersecurity protocols, incident response capabilities
- **Attack Examples**: Cisco counterfeit devices, SolarWinds software compromise, overseas rootkit embedding
- **Government Response**: CHIPS Act ($280B for domestic semiconductor manufacturing), Trusted Foundry program

**Supply Chain Attack Prevention:**
- **Vendor Due Diligence**: Rigorous evaluation of cybersecurity posture and supply chain management practices
- **Continuous Monitoring**: Regular audits, early detection of suspicious activities or vulnerabilities
- **Industry Collaboration**: Information sharing, joint defense strategies, ecosystem-wide security awareness
- **Contractual Safeguards**: Security clauses, adherence standards, legal repercussions for non-compliance

**Vendor Management Process:**
- **Selection Criteria**: Due diligence, conflict of interest checks, standardized questionnaires, rules of engagement
- **Monitoring Methods**: Performance reviews, feedback loops, continuous assessment, relationship adaptation
- **Contract Types**: Basic contracts, SLAs (service metrics), MOA/MOU (formal/informal agreements), MSA/SOW (project-specific)
- **Legal Protections**: NDAs (confidentiality), BPAs (partnerships), audit rights, penalty clauses

**Governance Framework:**
- **GRC Triad**: Governance (strategic leadership), Risk (uncertainty management), Compliance (regulatory adherence)
- **Structural Components**: Guidelines (recommended), Policies (high-level commitments), Standards (mandatory rules), Procedures (step-by-step instructions)
- **Organizational Structures**: Centralized (concentrated authority), Decentralized (distributed authority), Board oversight, Committee specialization
- **Adaptation Requirements**: Technology changes, regulatory shifts, cultural evolution, continuous monitoring and revision

**Policy Categories:**
- **User Behavior**: AUP defines acceptable system usage, boundaries for appropriate conduct
- **Security Framework**: Information security policies cover data classification, access control, encryption
- **Business Continuity**: Policies for operational continuity during disruptions, disaster recovery procedures
- **Operational Processes**: Incident response procedures, SDLC guidelines, change management controls
- **Implementation**: Policies translate governance objectives into actionable organizational requirements

**Standards Implementation:**
- **Authentication**: Password complexity, length requirements, rotation schedules, management tools
- **Authorization**: DAC (owner decides), MAC (label-based), RBAC (role-based), least privilege principle
- **Physical Protection**: Perimeter security, surveillance systems, environmental controls, secure areas
- **Data Protection**: AES for data at rest, RSA for communications, encryption key management, performance balance

## 🏷️ Domain Tags

**#Domain1** - Attacks, Threats & Vulnerabilities
- Supply chain attacks and threat vectors
- Third-party vendor attack surfaces

**#Domain2** - Architecture & Design  
- Risk assessment methodologies
- Vendor assessment processes
- Supply chain risk management

**#Domain5** - Governance, Risk & Compliance
- Risk management strategies and processes
- Governance frameworks and structures
- Compliance monitoring and reporting
- Policy development and implementation
- Standards and procedures establishment