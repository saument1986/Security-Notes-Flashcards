# Security+ Study Log

**Date:** {{2025-7-29}}
**Section/Module:** 6
**Duration:** 65 minutes
**Course Progress:** 20% complete

-----

## 📚 Today’s Material Covered

- [x] Malware
- [x] Botnets
- [x] Ransomeware
- [x] zombies

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                                | Definition                                                                                                                                                                                                                  |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Worms**                           | Standalone malware programs that replicate and spread to other systems by exploiting software vulnerabilities                                                                                                               |
| **Trojans**                         | Malicious programs which appear to be legitimate software that allow unauthorized access to a victims system when executed                                                                                                  |
| **Ransomware**                      | Encrypts a users data and holds it hostage until a ransom is paid to the attacker for decryption                                                                                                                            |
| **zombies**                         | Compromised computers that are remotely controlled by attackers and used in coordination to form a botnet                                                                                                                   |
| **Botnet**                          | Network of zombies and are often used for DDoS attacks, spam distribution, or cryptocurrency mining                                                                                                                         |
| **Rootkits**                        | Malicious tools that hide their activities and operate at the OS level to allow for ongoing privileged access                                                                                                               |
| **Backdoors**                       | Malicious means of bypassing normal authentication processes to gain unauthorized access to a system                                                                                                                        |
| **Logic Bombs**                     | Embed code placed in legitimate programs that executes a malicious action when a specific condition or trigger occurs                                                                                                       |
| **Keyloggers**                      | Record a users keystrokes to capture passwords or other sensitive information                                                                                                                                               |
| **Spyware**                         | Secretly monitors and gathers user information or activities and sends data to third parties                                                                                                                                |
| **Bloatware**                       | Unnecessary or pre-installed software that consumes system resources and space without offering any value to the user                                                                                                       |
| **Malware Exploitation Techniques** | Involves methods by which malware infiltrates and infects targeted systems                                                                                                                                                  |
| **Boot Sector Virus**               | Stored in the first sector of a hard drive and is then loaded into memory whenever the computer boots up                                                                                                                    |
| **Macro Virus**                     | A form of code that allows a virus to be embedded inside another document so that when that document is opened by the user, the virus is executed                                                                           |
| **Program Virus**                   | Tries to find executable or application files to infect with their malicious code                                                                                                                                           |
| **Multipartite Virus**              | A combination of a boot sector type virus and a program virus                                                                                                                                                               |
| **Encrypted Virus**                 | Designed to hide itself from being detected by encrypting its malicious code or payloads to avoid detection by any antivirus software                                                                                       |
| **Polymorphic Virus**               | Advanced version of an encrypted virus, but instead of just encrypting the contents, it will actually change the virus's code each time it is executed by altering the decryption module in order for it to evade detection |
| **Metamorphic Virus**               | Able to rewrite itself entirely before it attempts to infect a given file                                                                                                                                                   |
| **Stealth Virus**                   | Not necessarily a specific type of virus as much as it is a technique used to prevent the virus from being detected by the anti-virus software                                                                              |
| **Armored Virus**                   | Have a layer of protection to confuse a program or a person who's trying to analyze it                                                                                                                                      |
| **Hoax**                            | A form of technical social engineering that attempts to scare end users into taking undesirable action on their system                                                                                                      |
| **Remote Access Trojan (RAT)**      | Type of Trojan that is widely used by modern attackers because it provides the attacker with remote control of a victim machine                                                                                             |
| **Command and Control Node**        | Responsible for managing and coordinating the activities of other nodes or devices within a network                                                                                                                         |

### Important Points

- **Viruses**
	- Boot sector virus
		- specific antivirus that looks for boot sector virus
	- Macro Virus
		- embedded in documents or spreadsheets
	- Program Virus
		- infects every time a compromised program is run
	- Multipartite virus
		- Even if a cybersecurity professional finds the program part of the virus and cleans it out from within the operating system, they may have missed the boot sector portion
	- Encrypted Virus
		- Harder for antivirus software to find
	- Polymorphic Virus
		- Morphs so signature based antiviruses cant detect it
	- Metamorphic virus
		- More advanced version of a polymorphic virus
	- Armored virus
		- confuse system or person trying to analyze it
	- Hoax
		- type of technical social engineering
	- Multiple types can be combined to create a sophisticated virus
	- Worm
		- can replicate itself without any user interaction
		- Can infect the workstation and other computing assets
		- can cause disruption to the normal network traffic since they are constantly trying to replicate and spread across the network
		- Can create a DOS
		- worms are best known for spreading far and wide over the internet in a relatively short amount of time
		- *conficker* 
	- Trojans
		- appears to be a piece of desirable software
			- Remote access trojan
				- allows remote access 
	- Ransomware
		- Conducting regular backups
			- backup all important data,files,and systems
		- installing regular software updates
		- providing security awareness training
		- implementing multi-factor authentication for the systems
		- never pay the ransom
		- disconnect from the network
		- notify authorities
		- restore from known good backups after ensuring ransomware has been removed
	- Botnet
		- enables use of processing, memory, storage, and networking without victims consent
		- Made up of a group of zombies
		- Controlled by command and control node
		- Used to store illegal material
		- used to combine processing power to break through different types of encryption

## 🔗 Related Notes & Links

- [[Domain 1 - Attacks, Threats & Vulnerabilities]]
- [[2025-7-28 Jason Dion Security+ Study Log]]


