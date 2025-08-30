---
tags:
  - Domain1
  - Domain4
---
# Security+ Study Log

**Date:** August 9, 2025
**Section/Module:** Change & Asset Management
**Duration:** N/A
**Course Progress:** N/A

-----

## 📚 Today's Material Covered

- [x] Acquisition and Procurement Processes
- [x] Mobile Asset Deployment Models (BYOD, COPE, CYOD)
- [x] Asset Management (Assignment, Classification, Monitoring, Tracking)
- [x] Asset Disposal and Decommissioning (Sanitization, Destruction, Certification)
- [x] Change Management Framework and Approval Processes
- [x] Change Management Implementation Processes
- [x] Technical Implications of Changes
- [x] Change Documentation and Version Control

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                                           | Definition                                                                                                                       |
| ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Asset Management**                           | Systematic process of developing, operating, maintaining, and selling assets in cost-effective manner throughout their lifecycle |
| **Change Management**                          | Structured approach to transitioning individuals, teams, and organizations from current state to desired future state            |
| **Acquisition**                                | Process of obtaining goods and services                                                                                          |
| **Procurement**                                | Entire process of sourcing and obtaining goods/services, including all processes leading up to acquisition                       |
| **Company Credit Card**                        | Low-cost purchasing option for minor purchases that must be made quickly with set transaction limits                             |
| **Individual Purchase**                        | Employee makes purchase on behalf of company and seeks reimbursement, used for small items or emergencies                        |
| **Purchase Order (PO)**                        | Formal document issued by purchasing department authorizing specific purchase, creates financial obligation                      |
| **BYOD (Bring Your Own Device)**               | Policy allowing employees to use personal devices for work purposes                                                              |
| **COPE (Corporate-Owned, Personally Enabled)** | Company provides device to employee but allows personal use (like company car model)                                             |
| **CYOD (Choose Your Own Device)**              | Employee selects device from short list of company-approved options, middle ground between BYOD and COPE                         |
| **Asset Assignment**                           | Process of allocating or assigning ownership of assets to specific persons or groups within organization                         |
| **Asset Classification**                       | Process of categorizing assets based on criteria like function, value, or other organizational parameters                        |
| **Asset Monitoring**                           | Maintaining inventory/record of every asset including specifications, location, assigned users, and relevant details             |
| **Asset Tracking**                             | Monitoring and managing location, status, and condition of physical assets using specialized software and technologies           |
| **Enumeration**                                | Identifying and counting assets, especially during procurement or retirement, using software tools and scanners                  |
| **MDM (Mobile Device Management)**             | Solution allowing organization to securely manage and monitor employee mobile devices with centralized control                   |
| **Sanitization**                               | Process of making data inaccessible and irretrievable from storage medium using traditional forensic techniques                  |
| **Data Overwriting**                           | Replacing existing data with random information multiple times to obscure original data from forensic recovery                   |
| **Degaussing**                                 | Using magnetic field to disrupt magnetic domains on storage devices, rendering data unreadable and irretrievable                 |
| **Secure Erase**                               | Sanitization technique implemented at firmware level to completely delete data and prevent recovery                              |
| **Cryptographic Erase**                        | Leveraging encryption technologies where encryption keys are destroyed rather than erasing actual data                           |
| **Data Destruction**                           | Physical destruction of storage device itself through shredding, pulverizing, melting, or incinerating                           |
| **Certification**                              | Act of proof that data or hardware has been securely disposed of, providing audit trail                                          |
| **Data Retention**                             | Strategic decision on what data to keep and for how long based on regulatory, business, and security requirements                |
| **Change Advisory Board (CAB)**                | Body of representatives from various organizational parts evaluating ramifications of proposed changes                           |
| **Change Owner**                               | Individual or team responsible for initiation of change request, serving as advocate for the change                              |
| **Stakeholder**                                | Any person with vested interest in proposed change, either directly impacted or involved in assessment/implementation            |
| **Impact Analysis**                            | Assessment of potential effects, risks, and consequences of proposed change on organization and operations                       |
| **Scheduled Maintenance Window**               | Specific timeframe set aside for system adjustments and changes to minimize operational disruptions                              |
| **Backout Plan**                               | Predetermined strategy to revert system back to original state if change doesn't go as expected                                  |
| **Standard Operating Procedure (SOP)**         | Detailed, step-by-step instructions guiding how specific tasks should be carried out for consistency                             |
| **Allow List**                                 | Specification of which entities are permitted to access given resource                                                           |
| **Deny List (Block List)**                     | Specification of which entities are prevented from accessing given resource                                                      |
| **Restricted Activities**                      | Tasks or operations listed as restricted due to potential impact on system health or security                                    |
| **Legacy Applications**                        | Older software/systems that continue to be used but may be sensitive to changes due to limited support                           |
| **Dependencies**                               | Interconnected relationships where applications rely on specific databases, services, or other system components                 |
| **Version Control**                            | System tracking and managing changes to documents, software, and information allowing collaborative work and rollbacks           |
| **NIST SP 800-88**                             | Guidelines for Media Sanitization providing guidance on sanitization, destruction, and certification processes                   |
| **ITPR Process**                               | Information Technology Procurement Request process used by organizations like US Navy for rigorous purchase approval             |

### Important Points

**Acquisition and Procurement:**
- **Purchase Methods**: Company credit card (minor/quick), individual purchase (reimbursement), purchase order (formal/expensive)
- **Approval Process**: Internal assessment of need, budget verification, security/compatibility checks, multi-level authorization
- **Organizational Examples**: US Navy ITPR process with detailed assessment, IT standards verification, budget allocation review
- **Post-Procurement**: Compatibility assessment, security configuration, user training, workflow integration
- **Financial Terms**: Net 15/30/60 indicating payment timeline after purchase order issuance

**Mobile Device Deployment:**
- **BYOD Benefits**: Employee convenience (one device), lower organizational costs, personal freedom
- **BYOD Drawbacks**: Security challenges, limited MDM control, employee-controlled security, potential compliance issues
- **COPE Benefits**: Centralized management, standardized models, full organizational control
- **COPE Drawbacks**: Higher upfront costs, privacy concerns, potential need for dual devices
- **CYOD Balance**: Employee choice from approved options, limited support models, controlled standardization
- **Selection Criteria**: Cost considerations, security requirements, employee satisfaction, organizational risk appetite

**Asset Management Framework:**
- **Assignment Process**: Clear ownership definition, departmental allocation, usage accountability
- **Classification Categories**: Function-based, value-based, criticality levels (high-value servers vs low-value storage laptops)
- **Monitoring Components**: Inventory maintenance, specification tracking, location monitoring, user assignment records
- **Tracking Technologies**: GPS location services, specialized software, automated discovery tools
- **Enumeration Benefits**: Accurate inventory, unauthorized device detection, informed decision-making for updates/patches

**Mobile Device Management (MDM):**
- **Core Functions**: Policy enforcement, software uniformity, sensitive data protection, centralized administration
- **Security Features**: Remote lock/wipe capabilities, compliance monitoring, unauthorized access prevention
- **Deployment Capabilities**: Simultaneous software updates, patch distribution, application installation across thousands of devices
- **Operational Benefits**: Increased efficiency, reduced security risks, standardized user experience
- **Enterprise Scale**: Centralized management for vast, diverse device ecosystems

**Asset Disposal and Sanitization:**
- **NIST SP 800-88**: Authoritative guidance for media sanitization, destruction, and certification processes
- **Sanitization Methods**: Data overwriting (1/7/35 passes), degaussing (magnetic field disruption), secure erase (firmware-level)
- **Cryptographic Erase**: Key destruction rather than data deletion, 30-60 second process, enables device repurposing
- **Destruction Methods**: Shredding, pulverizing, melting, incinerating for high-security environments (NSA example)
- **Classification Impact**: Higher classification levels require more passes or physical destruction methods

**Data Retention Strategy:**
- **Retention Drivers**: Regulatory requirements (financial/medical records), historical analysis, dispute resolution
- **Cost Considerations**: Storage expenses, system complexity, security overhead ("more you store, more you secure")
- **Risk Factors**: Larger attack surface, increased breach potential, compliance complexity
- **Lifecycle Stages**: Creation → processing → archiving → destruction with strategic decision points

**Change Management Foundation:**
- **Core Process**: Current state assessment → vision creation → implementation → verification → documentation
- **Approval Structure**: Change Advisory Board (CAB) evaluation, change owner advocacy, stakeholder consultation
- **Impact Analysis**: Risk assessment, effect evaluation, long-term operational impact, unforeseen challenge identification
- **Stakeholder Types**: Technical (developers/admins), business (support teams), end users (customers/employees)

**Change Implementation Process:**
- **Preparation Phase**: Resource gathering, stakeholder engagement, readiness assessment
- **Vision Creation**: North star definition, success criteria, enthusiasm generation
- **Implementation**: Training sessions, team restructuring, technology introduction, continuous communication
- **Verification**: Effectiveness measurement, objective comparison, performance metrics analysis
- **Documentation**: Historical record maintenance, lessons learned capture, future reference materials

**Operational Considerations:**
- **Maintenance Windows**: Scheduled timeframes (e.g., Saturday midnight-4AM), emergency change procedures
- **Backout Planning**: Predetermined reversion strategy, safety net for complications, quick normalcy restoration
- **Testing Requirements**: Post-implementation validation, desired outcome confirmation, new issue identification
- **SOP Compliance**: Consistency maintenance, error reduction, uniform approach across systems

**Technical Implementation Challenges:**
- **Access Control**: Allow/deny list modifications, firewall rule reviews, IP address changes impact
- **Restricted Activities**: Protected database access, sensitive server shutdowns, security protocol adherence
- **Downtime Planning**: Impact estimation, peak hour avoidance, user/customer effect assessment
- **Service Dependencies**: Application restart requirements, data loss prevention, backlog management
- **Legacy Considerations**: Older application sensitivity, limited support, flexibility constraints
- **Dependency Mapping**: Interconnected system relationships, cascading effect prevention, partner architecture impact

**Documentation Requirements:**
- **Version Control**: Document tracking, collaborative work support, rollback capability, stability assurance
- **Diagram Updates**: Visual representation accuracy, architecture reflection, team communication facilitation
- **Process Improvement**: Policy/procedure revision, issue rectification, continuous improvement implementation
- **Record Maintenance**: Change request updates, trouble ticket completion, stakeholder notification, timeline creation
- **Administrative Value**: Accountability provision, future reference, administrative compliance beyond bureaucracy

## 🏷️ Domain Tags

**#Domain1** - Attacks, Threats & Vulnerabilities
- Change management impact on security posture
- Asset disposal preventing data breaches

**#Domain4** - Operations & Incident Response  
- Security techniques for computing resources
- Hardware, software, and data asset management
- Change management processes and security impact