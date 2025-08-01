# Jason Dion Security+ Study Log

**Date:** {{2025-7-30}}
**Section/Module:** 6
**Duration:** 50 Minutes
**Course Progress:** 22% complete

-----

## 📚 Today’s Material Covered

- [x] Rootkit
- [x] Backdoor
- [x] Logic bombs
- [x] Keyloggers
- [x] Spyware
- [x] Bloatware
- [x] Exploit Techniques
- [x] Indications of malware attacks

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                    | Definition                                                                                                                    |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Kernel Mode**         | Allows a system to control access to things like device drivers, sound card, and monitor                                      |
| **DLL Injection**       | Technique used to run arbitrary code within the address space of another process by forcing it to load a dynamic-link library |
| **Shim**                | Software code that is placed between two components                                                                           |
| **Easter Egg**          | Insecure coding practice that was used by programmers to provide a joke or a gag gift to the users                            |
| **Exploit Technique**   | Describes the specific method by which malware code infects a target host                                                     |
| **Fileless Malware**    | Used to create a process in the system memory without relying on the local file system of the infected host                   |
| **Dropper**             | Initiates or runs other malware forms within a payload on an infected host                                                    |
| **Downloaders**         | Retrieves additional tools post the initial infection facilitated by a dropper                                                |
| **Shellcode**           | Encompasses lightweight code meant to execute an exploit on a given target                                                    |
| **Concealment**         | Used to help the threat actor prolong unauthorized access to a system by hiding any evidence of malicious activities          |
| **Living Off the Land** | A strategy adopted by many advanced persistent threats and criminal organizations                                             |

### Important Points

- **Rootkit**
	- Allows highest level of permissions on affected system
	- ring 3 user permissions
	- ring 0 kernel mode
	- Ring 1 root user
	- tries to move to root 0 to avoid detection
	- digs deeply into the operating system
	- DLL Injections
	- Shim intercepts between OS and DLL Injections 
	- Traditional antivirus usually wont see it
- **Backdoors**
	- created for maintenance
	- some programmers still add backdoors
	- vulnerable to Remote access trojans
- **Easter Egg**
	- Do a barrel roll on google
	- Usually pretty harmless but add additional code which can create vulnerabilities
	- closely linked to Logic bombs
- **Logic Bomb**
- **Keylogger**
	- Originally developed by system administrators
	- Records every keystroke
	- software or hardware based
	- can evade antivirus
	- can steal sensitive information
	- good antivirus, updates and patches, physical checks, Training, MFA, encrypt keystrokes
- **Spyware**
	- Monitors and transmits 
	- can slow system down
	- only download through trusted sources
	- make sure systems stay up to date
- **Bloatware**
	- Pre-installed
	- uses ram and storage space
	- usually not malicious
	- Remove extra software and applications not used
	- Perform a clean Operation system install
- **Exploit Technique**
	- some focus on infecting memory
	- can be created to use fileless techniques
	- erases artifacts after installation
	- Stage 1 dropper or downloader
	- stage 2 Downloader
	- Execute primary objectives
	- conceal
	- *"Living off the land"* 
		- Try to exploit the standard system tools to perform intrusions
- **Indications of Malware attacks**
	- Account Lockout
		- Looks like multiple failed attempts
	- Concurrent session utilization
		- Should only be 1 user session at a time
	- Blocked Content
		- sudden increase in blocked content
	- Impossible Travel
		- access from 2 geographical locations with impossible travel time
	- Resource consumption
		- Unusual spikes that cant be linked to programs or reason
	- Resource inaccessibility
		- Ransomware makes data or resources unavailable
	- out-of-cycle logging
		- outside of normal hours 
	- missing logs
		- Delete logs to hide their tracks
	- published or documented attacks
		- If your organizations mentioned in a tabloid 

## 🔗 Related Notes & Links

- [[Domain 1 - Attacks, Threats & Vulnerabilities]]
- [[2025-7-29 Jason Dion Security+ Study Log]]


