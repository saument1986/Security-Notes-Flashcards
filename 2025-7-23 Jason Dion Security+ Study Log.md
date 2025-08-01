# Jason Dion Security+ Study Log

**Date:** {{2025-7-23}}
**Section/Module:**4
**Duration:** 
**Course Progress:** 14 % complete

-----

## 📚 Today’s Material Covered

- [x] Surveillance sytems 
- [x] Access control vestibules
- [x] Access badge cloning

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                           | Definition                                                                                                                                       |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Access control Vestibule**   | Double-door system that is designed with two doors that are electronically controlled to ensure that only one door can be opened at a given time |
| **Piggybacking**               | person with legitimate access intentionally allows another person without authorization to ent a secure area with them                           |
| **Tailgating**                 | Unauthorized person follows somone with legitimate access to the secure space without their knowledge or consent                                 |
| **Door Locks**                 | Physical security control that is designed to secure entryways by restricting and regulating access to particular space or property              |
| **False Acceptance Rate(FAR)** | The rate that the system authenticates a user as valid, even though that person should not have been granted access to the system                |
| **False Rejection Rate(FRR)**  | Occurs any time the bio metrics system denies a user who should have been allowed access to the system                                           |
| **Equal Error Rate (EER)**     | More commonly called *Crossover error rate* (CER) which uses a measure of the effectiveness of a given bio metrics system to achieve a balance   |
| **Access Badge Cloning**       | Refers to copying the data from an RFID or NFC card or badge onto another card or device                                                         |

### Important Points

- Visual obstruction, blind sensors or cameras, acoustic interference, electric magnetic interference, physical environment attacks
- Tamper alarms backup power supplies or encrypt frequencies
- **Access Control Vestibules**
	- provide a controlled environment for anyone trying to access an organizations facility
	- prevent piggybacking and tailgating
	- often require an access badge
- **Door Locks**
	- False acceptance or false rejection in fingerprint scanners
	- check Cross over error rate
	- Many modern door locks have multi factor
	- older Cipher locks 
	- not all door locks provide the same protection
- **Access Badge Cloning** 
	- RFID and NFC are popular technologies used for contactless authentication in various applicaion
	- Access Badge Cloning
		- Scanning
			- An attacker can use a handheld RFID or NFC reader to capture data from a victims card and store it for further processing
			- An attacker still needs to be relatively close to the access badge to clone it
		- Data Extraction
			- Once the data is captured, attackers extract the relevant authentication credentials from the card
		- Writing to a new card
			- Using specialized writing tools the attacker will then transfer the extracted data into a blank RFID or NFC card
		- Using a cloned access badge
			- Now that the attacker has their cloned access badge or device in hand they can gain unauthorized access to buildings computer sytems or even make payments
		- Prevention
			- Implement advanced encrytption in card-based authentication systems
			- Implement Multi-factor Authentication
			- Regularly update the security protocols
			- Educate the users
			- Users should implement the use of shielded wallets or sleeves with RFID access badges
			- monitor and audit access logs
## 🔗 Related Notes & Links

- [[Domain 1 - Attacks, Threats & Vulnerabilities]]
- [[Domain 2 - Architecture and Design]]
- [[Domain 3 - Implementation]]
- [[Domain 4 - Operations & Incident Response]]
- [[Domain 5 - Governance, Risk & Compliance]]



