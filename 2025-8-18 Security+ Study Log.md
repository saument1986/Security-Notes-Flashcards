---
tags:
  - Domain2
  - Domain4
---
# Security+ Study Log

**Date:** August 17, 2025
**Section/Module:** Identity and Access Management (IAM)
**Duration:** N/A
**Course Progress:** Objectives 2.4 & 4.6

-----

## 📚 Today's Material Covered

- [x] Identity and Access Management Overview
- [x] Multi-Factor Authentication (MFA)
- [x] Password Security and Policies
- [x] Password Attacks and Mitigation
- [x] Single Sign-On (SSO) Technologies
- [x] Federation Concepts
- [x] Privileged Access Management (PAM)
- [x] Access Control Models
- [x] Assigning Permissions and Least Privilege

| Term                                                | Definition                                                                                                                                       |
| --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Identity and Access Management (IAM)**           | Systems and processes managing access to ensure right individuals access right resources at right times for right reasons                       |
| **Identification**                                 | Process where user claims identity using unique identifier like username or email address                                                       |
| **Authentication**                                 | Process of verifying identity of user, device, or system against database of authorized users                                                   |
| **Authorization**                                  | Process determining what permissions or access levels authenticated user has to resources                                                        |
| **Accounting (Auditing)**                         | Process of tracking and recording user activities for compliance, security monitoring, and historical records                                   |
| **Provisioning**                                  | Process of creating new user accounts, assigning permissions, and providing system access                                                       |
| **Deprovisioning**                                | Process of removing individual's access rights when no longer needed (employee departure)                                                       |
| **Identity Proofing**                             | Process of verifying user identity before account creation using trusted data sources or identification documents                               |
| **Interoperability**                              | Ability of different systems, devices, applications to work together and share information using standards like SAML                           |
| **Attestation**                                   | Process of validating that user accounts and access rights are correct and up-to-date through regular reviews                                  |
| **Multi-Factor Authentication (MFA)**             | Security system requiring multiple authentication methods from independent credential categories to verify identity                              |
| **Something You Know (Knowledge Factor)**         | Knowledge-based authentication like passwords, PINs, or security questions                                                                      |
| **Something You Have (Possession Factor)**        | Physical possession authentication using smart cards, hardware tokens, or software tokens                                                       |
| **Something You Are (Inherence Factor)**          | Biometric authentication using fingerprints, facial recognition, voice recognition, or iris scans                                              |
| **Something You Do (Behavior Factor)**            | Behavioral authentication recognizing patterns like keystroke dynamics, mouse movement, or walking gait                                         |
| **Somewhere You Are (Location Factor)**           | Location-based authentication using IP verification, GPS tracking, or specific network connections                                              |
| **Smart Card**                                    | Credit card-sized identification with embedded integrated circuit for processing data in high-security access systems                          |
| **Hardware Token (Key Fob)**                     | Physical device generating unique time-based codes every 30-60 seconds for authentication                                                       |
| **Software Token (Soft Token)**                  | Application generating one-time codes on existing devices like smartphones without dedicated hardware                                           |
| **Authenticator App**                             | Software generating time-based one-time passcodes (Google Authenticator, Microsoft Authenticator)                                              |
| **SMS-Based Token**                               | One-time code sent to registered phone number, valid for 3-10 minutes                                                                          |
| **Biometric Authentication**                      | Authentication using unique biological characteristics with high security (Face ID: 1 in million false acceptance)                             |
| **Single-Factor Authentication**                  | Authentication using single factor type (username + password = one knowledge factor)                                                            |
| **Two-Factor Authentication (2FA)**               | Authentication using two different factor types (knowledge + possession)                                                                        |
| **Passkeys**                                      | Passwordless authentication using public key cryptography with device screen lock functionality                                                 |
| **Password Security**                             | Effectiveness measure of password in resisting guessing and brute-force attacks                                                                 |
| **Password Length**                               | Number of characters in password - longer passwords exponentially increase security (12-16 characters minimum recommended)                     |
| **Password Complexity**                           | Use of uppercase, lowercase, numbers, special characters - increases possible character combinations exponentially                              |
| **Password Reuse**                                | Practice of using same password across multiple accounts or reusing previous passwords on same system                                           |
| **Password Expiration**                           | Policy requiring password changes after certain period (90 days typical, but NIST no longer recommends)                                       |
| **Password Age**                                  | Length of time password has been in use; minimum age prevents rapid cycling to bypass history requirements                                      |
| **Password Manager**                              | Tool storing and managing passwords in centralized encrypted vault with generation, autofill, and sharing capabilities                         |
| **Passwordless Authentication**                   | Authentication methods eliminating passwords using biometrics, hardware tokens, OTP, magic links, or passkeys                                  |
| **Brute Force Attack**                           | Trying every possible character combination until correct password found - time-consuming but thorough                                          |
| **Dictionary Attack**                             | Using list of commonly used passwords and variations including "leet speak" character substitutions                                             |
| **Password Spraying**                            | Trying small number of common passwords against large number of accounts to avoid lockouts                                                      |
| **Hybrid Attack**                                | Combining dictionary and brute force methods, starting with common words then adding variations                                                 |
| **Leet Speak**                                   | Character substitution in passwords replacing letters with numbers/symbols (password becomes P@$$w0rd)                                         |
| **Single Sign-On (SSO)**                         | Authentication allowing access to multiple applications with single set of credentials                                                          |
| **Identity Provider (IdP)**                      | System creating, maintaining, managing identity information and providing authentication services                                               |
| **Lightweight Directory Access Protocol (LDAP)** | Protocol accessing and maintaining distributed directory information services over IP networks                                                  |
| **LDAP over SSL (LDAPS)**                        | Secure version of LDAP using SSL or StartTLS encryption for data transmission                                                                   |
| **Open Authorization (OAuth)**                   | Open standard for token-based authentication allowing third-party access without exposing passwords                                            |
| **JSON Web Token (JWT)**                         | Base64 encoded tokens used by OAuth for transferring claims between parties with digital signature support                                      |
| **Security Assertion Markup Language (SAML)**    | Standard for logging users into applications based on sessions in other contexts using XML assertions                                           |
| **Federation**                                   | Process linking electronic identities across multiple distinct identity management systems using trusted relationships                          |
| **Service Provider**                             | Application or service relying on identity provider for user authentication in federated environment                                           |
| **Privileged Access Management (PAM)**           | Solution restricting and monitoring privileged accounts using JIT permissions, password vaulting, and temporal accounts                        |
| **Just-In-Time (JIT) Permissions**              | Security model granting administrative access only when needed for specific period, then revoking automatically                               |
| **Password Vaulting**                            | Secure storage and management of passwords in digital vault requiring multi-factor authentication for access                                   |
| **Temporal Accounts**                            | Time-limited accounts created for specific purpose, automatically disabled/deleted after predetermined period                                   |
| **Mandatory Access Control (MAC)**               | Access control using security labels where users need equal/higher clearance than resource classification                                       |
| **Discretionary Access Control (DAC)**           | Access control where resource owner specifies which users can access each resource                                                             |
| **Role-Based Access Control (RBAC)**             | Access control assigning users to roles, then assigning permissions to roles rather than individuals                                           |
| **Rule-Based Access Control**                    | Access control using administrator-defined rules applied uniformly across all users (like ACLs)                                               |
| **Attribute-Based Access Control (ABAC)**        | Access control using user, environment, and resource attributes to make dynamic access decisions                                                |
| **Time of Day Restrictions**                     | Access control limiting resource access based on time when request is made (business hours only)                                               |
| **Principle of Least Privilege**                 | Security concept giving users minimum access rights necessary to complete job functions and nothing additional                                  |
| **Permission Creep**                             | Situation where users accumulate excessive permissions as they move between positions without proper cleanup                                    |
| **Local Administrator Account**                   | Most powerful account created during OS setup with system configuration and management capabilities                                             |
| **Standard User Account**                         | Limited account for everyday users restricted to designated storage areas without system configuration rights                                   |
| **Microsoft Account**                             | Free online account for accessing Microsoft services across multiple devices (Windows, Office 365, Xbox)                                       |
| **User Account Control (UAC)**                   | Windows mechanism ensuring administrative actions are explicitly authorized by user with shield icon prompts                                   |

### Important Points

**IAM Four Main Processes:**
- **Identification**: User claims identity with unique identifier (username, email)
- **Authentication**: System verifies claimed identity against authorized user database
- **Authorization**: Determines permissions and access levels for authenticated user
- **Accounting**: Tracks and logs user activities for compliance and security monitoring

**IAM Supporting Concepts:**
- **Provisioning**: Account creation, permission assignment, system access setup for new users
- **Deprovisioning**: Access removal when users leave organization or change roles
- **Identity Proofing**: Identity verification before account creation using trusted sources
- **Interoperability**: System integration using standards (SAML, OpenID Connect) for seamless authentication
- **Attestation**: Regular validation that accounts and access rights remain appropriate

**Multi-Factor Authentication Categories:**
- **Knowledge Factors**: Passwords, PINs, security questions - information only user should know
- **Possession Factors**: Smart cards, hardware tokens, smartphones - something user physically has
- **Inherence Factors**: Fingerprints, facial recognition, iris scans - biometric characteristics
- **Behavior Factors**: Keystroke patterns, mouse movement, signature dynamics - unique user behaviors
- **Location Factors**: GPS tracking, IP verification, network connection - geographic authentication

**Authentication Factor Implementation:**
- **Smart Cards**: Embedded circuits processing data for high-security access (government/enterprise use)
- **Hardware Tokens**: Physical key fobs generating 30-60 second rotating codes
- **Software Tokens**: Smartphone apps (Google/Microsoft Authenticator) or SMS codes
- **Biometric Systems**: Apple Face ID (1 in million false acceptance) vs Touch ID (1 in 50,000)
- **Passkeys**: Public key cryptography with private key secured by device lock screen

**Password Security Characteristics:**
- **Length Impact**: 4-digit PIN (10,000 combinations) vs 8-digit PIN (100 million combinations)
- **Complexity Benefits**: Numbers only (10 options) vs full character set (72+ options per position)
- **Real-World Examples**: "pencils" (0.4 seconds to crack) vs "PencilsAreForWriting" (2 months) vs "P3nc1l5Ar3F0rWr1t1ng!" (15 years)
- **Group Policy Configuration**: Windows gpedit.msc for password length, complexity, history, expiration settings

**Password Policy Components:**
- **Minimum Length**: 12-16 characters recommended, exponential security increase per additional character
- **Complexity Requirements**: Uppercase, lowercase, numbers, special characters (Windows built-in rules)
- **Password History**: Remember 24 previous passwords to prevent immediate reuse
- **Expiration Policies**: NIST no longer recommends rotation unless using password managers
- **Minimum Age**: 3-day minimum prevents rapid cycling to bypass history requirements

**Password Manager Benefits:**
- **Password Generation**: Strong, random, unique passwords with customizable policies
- **Autofill Functionality**: Automatic credential entry reducing human error
- **Secure Sharing**: Grant access without revealing actual passwords
- **Cross-Platform Access**: Synchronization across laptops, browsers, smartphones
- **Trusted Solutions**: 1Password, Bitwarden, Dashlane with enterprise features

**Passwordless Authentication Methods:**
- **Biometric Authentication**: Fingerprint sensors, facial recognition, iris scanning
- **Hardware Tokens**: Physical security keys with digital certificates
- **One-Time Passwords**: Email or SMS codes valid for 3-10 minutes
- **Magic Links**: Email links providing automatic authentication
- **Passkeys**: Browser/OS integration using device security features

**Password Attack Types:**
- **Brute Force**: Systematic testing of all possible combinations (computationally expensive)
- **Dictionary**: Common password lists including "leet speak" variations
- **Password Spraying**: Same few passwords against many accounts (avoids lockouts)
- **Hybrid**: Dictionary words with systematic variations (numbers, special characters)
- **Mitigation**: Length, complexity, MFA, account lockouts, CAPTCHAs

**John the Ripper Demonstration:**
- **Installation**: sudo apt-get install john (Kali Linux pre-installed)
- **MD5 Hash Creation**: echo -n "password" | md5sum | awk '{print $1}' > mypassword.txt
- **Cracking Command**: john --format=Raw-md5 mypassword.txt
- **Results Storage**: ~/.john/john.pot file stores cracked hashes
- **Educational Purpose**: Demonstrates weakness of common passwords and unsalted hashes

**Single Sign-On Operation:**
- **Trusted Relationships**: Between applications and identity providers
- **Process Flow**: Primary IdP authentication → secondary application access → identity verification → access granted
- **Benefits**: Improved user experience, increased productivity, reduced IT costs, enhanced security
- **Enterprise Example**: Windows domain controller authenticating for SharePoint access

**SSO Protocol Technologies:**
- **LDAP**: Directory services for user information sharing and authentication
- **LDAPS**: Secure LDAP over SSL/TLS encryption
- **OAuth**: Token-based authorization for third-party service access
- **JWT**: JSON Web Tokens for secure claims transfer
- **SAML**: XML-based assertions for cross-domain authentication

**Federation Implementation:**
- **Six-Step Process**: Login initiation → IdP redirection → user authentication → assertion generation → service provider return → verification/access
- **Trust Relationships**: Cross-organizational authentication without local account management
- **Benefits**: Simplified user experience, reduced administrative overhead, improved security
- **Real-World Example**: Google account login for third-party services

**Privileged Access Management Components:**
- **Just-In-Time Permissions**: Administrative access granted only during specific tasks
- **Password Vaulting**: Secure credential storage with MFA access requirements
- **Temporal Accounts**: Time-limited contractor/project accounts with automatic expiration
- **Audit Logging**: Comprehensive tracking of privileged account usage

**Access Control Model Comparison:**
- **MAC**: Security labels determine access (military classifications: Unclassified < Confidential < Secret < Top Secret)
- **DAC**: Resource owners control access permissions (file sharing scenarios)
- **RBAC**: Role membership determines permissions (department groups: Accounting, HR, Employees)
- **Rule-Based**: Administrator rules apply to all users (firewall ACLs, time restrictions)
- **ABAC**: Dynamic decisions using user, environment, resource attributes

**Access Control Implementations:**
- **Time Restrictions**: Business hours access (8 AM - 6 PM), preventing after-hours misuse
- **Least Privilege**: Minimum necessary access for job functions
- **Permission Creep**: Accumulated excess permissions from role changes requiring regular review
- **Group Management**: Windows groups implementing RBAC with inheritance

**User Account Management:**
- **Administrator Accounts**: Full system control for configuration and management tasks
- **Standard User Accounts**: Limited access to designated areas without system modification rights
- **Microsoft Accounts**: Cloud-based authentication for cross-device Microsoft services
- **User Account Control**: Administrative action confirmation with shield icon prompts

**File and Folder Permissions:**
- **Permission Types**: Read, write, execute, full control
- **Inheritance**: Folder permissions apply to contained files
- **Security Tab**: Windows Properties → Security for permission management
- **Group Permissions**: Users inherit permissions from group membership
- **Best Practices**: Grant minimal necessary permissions, regular permission audits

## 🏷️ Domain Tags

**#Domain2** - Threats, Vulnerabilities & Mitigations
- Password attack analysis and indicators
- Authentication factor vulnerabilities
- Credential compromise detection

**#Domain4** - Security Operations
- Identity and access management implementation
- Privileged access management
- Access control model deployment
- Permission assignment and maintenance