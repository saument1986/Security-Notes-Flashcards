# Security+ Study Log

**Date:** August 6, 2025
**Section/Module:** Advanced Security Topics & Risk Management  
**Duration:** N/A
**Course Progress:** N/A

-----

## 📚 Today's Material Covered

- [x] Blockchain Technology
- [x] Smart Contracts and Digital Contracts
- [x] Encryption Tools (TPM, HSM, KMS, Secure Enclaves)
- [x] Obfuscation Techniques (Steganography, Tokenization, Data Masking)
- [x] Cryptographic Attacks (Downgrade, Collision, Quantum Computing)
- [x] Post-Quantum Cryptography
- [x] Risk Management Framework
- [x] Risk Assessment Frequency Types
- [x] Risk Identification and Business Impact Analysis
- [x] Risk Registers and Key Risk Indicators

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                                  | Definition                                                                                                                                                |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Blockchain**                        | Shared immutable ledger for recording transactions, tracking assets, and building trust using cryptographic hashes and decentralized peer-to-peer network |
| **Smart Contracts**                   | Self-executing contracts where agreement terms are written directly into code, automatically executing when conditions are met without intermediaries     |
| **Public Ledger**                     | Record keeping system that maintains participants' identities in secure/anonymous format, tracks balances, and records all genuine transactions           |
| **Permissioned Blockchain**           | Business-focused blockchain that promotes trust and transparency using immutable public ledgers with controlled access                                    |
| **TPM (Trusted Platform Module)**     | Dedicated microcontroller designed to secure hardware through integrated cryptographic keys, offering hardware-level security                             |
| **HSM (Hardware Security Module)**    | Physical device that safeguards and manages digital keys, performs encryption operations within tamper-proof environment                                  |
| **KMS (Key Management System)**       | Integrated approach for generating, distributing, and managing cryptographic keys throughout their entire lifecycle                                       |
| **Secure Enclave**                    | Co-processor integrated into main processor, designed for data protection with isolated architecture for sensitive data processing                        |
| **Steganography**                     | Practice of hiding secret data within ordinary non-secret files or messages to avoid detection, concealing message existence                              |
| **Tokenization**                      | Technique substituting sensitive data elements with nonsensitive equivalents (tokens) that have no meaningful value                                       |
| **Data Masking**                      | Process of disguising original data to protect sensitive information while maintaining data authenticity and usability                                    |
| **Downgrade Attack**                  | Cryptographic attack forcing system to use weaker/older cryptographic standard than currently supported                                                   |
| **Collision Attack**                  | Attack aiming to find two different inputs that produce same hash output, exploiting birthday paradox                                                     |
| **Quantum Computing**                 | Computer using quantum mechanics to generate/manipulate qubits for enormous processing power                                                              |
| **Qubit**                             | Quantum bit composed of electrons/photons representing multiple combinations of 1s and 0s simultaneously using superpositioning                           |
| **Post-Quantum Cryptography**         | New cryptographic algorithms implementable on classic computers but impervious to quantum computer attacks                                                |
| **CRYSTALS-Kyber**                    | NIST-recommended post-quantum encryption algorithm using relatively small keys and lattice-based problems                                                 |
| **Risk Management**                   | Process of identifying, analyzing, treating, monitoring, and reporting risks to achieve objectives consistent with risk appetite                          |
| **Risk Identification**               | Proactive process recognizing potential risks that could negatively impact organization's ability to operate or achieve objectives                        |
| **Business Impact Analysis (BIA)**    | Process evaluating potential effects of disruption to organization's business functions and processes                                                     |
| **Recovery Time Objective (RTO)**     | Maximum acceptable length of time before lack of business function severely impacts organization                                                          |
| **Recovery Point Objective (RPO)**    | Maximum acceptable amount of data loss measured in time - point to which data must be restored                                                            |
| **Mean Time to Repair (MTTR)**        | Average time required to repair failed component or system - measure of maintainability                                                                   |
| **Mean Time Between Failures (MTBF)** | Average time between failures - measure of system/component reliability                                                                                   |
| **Risk Register**                     | Document recording details about identified risks including description, impact, likelihood, and mitigation actions                                       |
| **Key Risk Indicators (KRIs)**        | Critical predictive metrics providing early signal of increasing risk exposure in enterprise areas                                                        |
| **Risk Owner**                        | Person or group responsible for managing specific risk, monitoring it, and implementing mitigation actions                                                |
| **Risk Appetite**                     | Amount and type of risk organization willing to pursue/retain to achieve strategic objectives                                                             |
| **Risk Tolerance**                    | Degree of uncertainty organization/individual willing to handle while achieving objectives                                                                |
| **Ad-hoc Risk Assessment**            | Risk assessment conducted as needed, often in response to specific events or situations                                                                   |
| **Recurring Risk Assessment**         | Risk assessments conducted at regular intervals as part of standard operating procedures                                                                  |
| **One-time Risk Assessment**          | Risk assessment conducted for specific purpose and not repeated                                                                                           |
| **Continuous Risk Assessment**        | Ongoing monitoring and evaluation of risk using real-time data collection and analysis                                                                    |

### Important Points

**Blockchain Technology:**
- **Core Structure**: Each block contains previous hash, timestamp, and transaction data forming immutable chain
- **Decentralization**: Uses peer-to-peer network without central authority for trust and verification
- **Beyond Cryptocurrency**: Applications include supply chain management, voting systems, property transfers, IP protection
- **Smart Contracts**: Automated execution eliminates intermediaries, provides transparency, reduces fraud costs
- **Commercial Applications**: IBM's permissioned blockchain for business transactions with enhanced trust/transparency
- **Immutable Ledger**: Cannot modify historical data, provides complete traceability from origin to destination

**Encryption Tools:**
- **TPM Applications**: Commonly used with BitLocker drive encryption, stores keys in isolated hardware
- **HSM vs TPM**: HSM is enterprise "bank vault," TPM is personal "vault" - HSM for mission-critical operations
- **KMS Centralization**: Controls entire key lifecycle from creation to destruction, essential for large-scale operations
- **Secure Enclave Examples**: Apple's Face ID/Touch ID store biometric data separately from main processor
- **Hardware Security**: All tools provide hardware-level protection against software-based attacks
- **Compliance Requirements**: HSMs often required for regulatory compliance in financial/healthcare sectors

**Obfuscation Techniques:**
- **Steganography vs Encryption**: Steganography hides existence of message, encryption secures known messages
- **Tokenization Benefits**: Reduces PCI DSS compliance scope, protects actual data in separate vault
- **Data Masking Use Cases**: Testing environments, employee access control, regulatory compliance
- **File Size Changes**: Steganography may alter file sizes, potential detection method
- **Combined Approaches**: Often used together (steganography + encryption) for enhanced security
- **Business Applications**: Credit card processing, medical records, software development testing

**Cryptographic Attacks:**
- **Downgrade Attack Prevention**: Phase out legacy protocols, implement version intolerance checks
- **POODLE Example**: Real-world downgrade attack forcing SSL 3.0 usage despite TLS availability  
- **Birthday Paradox**: With 23 people, 50% chance of shared birthday; applies to hash collisions
- **MD5 Vulnerability**: Proven collision attacks led to deprecation for security applications
- **Quantum Threat Timeline**: No operational quantum computers today, estimate 2030+ for government/corporate use
- **Current vs Future**: Symmetric encryption (AES) more resistant than asymmetric (RSA/ECC) to quantum attacks

**Post-Quantum Cryptography:**
- **Key Size Method**: Doubling key length squares possible combinations (AES-128 → AES-256)
- **NIST Standards**: 2022 competition selected 4 algorithms after 6-year evaluation process
- **Lattice-Based Crypto**: Most recommended algorithms focus on structured lattice problem difficulty
- **Implementation Ready**: Algorithms work on today's classical computers but resist quantum attacks
- **Migration Planning**: Organizations should begin planning post-quantum transitions now

**Risk Management Process:**
- **Five Phases**: Identification → Analysis → Treatment → Monitoring → Reporting (cyclical process)
- **Proactive Approach**: Focus on prevention rather than reaction to risk events
- **Stakeholder Communication**: Risk reporting must be tailored to audience needs and decision-making
- **Dynamic Process**: Continuous monitoring ensures responsiveness to internal/external changes
- **Strategic Alignment**: All risk activities must support organizational objectives and risk appetite

**Risk Assessment Frequency:**
- **Selection Factors**: Depends on organization nature, risk types, environmental changes
- **Ad-hoc Triggers**: New products, market entry, regulatory changes, natural disasters
- **Recurring Schedule**: Annual (strategic), quarterly (operational), monthly (tactical)
- **Technology Enablement**: Continuous assessments require real-time monitoring systems
- **Cost-Benefit Balance**: Frequency must justify resources spent vs. risk reduction achieved

**Business Impact Analysis:**
- **Critical Function Priority**: Identify and rank business functions by importance to operations
- **Time-Based Metrics**: RTO focuses on recovery time, RPO focuses on acceptable data loss
- **Reliability Measures**: MTTR (repair speed), MTBF (failure frequency) guide maintenance strategies
- **Tolerance Thresholds**: Organizations set maximum acceptable downtime/data loss levels
- **Recovery Planning**: BIA results drive disaster recovery and business continuity planning

**Risk Register Management:**
- **Complete Documentation**: Description, impact, likelihood, outcome, cost, owner, KRIs all required
- **Risk Appetite Types**: Expansionary (high risk/return), Conservative (low risk/return), Neutral (balanced)
- **Prioritization Matrix**: Combine impact and likelihood to determine risk level (high/medium/low)
- **Early Warning Systems**: KRIs provide forward-looking view to enable proactive risk management
- **Accountability Structure**: Clear risk ownership ensures someone responsible for monitoring/mitigation

## 🔗 Related Links & Notes
