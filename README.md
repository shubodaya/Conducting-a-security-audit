# Security audit on Botium Toys company 
#### This company is a fictional company. The company has a single physical location, which serves as its main office, a storefront, and a warehouse for its products. 
## Scope and goals of the audit
#### Scope: The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. To review the assets Botium Toys has and the controls and compliance practices they have in place.
#### Goals: Assessing existing assets and completing the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.
## Current assets
#### Assets managed by the IT Department include:
1. On-premises equipment for in-office business needs
2. Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
3. Storefront products available for retail sale on-site and online; stored in the company’s adjoining warehouse
4. Management of systems, software, and services: accounting, telecommunication, database, security, e-commerce, and inventory management
5. Internet access
6. Internal network
7. Data retention and storage
8. Legacy system maintenance: end-of-life systems that require human monitoring
## Risk assessment
### Risk description
#### Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.
### Control best practices
#### The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
### Risk score
#### On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.
### Additional comments
##### The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:
1. Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.
2. Encryption is not currently used to ensure confidentiality of customers’ credit
card information that is accepted, processed, transmitted, and stored locally in
the company’s internal database.
3. Access controls pertaining to least privilege and separation of duties have not
been implemented.
4. The IT department has ensured availability and integrated controls to ensure
data integrity.
5. The IT department has a firewall that blocks traffic based on an appropriately
defined set of security rules.
6. Antivirus software is installed and monitored regularly by the IT department.
7. The IT department has not installed an intrusion detection system (IDS).
8. There are no disaster recovery plans currently in place, and the company does
not have backups of critical data.
9. The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
10. Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
11. There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
12. While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.
13. The store’s physical location, which includes Botium Toys’ main offices, store
front, and warehouse of products, has sufficient locks, up-to-date
closed-circuit television (CCTV) surveillance, as well as functioning fire
detection and prevention systems.
## Controls and compliance checklist
### Controls assessment checklist
#### Least Privilege: Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach.                                             
- [ ] Yes
- [x] No
#### Disaster recovery plans: There are no disaster recovery plans in place. These need to be implemented to ensure business continuity.
- [ ] Yes
- [x] No
#### Password policies: Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network.
- [ ] Yes
- [x] No
#### Separation of duties: Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll.
- [ ] Yes
- [x] No
#### Firewall: The existing firewall blocks traffic based on an appropriately defined set of security rules.
- [x] Yes
- [ ] No
#### Intrusion detection system (IDS): The IT department needs an IDS in place to help identify possible intrusions by threat actors.
- [ ] Yes
- [x] No
#### Backups: The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity.
- [ ] Yes
- [x] No
#### Antivirus software: Antivirus software is installed and monitored regularly by the IT department.
- [x] Yes
- [ ] No
#### Manual monitoring, maintenance, and intervention for legacy systems: The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach.
- [ ] Yes
- [x] No
#### Encryption: Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information.
- [ ] Yes
- [x] No
#### Password management system: There is no password management system currently in place; implementing this control would improve IT department/other employee productivity in the case of password issues.
- [ ] Yes
- [x] No
#### Locks (offices, storefront, warehouse): The store’s physical location, which includes the company’s main offices, store front, and warehouse of products has sufficient locks.
- [x] Yes
- [ ] No
#### Closed-circuit television (CCTV) surveillance: CCTV is installed/functioning at the store’s physical location.
- [x] Yes
- [ ] No
#### Fire detection/prevention (fire alarm, sprinkler system, etc.): Botium Toys’ physical location has a functioning fire detection and prevention system.
- [x] Yes
- [ ] No
### Payment Card Industry Data Standard (PCI DSS)
#### Only authorized users have access to customers’ credit card information: Currently, all employees have access to the company’s internal data.
- [ ] Yes
- [x] No
#### Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment: Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information.
- [ ] Yes
- [x] No
#### Implement data encryption procedures to better secure credit card transaction touchpoints and data: The company does not currently use encryption to better ensure the confidentiality of customers’ financial information.
- [ ] Yes
- [x] No
#### Adopt secure password management policies: Password policies are nominal and no password management system is currently in place.
### General Data Protection Regulation (GDPR)
#### E.U. customers’ data is kept private/secured: The company does not currently use encryption to better ensure the confidentiality of customers financial information.
- [ ] Yes
- [x] No
#### There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach: There is a plan to notify E.U. customers within 72 hours of a data breach.
- [x] Yes
- [ ] No
#### Ensure data is properly classified and inventoried: Current assets have been inventoried/listed, but not classified.
- [ ] Yes
- [x] No
#### Enforce privacy policies, procedures, and processes to properly document and maintain data: Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees, as needed.
- [x] Yes
- [ ] No
### System and Organizations Controls (SOC type 1, SOC type 2)
#### User access policies are established: Controls of Least Privilege and separation of duties are not currently in place; all employees have access to internally stored data.
- [ ] Yes
- [x] No
#### Sensitive data (PII/SPII) is confidential/private: Encryption is not currently used to better ensure the confidentiality of PII/SPII.
- [ ] Yes
- [x] No
#### Data integrity ensures the data is consistent, complete, accurate, and has been validated: Data integrity is in place.
- [x] Yes
- [ ] No
#### Data is available to individuals authorized to access it: While data is available to all employees, authorization needs to be limited to only the individuals who need access to it to do their jobs.
- [ ] Yes
- [x] No
### Recommendations: 
#### Multiple controls need to be implemented to improve Botium Toys’ security posture and better ensure the confidentiality of sensitive information, including: Least Privilege, disaster recovery plans, password policies, separation of duties, an IDS, ongoing legacy system management, encryption, and a password management system. To address gaps in compliance, Botium Toys needs to implement controls such as Least Privilege, separation of duties, and encryption. The company also needs to properly classify assets, to identify additional controls that may need to be implemented to improve their security posture and better protect sensitive information.
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####

