# Controls and Compliance Assessment 

## Case Study

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Scenario
Botium Toys: Scope, Goals, and Risk Assessment Report

### Scope 

The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

### Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to  improve Botium Toys’ security posture.

### Current assets
Assets managed by the IT Department include: 
* On-premises equipment for in-office business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring 

### Risk assessment

#### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

#### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

#### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

#### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

#### Additional Info 

In Cybersecurity, control types can be classified in three ways: 
1. Administrative/Managerial controls
2. Technical controls
3. Physical/Operational controls

Control types (providing defense and protecting assets) include, but are not limited to:
1. Preventative (preventing an incident from occurring in the first place)
2. Corrective (restoring an asset after an incident)
3. Detective (Determining whether an incident has occurred or is in progress)
4. Deterrent (Discouraging attacks)

## Controls Assessment Checklist

Does Botium Toys currenly have this control in place? 

| Yes | No | Control | Explanation |
| :-: | :-: | :-: | :- |
| Yes | `No` | Presently, all employees have access to customer data. Access privileges need to be restricted to minimize the risk of a data breach. |
| Yes | `No` | There is no disaster recovery plan in place. This needs to be addressed to ensure the business can continue operating in case of unexpected disruptions. |
| Yes | `No` | Password policies | Employee password requirements are too weak, increasing the likelihood that a threat actor could compromise sensitive data or other assets through employee devices or the internal network. |
| Yes | `No` | Separation of duties | PTo reduce the risk of fraud and unauthorized access to critical data, operational duties and payroll management should be separated, as the CEO currently handles both. |
| `Yes` | No | Firewalls | The firewall is configured to block traffic based on a well-defined set of security rules. |
| Yes | `No` | Intrusion detection system (IDS) | The IT department should implement an intrusion detection system (IDS) to identify potential intrusions from threat actors. |
| Yes | `No` | Backups | Backups of critical data must be maintained by the IT department to ensure business continuity in the event of a breach or data loss. |
| `Yes` | No | Antivirus software | Antivirus software is installed and monitored regularly to protect the company’s systems. | 
| Yes | `No` | Manual monitoring, maintenance, and intervention for legacy systems| Legacy systems are listed in the asset inventory and are monitored and maintained, but there is no established schedule for these tasks. Clear intervention policies and procedures need to be implemented to reduce the risk of a security breach.|
| Yes | `No` | Encryption | Encryption is not currently being used, which leaves sensitive information vulnerable. Implementing encryption would greatly enhance confidentiality. |
| Yes | `No` | Password management system | A password management system is not in place. Introducing one would improve both the IT department’s efficiency and employee productivity when resolving password issues. |
| `Yes` | No` | Locks(offices, storefront, warehouse) | The store’s physical location, including its main offices, storefront, and warehouse, has sufficient locks in place for security. |
| `Yes` | No | Closed-circuit television (CCTV) surveillance | CCTV cameras are installed and fully operational at the store’s physical location. |
| `Yes` | No | Fire detection/prevention (fire alarm, sprinkler system, etc.)| Fire detection and prevention systems at the physical location are functioning properly. |

## Compliance Checklist
Does Botium Toys currenly adhrere to this compliance best practice? 

* Payment Card Industry Data Security Standard (PCI DSS)

| Yes/No | Best Practice | Explanation |
| :-: | :-: | :- | :- |
| `Yes` | `No` | Authorized users can access to customer's credit card. | At the moment, all employees have access to it which is a bad practice in the business.  |
| `Yes` | `No` | Credit card is stored in a secure environment. | It is not encrypted and violates the law and regulations. |
| `Yes` | `No` | Encryption is secured. | No, the encryption has not taken place yet. | 

* GDPR
  
| Yes/No | Best Practice | Explanation |
| :-: | :-: | :- | :- |
| `Yes` | `No` | EU customers are kept secured. | The organization does not apply GDPR practice. Thus, it puts them at risk of being fined by the EU government. |
| `Yes` | `No` | Privacy policies are maintained properly.| According to the scenario, it has been enforced by the IT Team members and other staff. |

* System and Organizations Controls 

| Yes/No | Best Practice | Explanation |
| :-: | :-: | :- | :- |
| `Yes` | `No` | User access policies are established | Employees have access to internally stored data which means the access policy has not been applied. |
| `Yes` | `No` | Data integrity is consistent, complete, accurate | Data integrity is in place. | 
| `Yes` | `No` | Data is available to authorized users | Currently, all the employees can access all the data. |

## Recommendations

- To enhance Botium Toys' security posture and ensure better protection of sensitive information, several controls should be implemented. These include Least Privilege, disaster recovery plans, password policies, separation of duties, an Intrusion Detection System (IDS), effective legacy system management, encryption, and a password management system.
- To address compliance gaps, Botium Toys should prioritize controls like Least Privilege, separation of duties, and encryption. Additionally, the company must properly classify its assets to identify and implement any further necessary controls, strengthening its overall security framework and safeguarding confidential information.