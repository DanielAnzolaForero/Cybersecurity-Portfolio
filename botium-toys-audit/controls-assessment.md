# Botium Toys – Controls Assessment  
**Internal IT Audit – NIST CSF Alignment**  
**Author:** Daniel Anzola  

--------------------------------------------------------------------------------------------------------------------------------

## 1. Overview  
This document summarizes the control assessment performed for Botium Toys as part of an internal IT audit. 
The evaluation is based on the company’s current assets and the control categories defined in standard cybersecurity frameworks.
Controls were reviewed to determine whether they should be implemented and to assign a priority level.

--------------------------------------------------------------------------------------------------------------------------------

## 2. Assets in Scope  
The assessment covers all IT-managed assets, including:

- On-premises equipment  
- Employee devices (laptops, desktops, mobile phones, peripherals)  
- Remote workstations  
- Surveillance systems  
- Core systems and services (accounting, security, telecom, database, ecommerce, inventory)  
- Internet access and internal network  
- Vendor access  
- Data center hosting and storage  
- Badge readers  
- Legacy systems requiring manual oversight  

--------------------------------------------------------------------------------------------------------------------------------

## 3. Administrative Controls  

| Control Name | Control Purpose | Implement? | Priority |
|--------------|----------------|------------|----------|
| Least Privilege | Restricts access to only what is required for each role. | Yes | High |
| Disaster Recovery Plans | Ensures business continuity during incidents and supports rapid restoration. | Yes  | High |
| Password Policies | Defines password complexity to reduce credential-related attacks. | Yes  | High |
| Access Control Policies | Protects confidentiality and integrity through role-based access rules. | Yes  | High |
| Account Management Policies | Reduces risks associated with inactive, former, or mismanaged accounts. | Yes  | Medium |
| Separation of Duties | Prevents excessive privilege concentration that could enable misuse. | Yes  | High |

------------------------------------------------------------------------------------------------------------------------------

## 4. Technical Controls  

| Control Name | Control Purpose | Implement? | Priority |
|--------------|----------------|------------|----------|
| Firewall | Already implemented; filters malicious or unwanted traffic. | N/A | N/A |
| Intrusion Detection System (IDS) | Detects anomalous or suspicious activity on the network. | Yes | High |
| Encryption | Secures sensitive information, especially transactions and user data. | Yes | High |
| Backups | Supports recovery and reduces downtime during incidents. | Yes | High |
| Password Management System | Provides secure password recovery, resets, and account lockout notifications. | Yes  | Medium |
| Antivirus Software | Detects and contains known threats. | Yes  | High |
| Manual Monitoring for Legacy Systems | Required to mitigate risks associated with outdated systems. | Yes  | High |

---

## 5. Physical Controls  

| Control Name | Control Purpose | Implement? | Priority |
|--------------|----------------|------------|----------|
| Time-Controlled Safe | Minimizes the impact of unauthorized physical access. | Yes  | Low |
| Adequate Lighting | Deters physical threats by reducing concealment opportunities. | Yes  | Low |
| CCTV Surveillance | Supports both prevention and post-incident investigations. | Yes  | High |
| Locking Cabinets (Network Gear) | Prevents unauthorized access to core network equipment. | Yes  | Medium |
| Alarm System Signage | Acts as a deterrent by increasing perceived risk for attackers. | Yes  | Low |
| Physical Locks | Secures physical and digital infrastructure. | Yes  | High |
| Fire Detection & Suppression | Reduces risk of physical damage to assets and facilities. | Yes  | Medium |

---

## 6. Summary  
Most controls need to be implemented due to significant gaps in asset management, compliance requirements, and existing security processes. Priority levels indicate areas requiring immediate action, especially those involving identity access, disaster recovery, and threat detection.

