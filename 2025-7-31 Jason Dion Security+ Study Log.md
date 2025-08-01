# Jason Dion Security+ Study Log

**Date:** {{2025-7-31}}
**Section/Module:** 7
**Duration:** 56 Mins
**Course Progress:** 24% complete

-----

## 📚 Today’s Material Covered

- [x] Data Protection
- [x] Data Classifications
- [x] Data Ownership
- [x] Data States 

## 🔑 Key Concepts & Definitions

### New Terms Learned

| Term                               | Definition                                                                                                                                                    |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Data Protection**                | Process of safeguarding important information from corruption compromise, or loss                                                                             |
| **Data Sovereignty**               | Information is subject to the laws and governance structures within the nation where it is collected                                                          |
| **Data Loss Prevention (DLP)**     | Strategy for ensuring sensitive or critical information does not leave an organization                                                                        |
| **Data Classification**            | Category based on the organization's value and the sensitivity of the information if it were to be disclosed                                                  |
| **Sensitive Data**                 | Any information that can result in a loss of security or a loss of advantage to a company if accessed by an unauthorized person                               |
| **Data Ownership**                 | Process of identifying the person responsible for the confidentiality, integrity, availability, and privacy of the information assets                         |
| **Data Owner**                     | Senior executive role that has the responsibility for maintaining the confidentiality, integrity, and availability, of the information asset                  |
| **Data Controller**                | Entity that holds responsibility for deciding the purposes and methods of data storage, collection, and usage, and for guaranteeing the legality of processes |
| **Data Proccessor**                | Group or individual hired by the data controller to help with tasks like collecting, storing, or analyzing data                                               |
| **Data Steward**                   | Focused on the quality of the data and the associated metadata                                                                                                |
| **Data Custodian**                 | Responsible for handling the management of the system on which the data assets are stored                                                                     |
| **Privacy Officer**                | Role that is responsible for the oversight of any kind of Privacy-Related data, like PII, SPI, or PHI                                                         |
| **Data at Rest**                   | Refers to any data stored in database, file systems, or other storage systems                                                                                 |
| **Data in Transit/Data in Motion** | Refers to data actively moving from one location to another, such as across the internet or through a private network                                         |
| **Data in Use**                    | Refers to data in the process of being created, retrieved, updated, or deleted                                                                                |

### Important Points

- Overclassifying data leads to protecting all data at a high level
- Classification is based on whether you are a commercial business or Government organization
- **Business**
	- Public
		- Has no impact on the company if released and is often posted in an open-source environment
	- Sensitive
		- Has minimal impact if released (Organization's financial data)
	- Private
		- Contains data that should only be used within the organization
		- Relates to an individual entity
	- Confidential
		- Contains items such as trade secrets, intellectual property data, and source code that affect the business if disclosed
	- Critical
		- Contains valuable information
		- ex: credit card information
- **Government classifications**
	- Unclassified
		- Data that can be released to the public or under the Freedom of Information Act
	- Sensitive but unclassified
		- Data that would not hurt national security if released but could impact those whose data was being used
		- Ex: Medical records
	- Confidential
		- Data that could seriously affect the government if unauthorized disclosures happen
	- Secret
		- Data that could seriously damage national security if disclosed
	- Top Secret
		- Data that would damage national security if disclosed
- **Life Cycle**
	- Collect
	- Retain
	- Dispose
	- Should be defined in policies
	- Follow the local,state,and government laws and regulations for data retention time requirements
- **Data Owner**
	- Ultimate responsibility
	- labels assets and determines protection level
- **Data Controller**
	- Holds ultimate accountability
- **Data Processor**
	- Work at the direction of the data controller
- **Data Steward**
	- Ensures data is appropriately labeled and classified
- **Data Custodian**
	- System administrators
- **Privacy Officer**
	- is on the hook for data breach
	- Make sure you are compliant
- The Data owner should be a business entity responsible for creating this information, with each owner being assigned to their own department
- IT people should not be the data owners, but rather those who know more about the data based on the content of the company
**Data States**
- Data at Rest
	- Not actively moving
	- prime target for threat actors
	- best if encrypted
		- Full Disk Encryption
			- Encrypts the entire hard drive
		- Partition Encryption
			- Encrypts specific partitions of a hard drive
		- File Encryption
			- Encrypts individual files
		- Volume Encryption
			- Encrypts a set of selected files or directories
		- Database Encryption
			- Encrypts data stored in a database
		- Record Encryption
			- Encrypts specific fields within a database record
-  **Data in Transit**
	- Vulnerable to interception 
	- Encryption methods
		- SSL, TLS, VPN's and IPSec
		- SSL and TLS
			- Cryptiographic protocols designed to provide secure communication over a computer network
		- VPN
			- Technology that creates a secure connection over a less secure network
		- IPSec
			- Protocol suite used to secure IP communications by authenticating and encrypting each IP packet in a data stream
- **Data in Use**
	-  actively being processed

## 🔗 Related Notes & Links

- [[Domain 1 - Attacks, Threats & Vulnerabilities]]
- [[Domain 3 - Implementation]]
- [[Domain 4 - Operations & Incident Response]]
- [[Domain 5 - Governance, Risk & Compliance]]


