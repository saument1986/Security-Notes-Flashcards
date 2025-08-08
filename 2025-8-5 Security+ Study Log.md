# Security+ Study Log

**Date:** August 5, 2025
**Section/Module:** Cryptographic Algorithms & Public Key Infrastructure
**Course Progress:** 28%

-----

## 📚 Today's Material Covered

- [x] Symmetric Algorithm Overview
- [x] DES (Data Encryption Standard)
- [x] 3DES (Triple DES)
- [x] IDEA (International Data Encryption Algorithm)
- [x] AES (Advanced Encryption Standard)
- [x] Blowfish and Twofish
- [x] RC Cipher Suite (RC4, RC5, RC6)
- [x] Asymmetric Algorithm Overview
- [x] Public Key Cryptography Concepts
- [x] Diffie-Hellman Key Exchange
- [x] RSA Algorithm
- [x] ECC (Elliptic Curve Cryptography) and Variants
- [x] Hashing Fundamentals
- [x] MD5, SHA Family, RIPEMD, HMAC
- [x] Digital Signatures
- [x] Hash Security (Pass-the-Hash, Birthday Attacks)
- [x] Key Stretching, Salting, Nonce
- [x] Public Key Infrastructure (PKI)
- [x] Digital Certificates and X.509
- [x] Certificate Authorities and Trust Models

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                                               | Definition                                                                                                                                                                             |
| -------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Symmetric Algorithm**                            | A method of encryption where the same key is used for both encryption and decryption of data                                                                                           |
| **Asymmetric Algorithm**                           | Encryption method that uses two different keys (public and private key pair) for encryption and decryption. Also called Public Key Cryptography                                        |
| **Public Key**                                     | Freely available key that anyone can access and use for encryption or signature verification                                                                                           |
| **Private Key**                                    | Secret key known only to the owner, used for decryption or creating digital signatures                                                                                                 |
| **Digital Signature**                              | Hash digest of a message encrypted with sender's private key, providing integrity and non-repudiation                                                                                  |
| **DES (Data Encryption Standard)**                 | Uses a 64-bit key with 8 bits for parity, resulting in an effective 56-bit key length. Breaks messages into 64-bit blocks through 16 rounds of transposition and substitution          |
| **3DES (Triple DES)**                              | Modified version of DES using three different 56-bit keys. Process: encrypt with first key, decrypt with second key, encrypt with third key, creating effective 112-bit encryption     |
| **IDEA (International Data Encryption Algorithm)** | Symmetric block cipher using 64-bit blocks with 128-bit key size. Commonly used in PGP (Pretty Good Privacy) suite                                                                     |
| **AES (Advanced Encryption Standard)**             | Also known as Rijndael algorithm. Can use 128-bit, 192-bit, or 256-bit keys. Winner of NIST contest to replace DES, now the defacto standard for symmetric encryption                  |
| **Blowfish**                                       | Block cipher using 32-bit to 448-bit encryption key, encrypts 64 bits of data at a time. Developed as DES replacement but not widely utilized                                          |
| **Twofish**                                        | Uses 128-bit blocks with 128-bit, 192-bit, or 256-bit encryption keys. Never patented and released as open source                                                                      |
| **RC Cipher Suite**                                | Created by Ron Rivest. RC4 is a stream cipher with variable key size (40-2,048 bits). RC5 is a block cipher with keys up to 2,048 bits. RC6 is based on RC5 but stronger               |
| **Diffie-Hellman**                                 | Asymmetric algorithm used for key exchanges and secure key distribution, especially in VPN tunnel establishment. Susceptible to on-path/person-in-the-middle attacks                   |
| **RSA**                                            | Named after Rivest, Shamir, and Adleman. Used for key exchange, encryption, and digital signatures. Relies on difficulty of factoring large prime numbers. Supports 1024-4096 bit keys |
| **ECC (Elliptic Curve Cryptography)**              | Asymmetric algorithm based on algebraic structure of elliptical curves. About 6x more efficient than RSA - 256-bit ECC equals 2048-bit RSA security. Used heavily in mobile devices    |
| **ECDH**                                           | Elliptic Curve Diffie-Hellman - ECC version of Diffie-Hellman key exchange protocol                                                                                                    |
| **ECDHE**                                          | Elliptic Curve Diffie-Hellman Ephemeral - uses different key for each portion of key establishment process                                                                             |
| **ECDSA**                                          | Elliptic Curve Digital Signature Algorithm - used by US Government for digital signature needs                                                                                         |
| **Hashing**                                        | One-way cryptographic function that takes input and produces unique message digest. No way to determine original message from hash                                                     |
| **MD5**                                            | Creates 128-bit hash value. Most popular historically but vulnerable to collisions due to limited unique values                                                                        |
| **SHA Family**                                     | Secure Hash Algorithm family including SHA-1 (160-bit), SHA-2 (224-512 bits), SHA-3 (224-512 bits with 120 rounds)                                                                     |
| **RIPEMD**                                         | Race Integrity Primitive Evaluation Message Digest. Open source algorithm with 160-bit, 256-bit, and 320-bit versions                                                                  |
| **HMAC**                                           | Hash-based Message Authentication Code. Used with other algorithms (HMAC-MD5, HMAC-SHA256) for integrity and authenticity                                                              |
| **Pass-the-Hash Attack**                           | Technique allowing attacker to authenticate using hash of password instead of plaintext password                                                                                       |
| **Birthday Attack**                                | Attack that finds two different messages with same hash digest (collision) based on birthday paradox                                                                                   |
| **Key Stretching**                                 | Technique to enhance weaker keys by running through algorithm to create longer, more secure key                                                                                        |
| **Salting**                                        | Addition of random data to password before hashing to ensure different outputs for same passwords                                                                                      |
| **Nonce**                                          | Number used once - unique random number added to authentication process to prevent replay attacks                                                                                      |
| **PKI (Public Key Infrastructure)**                | System of hardware, software, policies, procedures, and people based on asymmetric encryption                                                                                          |
| **Certificate Authority (CA)**                     | Trusted third party that issues and manages digital certificates                                                                                                                       |
| **Digital Certificate**                            | Digitally signed electronic document binding public key with user's identity using X.509 standard                                                                                      |
| **Wildcard Certificate**                           | Allows all sub-domains to use same public key certificate (e.g., *.example.com)                                                                                                        |
| **Self-signed Certificate**                        | Certificate signed by same entity whose identity it certifies, no external verification                                                                                                |
| **Third-party Certificate**                        | Certificate issued and signed by trusted CA, embedded in browsers and OS                                                                                                               |
| **Root of Trust**                                  | Chain of trust concept where certificates validated from bottom to top through certification path                                                                                      |
| **Certificate Signing Request (CSR)**              | Block of encoded text containing information about entity requesting certificate, includes public key                                                                                  |
| **Certificate Revocation List (CRL)**              | Online list of digital certificates that CA has revoked due to compromise                                                                                                              |
| **OCSP**                                           | Online Certificate Status Protocol - determines revocation status of single certificate using serial number                                                                            |
| **OCSP Stapling**                                  | Allows certificate holder to get OCSP record at intervals and include in SSL/TLS handshake                                                                                             |
| **Public Key Pinning**                             | Resistance to impersonation attacks by presenting trusted public keys in HTTP header                                                                                                   |
| **Key Escrow**                                     | Process where cryptographic keys stored in secure third-party location for recovery                                                                                                    |
| **Block Cipher**                                   | Encryption method that processes data in fixed-size blocks                                                                                                                             |
| **Stream Cipher**                                  | Encryption method that processes data one bit or byte at a time                                                                                                                        |

### Important Points

**Symmetric Encryption:**
- **Symmetric vs Asymmetric**: Symmetric uses same key for encryption/decryption, asymmetric uses different keys
- **DES Weakness**: Only 56-bit effective key length, vulnerable to modern computing power
- **AES Dominance**: Most commonly used and strongest symmetric algorithm covered
- **RC4 Exception**: Only symmetric cipher discussed that is a stream cipher (all others are block ciphers)
- **Government Standard**: AES is the encryption standard used by federal government for sensitive but unclassified information
- **Historical Context**: DES used from 1970s to early 2000s before being replaced by stronger algorithms
- **Open Source Options**: Both Blowfish and Twofish were never patented and released as open source
- **RC Evolution**: RC1 never published, RC2 considered weak, RC3 cracked before release, RC4-RC6 commonly used

**Asymmetric Encryption:**
- **Four Security Services**: Public key cryptography provides confidentiality, integrity, authentication, and non-repudiation
- **Confidentiality**: Encrypt with receiver's public key - only receiver can decrypt with their private key
- **Non-repudiation**: Encrypt with sender's private key - proves sender identity since only they have the private key
- **Digital Signatures**: Hash message + encrypt hash with sender's private key = integrity + non-repudiation
- **Key Exchange Usage**: Diffie-Hellman commonly used for VPN tunnel establishment and IPSec
- **RSA Applications**: Used in secure tokens for multifactor authentication (6-digit changing numbers)
- **ECC Efficiency**: 6x more efficient than RSA - 256-bit ECC = 2048-bit RSA security level
- **Mobile Optimization**: ECC preferred for mobile devices due to lower processing power requirements
- **Vulnerability**: Diffie-Hellman susceptible to on-path/person-in-the-middle attacks without authentication

**Hashing:**
- **One-way Function**: Cannot reverse hash to get original message - acts as digital fingerprint
- **Fixed Length Output**: Hash digest always same length regardless of input size
- **Collision Vulnerability**: Two different inputs producing same hash (especially problematic with MD5)
- **SHA Evolution**: SHA-1 (160-bit) → SHA-2 (224-512 bit) → SHA-3 (more secure with 120 rounds)
- **Digital Signature Process**: Hash file → encrypt hash with private key → attach to message
- **Code Signing**: Used for mobile apps and software to ensure integrity and authenticity
- **Hash Sensitivity**: Changing even one character drastically changes entire hash output

**Hash Security:**
- **Pass-the-Hash Defense**: Use trusted OS, proper domain trusts, patching, MFA, least privilege
- **Birthday Attack Prevention**: Use longer hash digests (SHA-256 over MD5) to reduce collisions
- **Key Stretching**: Apply hash function multiple times to make brute force more expensive
- **Salting Benefits**: Defeats dictionary attacks, brute force attacks, and rainbow tables
- **Nonce Usage**: Prevents replay attacks by ensuring different outputs each time
- **Account Lockout**: Limit failed login attempts (typically 3) to slow down attackers

**PKI and Digital Certificates:**
- **PKI vs Public Key Crypto**: PKI is entire system, public key crypto is just encryption/decryption part
- **HTTPS Process**: Browser gets server's public key from CA → encrypts shared secret → establishes symmetric tunnel
- **Certificate Types**: Single-use, wildcard (*.domain.com), SAN (multiple domains), single/dual-sided
- **Trust Chain**: Root CA → Intermediate CA → End Entity Certificate (like family tree)
- **Certificate Management**: CSR generation → CA validation → certificate issuance → revocation if needed
- **Revocation Methods**: CRL (full list), OCSP (single lookup), OCSP stapling (included in handshake)
- **Security Measures**: Public key pinning prevents impersonation, key escrow enables recovery
- **X.509 Standard**: Common format for digital certificates containing identity and public key info

## 🔗 Related Links & Notes
