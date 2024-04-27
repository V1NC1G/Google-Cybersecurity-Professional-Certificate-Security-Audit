# Google Cybersecurity Professional Certificate - Security Audit

## Table of Contents

- [Scenario](#scenario)
- [Task](#task)
- [Scope, Goals, and Risk Assessment Report](#botium-toys-scope-goals-and-risk-assessment-report)
  - [Scope & Goals of the Audit](#scope-and-goals-of-the-audit)
  - [Current Assets](#current-assets)
  - [Risk Assessment](#risk-assessment)
- [Controls and Compliance Checksheet](#controls-and-compliance-checksheet)
  - [Controls Assessment Checklist](#controls-assessment-checklist)
  - [Compliance Checklist](#compliance-checklist)
    - [PCI DSS](#payment-and-card-industry-data-security-standard-pci-dss)
    - [GDPR](#general-data-protection-regulation)
    - [SOC type 1 & SOC type 2](#system-and-organizations-controls-soc-type-1-soc-type-2)
  - [Recommendations](#recommendations)
- [Learning Experience](#learning-experience)

## Scenario

_This scenario is based on a fictional company:_

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

## Task

The task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.

## Botium Toys: Scope, Goals, and Risk Assessment Report

### Scope and goals of the audit

**Scope**: The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

**Goals**: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to improve Botium Toys’ security posture.

### Current assets

Assets managed by the IT Department include:

- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, e-commerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

### Risk assessment

**Risk description**
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

**Control best practices**
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

**Risk score**
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

**Additional comments**
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

## Controls and Compliance Checksheet

Listed in the table are controls and compliance best practices that should be determined, as part of the audit, if it is in place.

### Controls Assessment Checklist

| **YES** | **NO** | **CONTROL**                                                         |
| ------- | ------ | ------------------------------------------------------------------- |
|         | X      | Least Privilege                                                     |
|         | X      | Disaster recovery plans                                             |
|         | X      | Password policies                                                   |
|         | X      | Separation of duties                                                |
| X       |        | Firewall                                                            |
|         | X      | Intrusion detection system (IDS)                                    |
|         | X      | Backups                                                             |
| X       |        | Antivirus software                                                  |
|         | X      | Manual monitoring, maintenance, and intervention for legacy systems |
|         | X      | Encryption                                                          |
|         | X      | Password management system                                          |
| X       |        | Locks (offices, storefront, warehouse)                              |
| X       |        | Closed-circuit television (CCTV) surveillance                       |
| X       |        | Fire detection/prevention (fire alarm, sprinkler system, etc.)      |

### Compliance Checklist

#### Payment and Card Industry Data Security Standard (PCI DSS)

| **YES** | **NO** | **CONTROL**                                                                                                  |
| ------- | ------ | ------------------------------------------------------------------------------------------------------------ |
|         | X      | Only authorized users have access to customers’ credit card information.                                     |
|         | X      | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|         | X      | Implement data encryption procedures to better secure credit card transaction touchpoints and data.          |
|         | X      | Adopt secure password management policies.                                                                   |

#### General Data Protection Regulation

| **YES** | **NO** | **CONTROL**                                                                                                       |
| ------- | ------ | ----------------------------------------------------------------------------------------------------------------- |
|         | X      | E.U. customers’ data is kept private/secured.                                                                     |
| X       |        | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|         | X      | Implement data encryption procedures to better secure credit card transaction touchpoints and data.               |
|         | X      | Ensure data is properly classified and inventoried.                                                               |
|         | X      | Enforce privacy policies, procedures, and processes to properly document and maintain data.                       |

#### System and Organizations Controls (SOC Type 1, SOC Type 2)

| **YES** | **NO** | **CONTROL**                                                                                |
| ------- | ------ | ------------------------------------------------------------------------------------------ |
|         | X      | User access policies are established.                                                      |
|         | X      | Sensitive data (PII/SPII) is confidential/private.                                         |
|         | X      | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|         | X      | Data is available to individuals authorized to access it.                                  |

### Recommendations

- Follow the principle of least privilege and separation of duties where employees within the company are given the least amount of access to assets/data but still be able to accomplish their day-to-day tasks.
- Initiate a company-wide password reset and set password polices to achieve a strong password for all users. At the same time, establish a password management system to enforce these policies.
- Establish a disaster recovery plan and backup as to not to lose high-risk assets in case a breach or system failure occurs. This would also factor directy to data integrity as maintaining data integrity involves safeguarding an organization's data from loss and leaks.
- Make use of an IDS to monitor system activity to detect intrusions or unauthorized access.
- An additional tool that can be used by the organization are SIEM tools. This would improve the effectiveness in the detection and identification of security breaches.
- Establish standard internal guidelines in monitoring, maintaining, and intervening on legacy systems. It would be better to take priority in setting up guidelines first on legacy systems that are affecting high-risk assets.

## Learning Experience

There was certainly a lot that goes into doing an audit. From knowing different types of controls and thinking about how it would bolster the security of an organization, to compliance where those controls are closely tied together.

This mock audit made me think about how broad cybersecurity really is and that having good foundational knowledge can help a security professional prepare, detect, analyze, and mitigate risks, threats, and vulnerabilites.

The mock audit also made me look back at some of my notes as to check if there are other controls that I could implement to further improve the security posture of the organization.
