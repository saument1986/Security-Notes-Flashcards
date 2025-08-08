# Security+ Study Log

**Date:** {{2025-8-4}}
**Section/Module:** 8
**Duration:** 60minutes
**Course Progress:** 26% complete

-----

## 📚 Today’s Material Covered

- [ ] Cryptographic Solutions
- [ ] 
- [ ] 

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                              | Definition                                                                                                            |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Encryption**                    | Process of converting ordinary information (plaintext) into an unintelligible form (ciphertext)                       |
| **Algorithm**                     | Mathematical function                                                                                                 |
| **Key**                           | Essential piece of information that determines the output of a cipher                                                 |
| **Symmetric Algorithms**          | Use the same key for both encryption and decryption                                                                   |
| **Asymmetric Algorithms**         | Use a pair of keys, a public key for encryption and a private key for decryption                                      |
| **Steganography**                 | The practice of hiding secret data within ordinary, non-secret files or messages to avoid detection                   |
| **Tokenization**                  | Substitutes sensitive data elements with non-sensitive equivalents called tokens                                      |
| **Data Masking/Data Obfuscation** | Process of disguising original data to protect sensitive information while maintaining its authenticity and usability |
| **Hybrid Implementation**         | Utilizes asymmetric encryption to securely transfer a private key that can then be used with symmetric encryption     |
| **Stream Cipher**                 | Utilizes a keystream generator to encrypt data bit by bit using a mathematical XOR function to create the ciphertext  |
| **Block Cipher**                  | Breaks the input into fixed-length blocks of data and performs the encryption on each block                           |

### Important Points

- **Encryption**
	- used to protect Data at rest, Data in transit and Data in use
	- uses cipher algorithms
	- Strength comes from the key not the algorithm
	- Use larger keys and rotate keys frequently
	- The length of a key is proportional to the level of security it provides
	- Most encryption algorithms are open-source and publicly accessible
- **Symmetric Encryption**
	- Single Key
	- (Private Key) Encryption algorithm in which both the sender and the receiver must know the same shared secret using a privately held key
	- faster than asymmetric
- **Asymmetric Encryption**
	- Two different keys
	- (Public Key) Encryption algorithm where different keys are used to encrypt and decrypt the data
	- Diffie-Hellman
	- RSA (Ron Rivest, Adi Shamir, and Leonard Adleman)
	- Elliptic Curve Cryptography (ECC)
- **Hybrid Implementation**
	- Best of both worlds
- **Stream Cipher
- **Block Cipher** 
	- easier to setup and implement

## 🔗 Related Notes & Links