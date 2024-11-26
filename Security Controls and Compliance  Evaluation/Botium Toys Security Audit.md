# Controls and Compliance Assessment 

## Scenario

### This is based on a fictional company

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Controls Assessment Checklist

*<ins>Select "Yes" or "No" to answer the question: Does Botium Toys currenly have this control in place?</ins>*

| Yes | No | Control | Explanation |
| :-: | :-: | :- | :- |
| ~~Yes~~ | `No` | Least Priviledge | Presently, all employees have access to customer data. Access privileges need to be restricted to minimize the risk of a data breach. |
| ~~Yes~~ | `No` | Disaster recovery plans | There is no disaster recovery plan in place. This needs to be addressed to ensure the business can continue operating in case of unexpected disruptions. |
| ~~Yes~~ | `No` | Password policies | Employee password requirements are too weak, increasing the likelihood that a threat actor could compromise sensitive data or other assets through employee devices or the internal network. |
| ~~Yes~~ | `No` | Separation of duties | PTo reduce the risk of fraud and unauthorized access to critical data, operational duties and payroll management should be separated, as the CEO currently handles both. |
| `Yes` | ~~No~~ | Firewalls | The firewall is configured to block traffic based on a well-defined set of security rules. |
| ~~Yes~~ | `No` | Intrusion detection system (IDS) | The IT department should implement an intrusion detection system (IDS) to identify potential intrusions from threat actors. |
| ~~Yes~~ | `No` | Backups | Backups of critical data must be maintained by the IT department to ensure business continuity in the event of a breach or data loss. |
| `Yes` | ~~No~~ | Antivirus software | Antivirus software is installed and monitored regularly to protect the company’s systems. | 
| ~~Yes~~ | `No` | Manual monitoring, maintenance, and intervention for legacy systems| Legacy systems are listed in the asset inventory and are monitored and maintained, but there is no established schedule for these tasks. Clear intervention policies and procedures need to be implemented to reduce the risk of a security breach.|
| ~~Yes~~ | `No` | Encryption | Encryption is not currently being used, which leaves sensitive information vulnerable. Implementing encryption would greatly enhance confidentiality. |
| ~~Yes~~ | `No` | Password management system | A password management system is not in place. Introducing one would improve both the IT department’s efficiency and employee productivity when resolving password issues. |
| `Yes` | ~~No~~ | Locks(offices, storefront, warehouse) | The store’s physical location, including its main offices, storefront, and warehouse, has sufficient locks in place for security. |
| `Yes` | ~~No~~ | Closed-circuit television (CCTV) surveillance | CCTV cameras are installed and fully operational at the store’s physical location. |
| `Yes` | ~~No~~ | Fire detection/prevention (fire alarm, sprinkler system, etc.)| Fire detection and prevention systems at the physical location are functioning properly. |

## Compliance Checklist

**<ins>Payment Card Industry Data Security Standard (PCI DSS)</ins>**

*<ins>Select "Yes" or "No" to answer the question: Does Botium Toys currenly adhrere to this compliance best practice?</ins>* 

| Yes | No | Best Practice | Explanation |
| :-: | :-: | :- | :- |
| ~~Yes~~ | `No` | Only authorized users have access to customers' credit card information. | All employees currently have access to the company’s internal data, which poses a significant security risk.  |
| ~~Yes~~ | `No` | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | Customers’ credit card information is not encrypted, and employees currently have unrestricted access to this data. |
| ~~Yes~~ | `No` | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | Encryption must be implemented to protect financial information. | 
| ~~Yes~~ | `No` | Adopt secure password management policies. | Current password policies are insufficient, and the company lacks a robust password management system to enforce strong, unique credentials for all users. |

**<ins>General Data Protection Regulation (GDPR)</ins>**
  
| Yes | No | Best Practice | Explanation |
| :-: | :-: | :- | :- |
| ~~Yes~~ | `No` | E.U. customers' data is kept private/secured. | The company does not currently employ encryption techniques to enhance the confidentiality of customers' financial information. |
| `Yes` | ~~No~~ | There is a plan in place to notify E.U customers within 72 hours if their data is compromised/there is a breach.| A plan is in place to notify all affected E.U. customers within 72 hours of any confirmed data breach, in compliance with GDPR regulations. |
| ~~Yes~~ | `No` | Ensure data is properly classified and inventoried. | Comprehensive inventory of current assets has been done, but further classification is necessary to accurately assess their value and potential risks. |
| `Yes` | ~~No~~ | Enforce privacy policies procedures, and processes to properly document and maintain data.| The company has established comprehensive privacy policies, procedures, and processes that are consistently enforced across the IT team and other relevant employees to safeguard sensitive information. |

**<ins>System and Organizations Controls (SOC type 1, SOC type 2)</ins>**

| Yes | No | Best Practice | Explanation |
| :-: | :-: | :- | :- |
| ~~Yes~~ | `No` | User access policies are established. | Controls for Least Privilege and separation of duties are not implemented, resulting in all employees having access to internally stored data. These measures should be established to restrict access based on job responsibilities. |
| ~~Yes~~ | `No` | Sensitive data (PII/SPII) is confidential/private | Encryption is not currently in use, leaving PII and SPII vulnerable. Implementing encryption would significantly enhance the confidentiality of this sensitive information. | 
| `Yes` | ~~No~~ | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | Data integrity measures are implemented and functioning effectively. |
| ~~Yes~~ | `No` | Data is available to individuals authourized to access it. | Currently, data is accessible to all employees. Access should be restricted so that only individuals whose roles require it have authorization. |

## Recommendations

- To enhance Botium Toys' security posture and ensure better protection of sensitive information, several controls should be implemented. These include Least Privilege, disaster recovery plans, password policies, separation of duties, an Intrusion Detection System (IDS), effective legacy system management, encryption, and a password management system.
  
- To address compliance gaps, Botium Toys should prioritize controls like Least Privilege, separation of duties, and encryption. Additionally, the company must properly classify its assets to identify and implement any further necessary controls, strengthening its overall security framework and safeguarding confidential information.
